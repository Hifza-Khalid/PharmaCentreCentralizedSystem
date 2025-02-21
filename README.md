# 💊 PharmaCentreCentralizedSystem

## 📌 Overview  
**PharmaCentreCentralizedSystem** is a **Java-based** pharmaceutical management system designed to centralize medicine stock tracking, agent management, and company record-keeping. It integrates **MySQL** with **XAMPP** and utilizes **Java Swing** for UI alongside **JDBC** for database interactions.

---

## 🔥 Features  

### 🌟 Core Functionalities  
✅ **🖥️ User Interface**  
- Interactive **Splash Screen** and **Home Page**.  
- **Easy Navigation** with a structured menu for **Medicines, Agents, and Companies**.  

✅ **🛒 Seller Panel**  
- Medicine record management with attributes: **MedID, MedName, Quantity, MFDate, ExpDate**.  
- **Billing System:** Add medicines to bill, generate invoices, and print receipts.  

✅ **💊 Medicine Management**  
- Full **CRUD (Create, Read, Update, Delete)** operations.  
- Medicines displayed in a structured **table view**.  

✅ **🧑‍⚕️ Agent Management**  
- Manage agents with fields: **AgentID, Name, Age, Contact, Gender, Password**.  
- **CRUD operations** to add, update, or remove agents.  

✅ **🏢 Company Management**  
- Manage pharmaceutical companies with fields: **CompanyID, Experience, Contact, Address**.  
- Perform **CRUD operations** seamlessly.  

✅ **🗄️ Database Connectivity**  
- Integrated with **MySQL** via **JDBC**.  
- Hosted on **XAMPP Server**.  
- Managed through **MySQL Workbench**.  

---

## 🛠️ Technologies Used  
| Technology  | Purpose |
|-------------|---------|
| **Java (Swing & JDBC)** | UI & Backend Logic |
| **MySQL (XAMPP, Workbench)** | Database Management |
| **NetBeans IDE** | Development Environment |
| **MariaDB** | Database Dependency |

---

## 🚀 Installation & Setup  

### 🔹 Prerequisites  
Ensure you have the following installed:  
✅ **JDK 8 or later**  
✅ **NetBeans IDE (or any Java IDE)**  
✅ **XAMPP (for MySQL and Apache Server)**  

### 🔹 Steps to Run the Project  
#### 1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/yourusername/PharmaCentreCentralizedSystem.git
```

#### 2️⃣ **Start XAMPP Server**  
- Open **XAMPP** and start `Apache` & `MySQL` services.  

#### 3️⃣ **Set Up the Database**  
- Open **MySQL Workbench** and create a new database:  
  ```sql
  CREATE DATABASE pharma_centre;
  ```
- Import the provided `.sql` file from the repository.  

#### 4️⃣ **Configure Database Connection in NetBeans**  
- Add **MySQL JDBC Driver** to the project.  
- Update database credentials in `DBConnection.java`.  

#### 5️⃣ **Run the Application**  
- Open the project in **NetBeans**.  
- Execute the `Main.java` file.  

---

## 🔄 CRUD Operations  
### ➕ Create (INSERT)  
```sql
INSERT INTO medicines (med_id, med_name, quantity, price) VALUES (101, 'Paracetamol', 50, 10.5);
```
### 📖 Read (SELECT)  
```sql
SELECT * FROM medicines;
```
### ✏️ Update (UPDATE)  
```sql
UPDATE medicines SET price = 12.0 WHERE med_id = 101;
```
### ❌ Delete (DELETE)  
```sql
DELETE FROM medicines WHERE med_id = 101;
```

---

## 🎯 Future Enhancements  
🚀 **Role-based authentication** (Admin, Seller, Agents).  
🚀 **Stock alert notifications** for expired medicines.  
🚀 **Enhanced reporting system** for sales & inventory tracking.  
🚀 **Cloud-based database integration** for remote access.  

---

## 📜 License  
This project is licensed under the **MIT License**.  

---

## 📬 Contact  
📧 **Email:** hifzaofpk@example.com  
🔗 **GitHub:** [Hifza-Khalid](https://github.com/Hifza-Khalid)  
```
