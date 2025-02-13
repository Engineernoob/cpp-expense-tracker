# C++ Expense Tracker

A command-line expense tracking application built with modern C++ that demonstrates professional software development practices and object-oriented design principles.

## Features

- **Modern C++ Implementation**
  - Utilizes C++11 features
  - Smart pointers and STL containers
  - Exception handling for robust error management

- **Clean Architecture**
  - Separation of concerns with distinct classes (Expense, ExpenseManager)
  - Modular design with clear responsibilities
  - Utility functions for reusability

- **Data Persistence**
  - File-based storage with structured data format
  - Efficient file I/O operations
  - Data validation and error checking

- **User Interface**
  - Interactive command-line interface
  - Professional table formatting using iomanip
  - Clear and intuitive menu system

- **Input Validation**
  - Robust date format validation (YYYY-MM-DD)
  - Amount validation for financial data
  - Error handling with user-friendly messages

- **Testing Infrastructure**
  - Built-in test mode for automated testing
  - Unit test capabilities
  - Simulated input testing

## Technical Skills Demonstrated

- Object-Oriented Programming in C++
- File I/O Operations
- Data Structures (vectors, strings)
- Input Validation and Error Handling
- Table Formatting and UI Design
- Test-Driven Development
- Code Organization and Architecture

## Building and Running

```bash
# Compile the project
g++ -std=c++11 src/*.cpp -o expense_tracker

# Run the application
./expense_tracker

# Run in test mode
./expense_tracker --test
```

## Project Structure

```
src/
├── expense.cpp        # Expense class implementation
├── expense.hpp        # Expense class definition
├── expense_manager.cpp # ExpenseManager class implementation
├── expense_manager.hpp # ExpenseManager class definition
├── main.cpp          # Main program logic and UI
├── utils.cpp         # Utility functions implementation
└── utils.hpp         # Utility functions declarations
```

## Future Enhancements

- Expense categories management
- Reporting and statistics
- Data export functionality
- Budget tracking and alerts

## Learning Outcomes

This project demonstrates proficiency in:
- Modern C++ development practices
- Object-oriented design principles
- File handling and data persistence
- User input validation and error handling
- Clean code organization and documentation
