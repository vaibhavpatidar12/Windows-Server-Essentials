
---

# 🌐 IP Address

An **IP address** (Internet Protocol address) is a unique identifier assigned to each device connected to a network that uses the Internet Protocol for communication.

---

## **IP Versions**

### **1. IPv1 (Internet Protocol Version 1)**

* **Introduced**: 1970s (ARPANET)
* **Status**: Experimental, never standardized
* **Features**:

  * First implementation of IP
  * Basic packet-switching concepts

### **2. IPv2**

* **Introduced**: Early 1980s
* **Status**: Experimental
* **Features**:

  * Minor improvements over IPv1
  * Limited adoption

### **3. IPv3**

* **Introduced**: Early 1980s
* **Status**: Experimental
* **Features**:

  * Explored multicasting
  * Basis for changes later merged into IPv4

### **4. IPv4**

* **Introduced**: 1981 (RFC 791)
* **Status**: Widely used, but address space is limited
* **Features**:

  * 32-bit addressing (\~4.3 billion addresses)
  * Class-based system (A, B, C, D, E)
  * Supports NAT, unicast, broadcast, multicast
  * Dynamic addressing via DHCP
  * Optional security via IPSec

### **5. IPv5 (Internet Stream Protocol - ST)**

* **Introduced**: 1990s
* **Status**: Experimental
* **Features**:

  * Designed for streaming and multimedia
  * Quality of Service (QoS) support
  * Never standardized

### **6. IPv6**

* **Introduced**: 1998 (RFC 2460)
* **Status**: Actively replacing IPv4
* **Features**:

  * 128-bit addressing (\~340 undecillion addresses)
  * No NAT required
  * Mandatory IPSec support
  * Uses multicast and anycast instead of broadcast
  * Auto-configuration via SLAAC
  * Efficient hierarchical routing

---

## **Main IP Types Used Today**

### **IPv4**

* **Structure**:

  * 32 bits, divided into 4 sections (8 bits each)
  * Decimal range per section: 0–255
  * Binary range: `00000000.00000000.00000000.00000000` → `11111111.11111111.11111111.11111111`
* **Total addresses**: 4,294,967,296
* **Example of binary to decimal**:

  ```
  00000000 = 0
  00000001 = 1
  00000010 = 2
  ...
  00010000 = 16
  ```

#### **IPv4 Classes**

| Class | Range                       | Network Bits | Host Bits | No. of Networks | No. of Hosts | Reserved For    |
| ----- | --------------------------- | ------------ | --------- | --------------- | ------------ | --------------- |
| **A** | 0.0.0.0 – 127.255.255.255   | 7            | 24        | 126             | 16,777,214   | Government      |
| **B** | 128.0.0.0 – 191.255.255.255 | 14           | 16        | 16,384          | 65,534       | Companies       |
| **C** | 192.0.0.0 – 223.255.255.255 | 21           | 8         | 2,097,152       | 254          | Small Companies |
| **D** | 224.0.0.0 – 239.255.255.255 | -            | -         | -               | -            | Multicasting    |
| **E** | 240.0.0.0 – 255.255.255.255 | -            | -         | -               | -            | Future Use      |

---

### **IPv6**

* **Address range**: Vast, designed to replace IPv4
* **Key differences**:

  * 128-bit addressing
  * Built-in security
  * No broadcast; uses multicast/anycast
  * Supports auto-configuration

