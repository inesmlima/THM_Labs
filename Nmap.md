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

