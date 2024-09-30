# Nmap Live Host Discovery
How to use Nmap to discover live hosts using ARP scan, ICMP scan, and TCP/UDP ping scan.

- The 1st and 2nd tasks were very straighforward, with some necessary introductory reading and simulations:
  - ![image](https://github.com/user-attachments/assets/cb985cb3-9574-4322-ae6f-52d86b0aed76)
  - ![image](https://github.com/user-attachments/assets/2bde3fe6-d3a2-40d2-baba-1f656456beab)

- For task 3, I've used the nmap -sL command for both questions, using subnet and range after the command, respectively:
  - nmap -sL subnet and nmap -sL range

- In task 4 there were additional simulations:
  - ![image](https://github.com/user-attachments/assets/32bc2cac-f261-4e3c-bffc-0f28fe494028)
  - ![image](https://github.com/user-attachments/assets/cfe80ea7-8535-4c6a-829e-12dbc9d77bb7)
  - Side note: In the 2nd question, the reason why it wasn't necessary additional ARP requests it's because the switch stored information from the 1st ARP request in it's Content Addressable Memory.

- The ARP query only works if the target is on the same subnet as yourself, hence the reason we're not able to discover all devices:
  - ![image](https://github.com/user-attachments/assets/cd0ae99b-c380-42b2-92d3-e4e80479313d)
  - ![image](https://github.com/user-attachments/assets/4b9476f9-f109-437d-8d2f-658d6d4e8004)

- For task 6, there's some required technical reading and questions to answer at the end, very straightforward.

- Task 7 discussed the TCP/UDP host discovery. Privileged users (root and sudoers) can send TCP SYN packets and don’t need to complete the TCP 3-way handshake even if the port is open. Unprivileged users have no choice but to complete the 3-way handshake if the port is open. UDP, however, doesn't trigger a response if the host is online. Read the documentation and answers the questions to complete the task.
Same process for task 8.
