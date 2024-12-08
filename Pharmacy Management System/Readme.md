# Pharmacy Management System  

The **Pharmacy Management System** is a web-based application developed using JSP, Servlet, and Java. It is designed to streamline pharmacy operations by providing features for managing inventory, processing orders, and maintaining customer records. This system simplifies workflows, improves efficiency, and ensures accuracy in day-to-day operations.  

## Features  

- 🛒 **Order Management**: Process customer orders efficiently and generate invoices.  
- 📦 **Inventory Management**: Track stock levels, manage supplies, and update inventory in real time.  
- 👤 **Customer Records**: Maintain detailed customer information for order history and prescriptions.  
- 🔍 **Search Functionality**: Quickly search for medicines by name, category, or manufacturer.  
- 📊 **Admin Dashboard**: Centralized interface for managing pharmacy operations.  
- 🛠️ **Robust Backend**: Developed using JSP and Servlet with a MySQL database for data storage.  
- 🌐 **Web-Based**: Accessible from any device with a browser, providing flexibility and convenience.  

---

## Requirements  

To run the system, ensure the following software is installed:  

- JDK 8+  
- Apache Tomcat 8+  
- MySQL Database  
- IDE (e.g., Eclipse or IntelliJ IDEA)  

---

## Installation  

1. **Clone the Repository**  
   ```bash  
   git clone https://github.com/your-repo-link/pharmacy-management-system.git  
   cd pharmacy-management-system  
   ```  

2. **Configure the Database**  
   - Create a MySQL database (e.g., `pharmacy_db`).  
   - Import the SQL script from the `database/` directory to set up the schema and initial data.  

3. **Update Database Configuration**  
   - Open the `dbconfig.java` file in the `src/com/pharmacy/` directory.  
   - Update the database URL, username, and password.  

4. **Deploy the Application**  
   - Import the project into your IDE.  
   - Build the WAR file and deploy it to the Apache Tomcat server.  

5. **Access the Application**  
   - Start the Tomcat server and open your browser.  
   - Navigate to `http://localhost:8080/pharmacy-management-system`.  

---

## File Structure  

- `src/`: Contains the Java source code (Servlets, utility classes, etc.).  
- `web/`: JSP files and static assets (HTML, CSS, JS).  
- `database/`: SQL scripts for setting up the database.  
- `WEB-INF/`: Deployment descriptor (`web.xml`).  

---

## Screenshots  

### Admin Dashboard  
![Admin Dashboard](screenshots/admin_dashboard.png)  
Manage inventory, orders, and customer records from a centralized interface.  

### Order Management  
![Order Management](screenshots/order_management.png)  
Process customer orders and generate invoices effortlessly.  

### Inventory Overview  
![Inventory Overview](screenshots/inventory.png)  
Track and manage stock levels with ease.  

---

## Contributing  

We welcome contributions! Please follow our [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.  

---

## License  

This project is licensed under the [MIT License](LICENSE).  

---

## Acknowledgements  

- JSP and Servlet for backend development.  
- MySQL for robust and scalable data storage.  
- Bootstrap for responsive UI design.  

---  

Enjoyed this project? ⭐ it on [GitHub](https://github.com/your-repo-link)!  
