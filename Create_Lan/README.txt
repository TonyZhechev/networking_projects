# PACKET TRACER - CREATE A LAN 🖥️📡

## 🔹 OVERVIEW  
IN THIS PROJECT, YOU WILL LEARN HOW TO **SET UP A SIMPLE LOCAL AREA NETWORK (LAN)** USING CISCO PACKET TRACER.  

## 🔹 OBJECTIVES  
✅ CONNECT NETWORK DEVICES AND HOSTS  
✅ CONFIGURE DEVICES WITH IPV4 ADDRESSING  
✅ VERIFY THE END DEVICE CONFIGURATION AND CONNECTIVITY  
✅ USE NETWORKING COMMANDS TO VIEW HOST INFORMATION  

## 🔹 NETWORK DIAGRAM  
📌 **HERE IS A SIMPLE DIAGRAM THAT SHOWS HOW THE NETWORK IS BUILT.**  
📌 **EASY TO UNDERSTAND EVEN FOR BEGINNERS!**  

![Network Diagram](network_diagram.png)

## 🔹 DEVICES USED  
📌 **1 ROUTER**  
📌 **1 SWITCH**  
📌 **3 COMPUTERS (PCs)**  

## 🔹 IPV4 ADDRESSING SCHEME  
| DEVICE | INTERFACE | IP ADDRESS | SUBNET MASK |  
|--------|-----------|-------------|---------------|  
| **Router** | G0/0 | 192.168.1.1 | 255.255.255.0 |  
| **PC1** | NIC | 192.168.1.10 | 255.255.255.0 |  
| **PC2** | NIC | 192.168.1.11 | 255.255.255.0 |  
| **PC3** | NIC | 192.168.1.12 | 255.255.255.0 |  
| **Switch** | - | No IP Assigned | - |  

## 🔹 STEPS TO CONFIGURE THE NETWORK  

### **🛠️ STEP 1: CONNECT DEVICES**  
1️⃣ DRAG AND DROP THE FOLLOWING DEVICES FROM PACKET TRACER:  
   - 1 ROUTER  
   - 1 SWITCH  
   - 3 PCs  
2️⃣ CONNECT THEM USING **COPPER STRAIGHT-THROUGH CABLES**.  
3️⃣ CONNECT PCs TO THE SWITCH AND THE SWITCH TO THE ROUTER.  

---

### **🛠️ STEP 2: ASSIGN IP ADDRESSES**  
1️⃣ GO TO EACH **PC** AND SET A STATIC IP ADDRESS:  
   - CLICK ON PC1 → DESKTOP → IP CONFIGURATION → ENTER **192.168.1.10**  
   - CLICK ON PC2 → DESKTOP → IP CONFIGURATION → ENTER **192.168.1.11**  
   - CLICK ON PC3 → DESKTOP → IP CONFIGURATION → ENTER **192.168.1.12**  

2️⃣ ON THE **ROUTER**, CONFIGURE THE **GIGABIT ETHERNET 0/0 INTERFACE**:  
```bash
Router> enable
Router# configure terminal
Router(config)# interface GigabitEthernet0/0
Router(config-if)# ip address 192.168.1.1 255.255.255.0
Router(config-if)# no shutdown
Router(config-if)# exit
Router(config)# exit