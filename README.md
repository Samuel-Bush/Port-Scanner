# Port-Scanner

Basic project that scans ports (of a practice site) to enhance my learning of cybersecurity fundamentals.

# What it does

- Attempts to secure a connection with each port listed inside the dictionary.
- Ouputs all of the open ports on a device or site.
  
# How it works 

- Using the a TCP socket, this program attempts to establish a connection with each of the ports in the dictionary.
- The timeout is set to 1 second, if the TCP socket cannot connect within the timeframe, it will conclude the port is closed.
- If a port is open, the function will return true, and the specific port will be added to the list of open ports.
  
# What I learnt

- Program logic, in particular the practical implementations of a defined function and a dictionary (over a list/tuple)
- Uses of the ports and the common ports that would be considered security vulnreabilities.

# Note

This is a educational project for port scanning of practice sites (e.g. scanme.nmap.org) or your own devices. Scanning sites or devices unauthorised is generally illegal under the computer misuse act 1990.

# Thank you for reading
