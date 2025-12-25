# Market Automation System

![CSharp](https://img.shields.io/badge/C%23-.NET-green)
![WinForms](https://img.shields.io/badge/UI-Windows%20Forms-blue)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)
![Data](https://img.shields.io/badge/Data-Mock%20In--Memory-orange)
![Status](https://img.shields.io/badge/Status-Demo%20Project-yellow)
![License](https://img.shields.io/badge/License-Not%20Specified-red)

A **Market Automation System** desktop application developed using **C# (.NET Framework)** and **Windows Forms**.  
This project simulates a small-scale market (store) automation system using **mock (in-memory) data**, without any database dependency.

---

## 🧠 Overview

This project demonstrates:

- Desktop application development with **C# WinForms**
- Market/store automation logic
- Sales, product, customer, and payment workflows
- Object-oriented design with domain-focused classes
- Application logic built entirely on **mock data**

The application is suitable for **educational purposes**, **OOP practice**, and **demo projects**.

---

## ✨ Features

- 🏪 Market / Store management simulation
- 📦 Product catalog & product definitions
- 🛒 Sales transactions
- 🧾 Sales items (Sale details)
- 👤 Customer & cashier (store clerk) models
- 💳 Payment methods:
  - Cash
  - Credit card
- 🧠 In-memory mock data handling (no database)

---

## 🧰 Tech Stack

- **C#**
- **.NET Framework**
- **Windows Forms**
- **Object-Oriented Programming (OOP)**
- **Mock / In-Memory Data**

---

## 📂 Project Structure

```text
MarketOtomasyon/
└── MarketOtomasyon v1.0/
    ├── Properties/                 # Project properties
    ├── bin/Debug/                  # Build output
    ├── obj/Debug/                  # Build intermediates
    ├── App.config                  # Application configuration
    ├── Program.cs                  # Application entry point
    ├── Form1.cs                    # Main UI form
    ├── Form1.Designer.cs           # UI designer
    ├── Form1.resx                  # UI resources
    ├── Dukkan.cs                   # Store model
    ├── Urun.cs                     # Product model
    ├── UrunTanimi.cs               # Product definition
    ├── UrunKatalog.cs              # Product catalog
    ├── Musteri.cs                  # Customer model
    ├── Kisi.cs                     # Base person class
    ├── Kasagorevlisi.cs             # Cashier model
    ├── Satis.cs                    # Sale transaction
    ├── SatisKalemi.cs              # Sale item
    ├── Odeme.cs                    # Payment base class
    ├── Nakit.cs                    # Cash payment
    ├── KrediKarti.cs               # Credit card payment
    └── README.md
```

> The project follows a **classic Windows Forms structure** with **domain-driven class files**, where business logic is handled in-memory.

---

## 🗄️ Data Handling

- ❌ No database is used
- ✅ All data is managed via **in-memory (mock) objects**
- Suitable for:
  - OOP learning
  - Algorithm & workflow simulation
  - UI + logic separation practice

---

## 📌 Prerequisites

To run this project locally, you need:

- Windows OS
- Visual Studio 2019 or later
- .NET Framework installed

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/SergenEsendemir/MarketAutomationSystem.git
   ```

2. **Open the solution**
   - Open `MarketOtomasyon v1.0.csproj` in Visual Studio

3. **Run**
   - Press **F5** or click **Start Debugging**

---

## 🎯 Purpose

This project was created to:

- Practice **C# WinForms** development
- Improve **object-oriented design** skills
- Simulate a real-world market automation workflow
- Build logic-heavy applications without database complexity

It is a **learning-focused demo project**, not intended for production use.

---

## 🤝 Contributing

Contributions are welcome:

- UI improvements
- Code refactoring
- Feature extensions
- Unit test additions

---

## 👤 Author

**Sergen Esendemir**  
GitHub: https://github.com/SergenEsendemir

---

## 📄 License

No license is currently specified.  
You may add one if required (e.g., MIT License).
