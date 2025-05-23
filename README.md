# ThriftTrack

**ThriftTrack** is a Windows-based thrift store management system designed to streamline and simplify the operations of second-hand stores. It helps manage inventory, track donations, process orders, handle payments, and generate reports, all from a user-friendly interface.

## 📌 Features

- **User Authentication**
  - Admin login and access control
- **Member Management**
  - Add, view, and delete Customers and Donors
- **Inventory Management**
  - Add, update, and delete products
  - Track product categories, prices, and quantities
- **Order Management**
  - Place orders with support for multiple products
  - View and manage order history
- **Payment Processing**
  - Capture payment method, order total, and customer info
  - Display invoice details after payment
- **Donation Tracking**
  - Maintain donor records
  - Log number of donations per donor
- **Reporting**
  - View invoices and sales reports through a dedicated ReportForm

## 🛠️ Technologies Used

- **Language:** VB.NET
- **Framework:** .NET Framework (Windows Forms)
- **Database:** Microsoft SQL Server
- **Reporting:** Crystal Reports / ReportViewer (optional)

## 📁 Project Structure

```

ThriftTrack/
├── Forms/
│   ├── LoginForm.vb
│   ├── DashboardForm.vb
│   ├── MemberForm.vb
│   ├── ProductForm.vb
│   ├── OrderForm.vb
│   ├── PaymentForm.vb
│   ├── ReportForm.vb
├── Modules/
│   └── DatabaseModule.vb
├── Assets/
│   └── Images, icons, resources
├── Database/
│   └── thrifttrack\_db.sql (Schema and seed data)
└── README.md

```

## ⚙️ Setup Instructions

1. **Clone the repository**:
```

git clone [(https://github.com/HermitPurple77/BBThriftTrack.git)]

````

2. **Open in Visual Studio**:
- Open `ThriftTrack.sln`

3. **Configure the database**:
- Restore `thrifttrack_db.sql` in SQL Server
- Update your connection string in `DatabaseModule.vb`:
  ```vb
  Dim con As New SqlConnection("Data Source=.\SQLEXPRESS;Initial Catalog=thrifttrack_db;Integrated Security=True")
  ```

4. **Run the application**:
- Press `F5` in Visual Studio

## 👥 User Roles

- **Admin:** Full access to all modules
- **Staff (Optional Future Scope):** Restricted access to inventory and order modules

## 🚀 Future Enhancements

- Mobile app integration
- Online store module (web-based portal)
- AI-based product pricing suggestions
- Email and SMS notification system

## 🧑‍💻 Contributors

- Srinidhi S – Developer
- Diya S – Co Developer
  

## 📄 License

This project is free to use and modify. No license restrictions.
````
