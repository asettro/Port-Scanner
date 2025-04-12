# Port Scanner Script

Bash script that checks if a host is online and scans for open ports within a specified range.

## How to Use

1. Clone the repository or download the script.

2. Open a terminal and run the script with the following format:

   ```
   ./port_scanner.sh <host> <MIN_PORT> <MAX_PORT>

    <host>: The IP address or hostname of the target

    <MIN_PORT>: The starting port number

    <MAX_PORT>: The ending port number

## Example:
```
./port_scanner.sh 192.168.1.1 80 100
```
This would scan ports from 80 to 100 on the host 192.168.1.1.

## Notes
1. This script is for fun and learning. It's not meant for large-scale or professional use.
   
2. It uses nc for port scanning and may be blocked by firewalls.
   
3. The script checks if the target is online using a simple ping before scanning ports
   
4. This script does not support scanning subnets. It is designed to scan a single host at a time, not a range of IP addresses or subnets.
