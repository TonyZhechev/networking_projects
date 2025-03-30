# 🚀 Packet Tracer - Use FTP Services

## 📌 Project Overview
Welcome to the **Use FTP Services** project! 🌍 In this activity, you will **upload a file to an FTP server** and **download a file from an FTP server** using Packet Tracer. This project demonstrates how clients interact with an FTP server for file transfers over a network.

---

## 🎯 Objectives
✅ Upload a file to an FTP server 📤  
✅ Download a file from an FTP server 📥  
✅ Rename files on an FTP server 📝  
✅ Delete a file from an FTP server ❌  

---

## 🖥️ Network Topology Diagram
📌 **Diagram Below:** This shows how the client and server interact over FTP.

🚀 *(Insert Image Here - "ftp_services_diagram.png")* 🚀

---

## 🔧 Instructions
### 🔹 Part 1: Upload a File to an FTP Server
#### 1️⃣ Locate the File
- Open **PC-A** 🖥️
- Go to **Desktop > Command Prompt**
- Type `dir` to list files ➡️ Check for `sampleFile.txt` 📄

#### 2️⃣ Connect to the FTP Server
- Type `ftp 209.165.200.226` 🌍
- Enter credentials:
  - **Username:** `student`
  - **Password:** `class`

#### 3️⃣ Upload the File
- Use `put sampleFile.txt` to upload 📤
- Confirm upload using `dir`

---

### 🔹 Part 2: Download a File from the FTP Server
#### 1️⃣ Rename the File
- Use `rename sampleFile.txt sampleFile_FTP.txt` 📝
- Confirm with `dir`

#### 2️⃣ Download the File
- Use `get sampleFile_FTP.txt` to retrieve the file 📥

#### 3️⃣ Delete the File (Bonus)
- Use `delete sampleFile_FTP.txt` ❌
- Confirm with `dir`
- Exit using `quit`

---

## 📂 Repository Structure
```
📂 networking_projects
 ├── 📁 FTP_Services_Project
 │   ├── 📄 README.md  (This file!)
 │   ├── 📄 LICENSE    (MIT License)
 │   ├── 📷 ftp_services_diagram.png  (Network Diagram)
 │   ├── 📂 PacketTracer_Files
 │   │   ├── ftp_project.pkt  (Packet Tracer Lab File)
```

---

## 📝 License
📜 This project is licensed under the **MIT License** – see the LICENSE file for details.

---

## 💡 Additional Enhancements
🔹 **Make it Interactive:** Add screenshots from Packet Tracer to your repo 📸  
🔹 **Expand the Project:** Set up an **HTTP or DNS server** for further learning 🌎  
🔹 **Automate FTP Commands:** Write a simple script to automate file transfers 🤖  

Happy Networking! 🌐💻🚀

