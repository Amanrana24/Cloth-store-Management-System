
# Cloth Store Management System using OOP | Complete C++ Project  

# Cloth Store Management System (C++)

A simple, console-based Cloth Store Management System developed in **C++** using Object-Oriented Programming (OOP) concepts. The application allows users to manage clothing inventory by adding new items, displaying available items, and deleting items through an interactive menu.

## Features

- **Add Clothing Items:** Enter the item name, price, and quantity to add products to the inventory.
- **Display Inventory:** View the details of all clothing items stored in the system.
- **Delete Clothing Items:** Remove an item from the inventory by entering its name.
- **Interactive Menu:** Navigate through the available operations using a simple, menu-driven interface.
- **Vector-Based Storage:** Use the C++ Standard Library's `vector` to store and manage clothing records dynamically.

## Technologies Used

- **Language:** C++
- **Concepts:** Object-Oriented Programming (OOP), Classes, Objects, Encapsulation
- **Data Structures:** `vector`
- **Libraries:** `iostream`, `vector`

## Project Structure

```text
Cloth-Store-Management-System/
│
├── main.cpp       # Main source code
└── README.md      # Project documentation
```

## Getting Started

### Prerequisites

To compile and run this project, you need:

- A C++ compiler, such as GCC or MinGW.
- A terminal or command-line interface.
- A code editor or IDE, such as Visual Studio Code, Code::Blocks, or Visual Studio.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Cloth-Store-Management-System.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Cloth-Store-Management-System
   ```

3. Compile the source code:

   ```bash
   g++ main.cpp -o cloth_store
   ```

4. Run the application:

   **Windows:**
   ```bash
   cloth_store.exe
   ```

   **Linux/macOS:**
   ```bash
   ./cloth_store
   ```

## How to Use

After launching the application, the following menu is displayed:

```text
***** Cloth Store *****

1. for add clothing item
2. for display clothing item
3. for delete clothing item
0. for exit from program

Enter choice:
```

Select an option by entering the corresponding number.

| Option | Operation | Description |
|---|---|---|
| 1 | Add Item | Enter the name, price, and quantity of a clothing item. |
| 2 | Display Items | View the clothing items currently stored in memory. |
| 3 | Delete Item | Enter the name of the item you want to remove. |
| 0 | Exit | Close the application. |

## Object-Oriented Programming Concepts

- **Class:** The `Cloth` class represents clothing inventory management.
- **Objects:** Objects of the `Cloth` class are used to access inventory operations.
- **Encapsulation:** Clothing attributes such as item name, price, and quantity are declared as private members.
- **Dynamic Storage:** A `vector` stores clothing records and allows items to be added or removed at runtime.

## Limitations

- Inventory data is stored in memory and is lost when the program terminates.
- Item names are entered as single words in the current implementation.
- Deleting an item requires its name.
- The current version does not include stock updates, sales processing, or user authentication.

## Future Improvements

- Add file handling or database integration for persistent inventory storage.
- Support clothing names containing spaces.
- Add search and update functionality.
- Implement input validation and error handling.
- Introduce stock management and sales tracking.
- Improve the interface and make it compatible with different operating systems.

## Learning Objectives

This project demonstrates the practical application of C++ fundamentals, including classes, objects, encapsulation, loops, conditional statements, vectors, and basic inventory management operations.

## License

This project is available for educational and personal learning purposes. You may modify and extend it to suit your requirements.


