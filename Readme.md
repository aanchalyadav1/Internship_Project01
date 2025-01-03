# Sniffing Attack using Wireshark

As a budding ethical hacker, your ability to analyze network traffic is a superpower. Enter Wireshark, the open-source packet analyzer that grants you unparalleled visibility into the data flowing through networks. Let’s embark on a journey of packet interception and analysis!

# 🦈 What is Wireshark?
Wireshark is a free and open-source network packet analyzer that lets you capture and inspect the data traveling back and forth on your network. With Wireshark, you become a digital detective, observing network conversations, identifying vulnerabilities, and understanding communication patterns.

Note: These tools are very huge and have more functionalities which can’t be written in one blog. So better to explore and know about the tool.

# 🛠️ Setting Up Wireshark
- Download and install Wireshark from the official website (Pre-installed in Kali Linux).
- Launch Wireshark and grant it the necessary privileges to capture network traffic.

# 🔧 Capturing Network Traffic
- Choose your network interface (Ethernet, Wi-Fi) for packet capture.
- Click “Start” to initiate packet capture and witness the live flow of data.

# 🔍 Analyzing Packets — Unveiling the Intricacies
Wireshark captures packets, but the real magic lies in analyzing their contents. Let’s explore some key features:

1. Packet Display Filter — Use filters to focus on specific packets. For example, “http” filters display only HTTP traffic.
2. Packet List Pane — Shows captured packets, including their source, destination, and protocols.
3. Packet Details Pane — Provides a deep dive into packet contents, revealing headers, payloads, and more.

# # 🔒 Practical Exercise: Sniffing Attack on “http://testphp.vulnweb.com/”
- Begin packet capture and visit the target URL in your browser.
- Analyze captured packets to uncover potentially sensitive information, such as login credentials.

# 🔍 Filtering for Relevant Information
- Use display filters to isolate packets containing specific information, like “http.host == testphp.vulnweb.com.”

#🌟 Advanced Analysis — Follow TCP Stream
- Right-click on a packet and select “Follow” > “TCP Stream” to reconstruct and analyze a full conversation.

# 💡 Expert Tip: Protecting Yourself During Packet Capture
Never capture packets on networks you don’t own or have permission to monitor. Ethical hacking operates within legal and ethical boundaries.
