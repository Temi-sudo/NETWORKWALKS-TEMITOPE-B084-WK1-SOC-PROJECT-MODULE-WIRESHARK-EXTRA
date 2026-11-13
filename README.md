# NETWORKWALKS-TEMITOPE-B084-WK1-SOC-PROJECT-MODULE-WIRESHARK-EXTRA

### Security Operations Center (SOC) Analysis

### Real-time network packet analyzer with Wireshark 

## 🚀 Project Overview
<p>A SOC Analyst is a cybersecurity professional who monitors an organization's networks, endpoints, cloud tools, and data to detect, investigate, and respond to cyber threats.</p>
<p></p>Wireshark is a free, open-source network protocol analyzer that captures and inspects data packets traveling across a computer network in real time.</p>

## 🎯 Objectives
Our main objectives are listed as follows:

 * Identify an attack IP address.<br>
 * Follow a Transmission Control Protocol (TCP) Stream. <br>
 * Find hidden data in a TCP stream. <br>
 * Find usernames and passwords sent in clear text over HTTP. <br>
 * Catch a brute-force attack. <br>
 * Catch a call scammer. <br>

 ## 📌 Features
 Some features of SOC:
 
  1. Live packet capture. <br>
  2. Deep Protocol Dissection. <br>
  3. Payload & File Extraction <br>
  4. Network troubleshooting. <br>
  5. Detailed documentation. <br>

 ## ⚙️ Setting up your lab
  Step 1. Download and install the latest stable version of Wireshark from the official site: https://www.wireshark.org/download.html

  Step 2. Check the three boxes below for improved security and backward compatibility.
  
  <img width="467" height="320" alt="Step 2-Wireshark installation" src="https://github.com/user-attachments/assets/833058b5-ad43-4959-b8a6-370448a7ad13" /> <br>

  Step 3. Launch Wireshark

 ## 💡 Knowledgede Acquired
 1. Through this project, I learned how to install Wireshark.

 2. Know many packets Wireshark captured at a glance

 3. Learned new protocols like Session Initiation Protocol (SIP) INVITE, RTP, FTP

 4. Learned how to use the filter bar to navigate and find packet information easily 

 ## 🖥️ SOC Lab Practice and Results Using NETWORKWALKS Wireshark

 1. Identify the Attacker’s IP: https://networkwalks.com/wireshark-lab3/ <br>
<img width="1080" height="1700" alt="Lab 3 Result - Temitope Ogunji" src="https://github.com/user-attachments/assets/f0b2bf29-092c-474a-abd5-1789324e1212" /> <br>

2. Follow TCP Stream 1: https://networkwalks.com/wireshark-lab4/ <br>
<img width="1080" height="1700" alt="Lab 4 Result - Temitope Ogunji" src="https://github.com/user-attachments/assets/bbf36eec-31c7-4138-9e2d-8bcc015eaa4b" /> <br>

3. Follow TCP Stream, Part 2: https://networkwalks.com/wireshark-lab5/ <br>
<img width="1325" height="520" alt="Wireshark Lab 5" src="https://github.com/user-attachments/assets/a8f3dc70-8665-4d49-829e-3b0f564722ff" /> <br>

<img width="1080" height="1700" alt="Lab 5 Result - Temitope Ogunji" src="https://github.com/user-attachments/assets/6d6f25c7-3ec4-46e5-aeb1-9cfd8a1fe13f" /> <br>

4. HTTP Plain Text Credentials: https://networkwalks.com/wireshark-lab6/ <br>
<img width="1344" height="450" alt="Wireshark Lab 6" src="https://github.com/user-attachments/assets/47392a7a-0179-4dc7-912e-a89ebfd4dd58" /> <br>

<img width="1080" height="1700" alt="Lab 6 Result - Temitope Ogunji" src="https://github.com/user-attachments/assets/cb57fee5-0d37-4a3f-a165-a481c2f2aad1" /> <br>

5. Catch the Brute Force Attacker: https://networkwalks.com/wireshark-lab7/ <br>
<img width="1319" height="445" alt="Wireshark Lab 7" src="https://github.com/user-attachments/assets/a8d32e90-bff5-4e62-b8d7-643851d2c66d" /> <br>

<img width="1080" height="1700" alt="Lab 7 Result - Temitope Ogunji" src="https://github.com/user-attachments/assets/37c21d77-e2ab-4a83-9c59-f63cd7c90de9" /> <br>

6. Catch the Call Scammer: https://networkwalks.com/wireshark-lab8/ <br>
<img width="1315" height="571" alt="Wireshark Lab 8" src="https://github.com/user-attachments/assets/68a545fa-9b5c-4c40-887d-059b891fff52" />

<img width="1080" height="1700" alt="Lab 8 Result - Temitope Ogunji" src="https://github.com/user-attachments/assets/5fcef0de-2d40-4a6f-9659-8974702fdfaf" /> <br>


 ## 🖥️ SOC Practice and Results using live Wireshark on my computer

 ## 📝 Overview
In this lab, I will capture my own Wi-Fi traffic while opening a website and read information from the packets. <br>

 ## Task 
Capture your own Wi-Fi traffic with Wireshark on your Windows laptop while you open networkwalks.com, then find the six answers below in the packets. <br>
Website: https://networkwalks.com 

Questions: 
1. What is the IP address of your own laptop? 
2. What is the IP address of your DNS server? 
3. What is the IP address of the website networkwalks.com? 
4. Which website name (Server Name) is sent in the TLS Client Hello? 
5. Which server port is used for the secure connection? 
6. Which TLS version does the website use?

Solution: <br>
Screenshot of Wireshark showing the DNS answer with the website IP <br>
<img width="991" height="660" alt="Lab 4-Live Wireshark Practice-5" src="https://github.com/user-attachments/assets/51272ade-1c48-4512-a763-624d56e006fe" /> <br>





