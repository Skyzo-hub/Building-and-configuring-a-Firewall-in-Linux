# Building and configuring a Firewall in Linux

# Objective: 

The objective of this project is to build and configure a robust firewall solution in a Linux environment to enhance network security. The lab will focus on deploying iptables or firewalld (depending on the chosen distribution) to control network traffic, define security rules, and block unauthorized access.

### Skills Learned
- Linux system administration.
- Network Security
- Firewall Configuration
- Logging and monitoring
- Documentation

### Tools Used
- Ubuntu Linux, UFW (Uncomplicated Firewall).
- Terminal CLI

## Steps
![image](https://github.com/user-attachments/assets/0601458d-11eb-45d2-baaa-73b873c25bc7)

1. Install and Enable UFW
![image](https://github.com/user-attachments/assets/a1e019d8-bf49-4287-8f9b-b1af2ba7563f)
![image](https://github.com/user-attachments/assets/85425348-4c88-4e45-957f-ca6a2b8939e8)
2. Set default policies to deny all incoming connections and allow all outgoing connections.
![image](https://github.com/user-attachments/assets/436c37c3-8338-4a56-9f69-3881a77fddb2)
3. Add rules to allow necessary traffic: SSH (port 22), HTTP (port 80), HTTPS (port 443).
![image](https://github.com/user-attachments/assets/30c55198-0ab9-4bfa-bd36-08c2ad4fe2fa)
4. Allow a specific IP addresses
![image](https://github.com/user-attachments/assets/81de32b8-de78-431c-9a17-05fb227c6e92)
5. Enable logging to monitor firewall activity.
![image](https://github.com/user-attachments/assets/1ad5283b-c9ae-420a-bb33-cbc6cbc690e1)
7. Verify the current UFW rules
![image](https://github.com/user-attachments/assets/0cfc9943-9c77-41f0-9d72-8dbe8dd0651c)














