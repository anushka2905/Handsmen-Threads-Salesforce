# 🧵 HandsMen Threads - Salesforce Project  
**Elevating the Art of Sophistication in Men's Fashion**

This project represents a **Salesforce-based digital transformation** initiative for HandsMen Threads, a forward-thinking fashion brand. The goal is to **streamline operations** and **enhance customer engagement** through automation, intelligent data modeling, and modern UX.

---

## 📂 Table of Contents
- [🚀 Project Overview](#-project-overview)
- [🛠️ Key Features](#️-key-features)
- [📊 Data Model Highlights](#-data-model-highlights)
- [⚙️ Technologies & Tools Used](#-technologies--tools-used)
- [📚 What I Learned](#-what-i-learned)
- [🔗 Project Links](#-project-links)
- [🖼️ Custom Objects & Flow Screenshots](#️-custom-objects--flow-screenshots)
- [📄 License](#-license)
- [💬 Feedback](#-feedback)

---

## 🚀 Project Overview

**HandsMen Threads** leverages Salesforce to:

- Centralize and secure customer, order, and inventory data.
- Automate key workflows for sales and service teams.
- Provide real-time visibility and reporting across departments.

---

## 🛠️ Key Features

- ✅ **Automated Order Confirmations**  
  Email confirmation is sent to customers instantly upon order placement.

- 🏆 **Dynamic Loyalty Program**  
  Loyalty tier updates automatically based on customer purchase history.

- 📦 **Proactive Stock Alerts**  
  Inventory team is alerted when stock falls below 5 units.

- 🕛 **Scheduled Bulk Updates**  
  Nightly batch jobs update inventory and financial records.

---

## 📊 Data Model Highlights

### 🔹 Custom Objects
- `Customer`
- `Order`
- `Product`
- `Inventory`
- `LoyaltyTier`

### 🔗 Object Relationships
- **Customer → Order** (One-to-Many)
- **Order → Product** (Many-to-One)
- **Customer → LoyaltyTier** (One-to-One)

---

## ⚙️ Technologies & Tools Used

| Technology               | Purpose                                  |
|--------------------------|------------------------------------------|
| Salesforce Lightning App | Custom UI design                         |
| Record-Triggered Flows   | Real-time process automation             |
| Apex Triggers            | Business logic for loyalty program       |
| Batch Apex               | Bulk record updates                      |
| Validation Rules         | Maintain data integrity                  |
| Scheduled Apex           | Run nightly sync processes               |

---

## 📚 What I Learned

- Designing scalable data models in Salesforce
- Automating business logic using Flows and Apex
- Enforcing data quality with validations
- Writing asynchronous code using `Batch` and `Scheduled` Apex
- Building user interfaces with Lightning App Builder

---

## 🔗 Project Links

- 🔗 **GitHub Repo**: [Handsmen-Threads-Salesforce](https://github.com/anushka2905/Handsmen-Threads-Salesforce)
- 🎥 **Demo Video**: [Click Here](https://drive.google.com/file/d/1Y7O3ZkQZWx3ecD3qLnoFWbXrIAVfSM6U/view?usp=sharing)

---

## 🖼️ Custom Objects & Flow Screenshots

> 📌 Replace with actual image links or GitHub-hosted image URLs

- **🔄 Customer Object**:
  <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/8d3aa2a9-577b-454f-8db1-080259ac1616" />
- **🔄 Order Object**:
  <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/32ed19c4-58a2-4641-a019-5f1184c0b38b" />
- **🔄 Product Object**:
  <img width="1914" height="1028" alt="Image" src="https://github.com/user-attachments/assets/aa472021-b8f0-4993-aa21-fa845b85652e" />
- **🔄 Inventory Object**:
  <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/7e4871dd-156b-458e-8fe7-79a207a9a7d4" />
- **🔄 Marketing Campaign**:
  <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/b872f298-0957-4860-a6aa-837b3bfcb3f1" />

### 🔁 Key Automation Flows

- 🌟 **Loyalty Program Flow**:
  <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/28be8a43-1aae-401f-abf5-8d649aaa0c0a" /> 
- 📧 **Order Confirmation Flow**:
  <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/4d63c093-7844-4a65-a837-99b64c0cf9dd" />
- 📦 **Stock Alert Flow**:
  <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/36f905e5-87f1-46ad-bafc-9abb9cfc7864" />

### 🔁 Email Templates

- **Order Confirmation:**
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/3a920e8d-a543-4772-8afe-3146f5cfc548" />

- **Low Stock Alert:**
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/4af5c8cf-1f3c-46af-85d0-545c444fb4fc" />

- **Loyalty Status**
<img width="1919" height="1079" alt="Image" src="https://github.com/user-attachments/assets/1bef0bf1-ca69-408a-8331-a8e4346d8015" />


### 🧠 Developer Console Snapshots
- **OrderTotalTrigger**:
  
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/ea8ee78f-6e47-49e0-a462-9be5da161faf" />

- **StockDeductionTrigger**:
  
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/4e70563a-9029-4546-9d6e-d0e9206b8168" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/23caa296-bbbc-4607-8a79-1f7a02d0ad5e" />

- **InventoryBatchJob**:
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/da5c7f10-8e2a-46f4-a76e-cffe2412fbc8" />
  
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/c3791628-3529-4119-9eac-b6d2a7bd6b5b" />

---

## 📄 License

This project is for academic and portfolio purposes.  
You’re free to fork, adapt, or reference it for learning.

---

## 💬 Feedback

Have suggestions, questions, or want to collaborate?  
Open an issue or drop a message — I’d love to connect!

---
