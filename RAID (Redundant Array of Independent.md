### **RAID (Redundant Array of Independent/Inexpensive Disks) :-**

RAID is a **data storage virtualization** technology that combines multiple physical drives into a single logical unit to improve **performance, redundancy, or both**.

### **Types of RAID Levels**

### **1. RAID 0 (Striping, No Redundancy) :-**

- **How it works**: Splits data across multiple disks (striping) for higher speed.
- **Pros**: **Fastest** read/write performance.
- **Cons**: **No fault tolerance**—if one disk fails, all data is lost.
- **Use Case**: High-speed applications (e.g., gaming, video editing, cache storage).

### **2. RAID 1 (Mirroring) :-**

- **How it works**: Data is duplicated (mirrored) across two or more disks.
- **Pros**: **High reliability**, as data is safe even if one disk fails.
- **Cons**: **Storage efficiency = 50%** (needs double the storage).
- **Use Case**: Critical systems that require **data redundancy** (e.g., databases, financial records).

### **3. RAID 5 (Striping with Parity) :-**

- **How it works**: Data is striped across multiple disks with **parity (error-checking info)** stored on one disk at a time.
- **Pros**: **Balanced performance & fault tolerance** (can survive one disk failure).
- **Cons**: Slower write speeds due to parity calculations.
- **Use Case**: Web servers, file servers, general-purpose storage.

### **4. RAID 6 (Striping with Double Parity) :-**

- **How it works**: Similar to RAID 5 but with **two parity blocks** for extra protection.
- **Pros**: Can survive **two disk failures**.
- **Cons**: Requires at least **four disks** and is slower than RAID 5.
- **Use Case**: Enterprise storage where high redundancy is critical.

### **5. RAID 10 (RAID 1 + RAID 0, aka "RAID 1+0") :-**

- **How it works**: Combines mirroring (RAID 1) with striping (RAID 0) for both **speed and redundancy**.
- **Pros**: **Fast performance + high fault tolerance**.
- **Cons**: Needs at least **four disks** and has **50% storage efficiency**.
- **Use Case**: High-performance databases, virtualization, enterprise applications.

---

### **Software vs. Hardware RAID**

- **Software RAID**: Managed by the OS (e.g., Windows Storage Spaces, Linux mdadm).
- **Hardware RAID**: Uses a dedicated RAID controller for better performance and reliability.
