# 📦 Azure Blob Storage

Azure Blob Storage is Microsoft’s **object storage solution for the cloud**.  
It’s designed to store large amounts of **unstructured data** (data without a fixed schema).

---

## 🔹 1. What is Blob?

**BLOB = Binary Large Object**

- Can store any type of data: text, images, videos, backups, logs, documents, IoT data.  
- Ideal for cloud-native applications, big data, and content delivery.

---

## 🔹 2. Blob Storage Types

Blob storage offers **three blob types**:

### 🟦 Block Blobs
- Store **text & binary data** (documents, images, backups).
- Optimized for **uploading and streaming large files**.

### 🟧 Append Blobs
- Optimized for **append operations** (adding data at the end).
- Best for **logs, audit trails, telemetry data**.

### 🟥 Page Blobs
- Store data in **random access pages**.
- Optimized for **frequent read/write operations**.
- Used for **Virtual Hard Drives (VHDs)** in Azure Virtual Machines.

---

## 🔹 3. Storage Tiers (Cost Optimization)

Azure Blob supports **access tiers** to balance **cost vs. access frequency**:

| Tier         | Use Case | Cost | Retrieval |
|--------------|----------|------|-----------|
| 🔥 **Hot**   | Frequently accessed data | 💲 High | ⚡ Fast |
| ❄️ **Cool**  | Infrequently accessed (≥ 30 days) | 💲 Lower | ⚡ Fast |
| 🗄️ **Archive** | Rarely accessed, long-term backup | 💲 Very Low | 🕒 Hours |

---

## 🔹 4. Blob Storage Structure

Blob Storage is organized like this:

