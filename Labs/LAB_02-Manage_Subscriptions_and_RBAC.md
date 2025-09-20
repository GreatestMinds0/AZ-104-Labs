# Lab 02 – Manage Subscriptions and RBAC

## 📌 Lab Overview
This lab focuses on managing **Azure subscriptions** and implementing **role-based access control (RBAC)**.  
Main objectives:
- Explore Azure subscriptions and billing
- Assign roles at subscription, resource group, and resource levels
- Apply least-privilege access

---

## 🛠️ Step-by-Step Process

### Step 1 – Explore Subscriptions
- Navigated to **Azure Portal → Subscriptions**  
- Verified subscription IDs and names  
- Noted the current subscription for lab use  

📸 Screenshot:  
![Subscriptions overview](images/lab02-step1.png)

---

### Step 2 – Assign Roles (RBAC)
- Selected a **resource group** or specific resource  
- Went to **Access control (IAM)** → **Add role assignment**  
- Assigned **Reader / Contributor / Owner** roles to test accounts  
- Verified permissions by signing in as test user  

📸 Screenshot:  
![Assigning RBAC roles](images/lab02-step2.png)

---

### Step 3 – Test Least-Privilege Access
- Confirmed users had only the permissions assigned  
- Tested that access to unrelated resources was blocked  

📸 Screenshot:  
![Testing access](images/lab02-step3.png)

---

## ✅ Lab Summary
- Successfully explored subscriptions  
- Assigned RBAC roles at appropriate scopes  
- Verified least-privilege access for users
