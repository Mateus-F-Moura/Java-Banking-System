# 🏦 Bank Account System

> A console-based banking application demonstrating core Java programming skills and Object-Oriented Programming principles.

## 📋 Project Overview

This project simulates a simple bank account management system where users can create accounts, make deposits, withdrawals, and update account information through an interactive menu. The application was developed as a learning project to strengthen fundamental programming concepts.

## 🎯 Skills Demonstrated

### Object-Oriented Programming (OOP)
- **Encapsulation**: Implementation of private attributes with controlled access through getters and setters
- **Class Design**: Well-structured separation of concerns between entity (Bank) and application layers
- **Data Hiding**: Protected sensitive account information using proper access modifiers

### Java Core Concepts
- **Constructors**: Created custom constructors for flexible object initialization
- **Method Overriding**: Implemented custom `toString()` method for formatted output
- **Data Types**: Proper use of primitive types (int, double) and String objects
- **Final Keyword**: Applied `final` modifier to immutable attributes

### Control Flow & Logic
- **Switch-Case Statements**: Implemented menu navigation with multiple options
- **Do-While Loop**: Created continuous program execution until user exits
- **Conditional Logic**: Applied if-else statements for option handling
- **Input Validation**: Handled user input with Scanner class

### Business Logic Implementation
- **Transaction Fees**: Applied $5.00 withdrawal fee in business logic
- **Balance Management**: Implemented deposit and withdrawal operations
- **Account Updates**: Created functionality to modify account holder information

### Clean Code Practices
- **Code Organization**: Separated entities and application logic into distinct packages
- **Meaningful Names**: Used descriptive variable and method names
- **Method Responsibility**: Each method has a single, well-defined purpose
- **Code Readability**: Structured code with proper indentation and formatting

## 🛠️ Technologies Used

- **Language**: Java
- **IDE**: IntelliJ IDEA
- **Version Control**: Git & GitHub

## 📂 Project Structure

```
Bank-Account/
├── src/
│   ├── application/
│   │   └── Main.java          # Main program with user interface
│   └── entities/
│       └── Bank.java           # Bank account entity class
├── .gitignore
└── Bank-Account.iml
```

## 🚀 Features

### Interactive Menu System
- **Option 0**: Exit the program
- **Option 1**: Change account holder name
- **Option 2**: Make a deposit
- **Option 3**: Make a withdrawal (includes $5.00 fee)

### Account Management
- Create new accounts with account number and holder name
- Optional initial deposit during account creation
- Real-time balance updates
- Formatted account information display

## 💻 How to Run

1. **Clone the repository**
```bash
git clone https://github.com/Mateus-F-Moura/Bank-Account.git
```

2. **Navigate to project directory**
```bash
cd Bank-Account
```

3. **Open in your Java IDE**
   - IntelliJ IDEA, Eclipse, VS Code, or any Java-compatible IDE

4. **Run the Main class**
   - Navigate to `src/application/Main.java`
   - Run the main method

## 📚 Key Learning Outcomes

Through this project, I strengthened my understanding of:

✅ **Encapsulation principles** and why data protection is crucial  
✅ **Constructor usage** for object initialization  
✅ **Method design** and single responsibility principle  
✅ **User input handling** with Scanner and proper resource management  
✅ **Control structures** (loops and conditional statements)  
✅ **String formatting** for professional output presentation  
✅ **Package organization** for scalable code structure  
✅ **Git version control** for project management  

## 🎓 Academic Context

This project was developed as part of my learning journey in:
- Object-Oriented Programming fundamentals
- Clean code practices
- Software design principles
- Java programming language

## 👨‍💻 Author

**Mateus Ferreira de Moura**

Java Back-End Developer | Internet Systems Student

- 💼 LinkedIn: [mateus-ferreira-de-moura](https://www.linkedin.com/in/mateus-ferreira-de-moura)
- 🐙 GitHub: [@Mateus-F-Moura](https://github.com/Mateus-F-Moura)
- 📧 Email: mf753161@gmail.com

## 📝 License

This is an educational project developed for learning purposes.

---

⭐ **If you found this project helpful for learning Java OOP concepts, consider giving it a star!**
