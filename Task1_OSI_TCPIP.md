# 🧠 Task 1: Understand OSI & TCP/IP Models
## Week 1 - Networking Challenge (90 Days of DevOps 2025)

---

### 🌍 Overview
In networking, data travels between devices through different layers that handle specific tasks.  
Two major models describe how this communication happens:
- **OSI Model (Open Systems Interconnection)**
- **TCP/IP Model (Transmission Control Protocol / Internet Protocol)**

---

## 🧩 OSI Model (7 Layers)

| Layer No. | Layer Name        | Description | Real-World Example |
|------------|------------------|--------------|--------------------|
| 7️⃣ | **Application Layer** | User-facing applications and network services | HTTP, HTTPS, SMTP, FTP |
| 6️⃣ | **Presentation Layer** | Data encryption, compression, translation | SSL/TLS encryption, JPEG, ASCII |
| 5️⃣ | **Session Layer** | Manages sessions between devices | Maintaining login sessions, API calls |
| 4️⃣ | **Transport Layer** | Ensures reliable data delivery | TCP, UDP |
| 3️⃣ | **Network Layer** | Handles routing and addressing | IP, ICMP, Routers |
| 2️⃣ | **Data Link Layer** | Transfers data between nodes in the same network | Ethernet, MAC addresses |
| 1️⃣ | **Physical Layer** | Deals with physical connections and signals | Cables, Wi-Fi, Hubs |

📝 **Example:**  
When you open a website:
1. Your browser (Application Layer) sends an HTTP request.  
2. It’s encrypted (Presentation Layer).  
3. The session is maintained (Session Layer).  
4. TCP ensures reliable delivery (Transport Layer).  
5. IP routes the data (Network Layer).  
6. Ethernet sends it over LAN (Data Link).  
7. Finally, it’s transmitted via Wi-Fi or cable (Physical).

---

## 🌐 TCP/IP Model (4 Layers)

| Layer No. | Layer Name        | Description | Real-World Example |
|------------|------------------|--------------|--------------------|
| 4️⃣ | **Application Layer** | User applications and services | HTTP, DNS, SSH, FTP |
| 3️⃣ | **Transport Layer** | Manages end-to-end communication | TCP, UDP |
| 2️⃣ | **Internet Layer** | Handles IP addressing and routing | IP, ICMP |
| 1️⃣ | **Network Access Layer** | Physical network transmission | Ethernet, Wi-Fi |

🧩 **Note:**  
The TCP/IP model combines some OSI layers:
- Application + Presentation + Session → **Application Layer**  
- Data Link + Physical → **Network Access Layer**

---

## 🔁 Comparison: OSI vs TCP/IP

| Feature | OSI Model | TCP/IP Model |
|----------|------------|---------------|
| Layers | 7 | 4 |
| Developed By | ISO | ARPANET (US DoD) |
| Example Protocols | HTTP, FTP, TCP, IP | HTTP, TCP, IP, SSH |
| Usage | Theoretical model | Practical implementation |
| Focus | Conceptual framework | Real-world networking |

---

## 📚 Summary
- The **OSI Model** explains *how data flows conceptually*.  
- The **TCP/IP Model** shows *how data actually moves on the internet*.  
- Both models help DevOps engineers understand how services communicate, troubleshoot issues, and configure systems efficiently.

---

## 🧾 Learning Outcome
✅ Understood the OSI and TCP/IP models  
✅ Identified real-world protocols used at each layer  
✅ Learned how data travels through layers to deliver applications like websites or APIs  

---

⭐ *Part of Week 1 - 90 Days of DevOps Challenge (Networking Fundamentals)*  
#Networking #DevOps #OSIModel #TCPIP #90DaysOfDevOps
