TASK 1 - BASIC NETWORK SNIFFER

To run this code, follow these steps:

1. Install Dependencies:
Ensure you have the required Python packages installed. You can use pip to install them:

pip install scapy psutil prettytable colorama

scapy: For packet sniffing and manipulation.
psutil: To fetch network interface details.
prettytable: To format tables.
colorama: To colorize terminal output.

2. Run the Code:
Save the code to a Python file, for example, packet_sniffer.py. Open a terminal or command prompt and navigate to the directory where the file is saved.

Run the script with:

python packet_sniffer.py
![sniff command](https://github.com/user-attachments/assets/43914763-93af-40a2-b577-7edc2f6c4508)


3. Permissions:
Packet sniffing often requires elevated privileges. If you're running the script on a Unix-based system (like Linux or macOS), you might need to use sudo:

sudo python packet_sniffer.py
![selecting interface](https://github.com/user-attachments/assets/a7f4c8f3-42fd-4255-9614-0dbab8a44d07)

![sniffing](https://github.com/user-attachments/assets/f07509a1-8d71-4a81-bc38-cf5587bab2be)

On Windows, running the script in an administrator command prompt might be necessary.

![5](https://github.com/user-attachments/assets/a12c8d4c-f8db-4f76-98bb-c0c38f143dbe)


4. Verify Interface:
Make sure to enter the correct network interface name when prompted. You can list available interfaces using ifconfig (Linux/macOS) or ipconfig (Windows).


5. Running Environment:
Ensure that no other processes are interfering with network traffic or access to the network interface.
