# 📞 Phonebook Manager (Java)

This project implements a simple **Phonebook system** in Java using a custom **linked list**. It allows users to add, modify, delete, sort, and move contact entries, all stored as nodes in a singly linked list.

---

## 🧠 Features

- **Add new contacts** with name, address, city, and phone number
- **Modify existing entries** by contact name
- **Delete entries** by name
- **Move all Bellingham entries** to Seattle in one command
- **Sort contacts alphabetically** by last name using a bubble sort algorithm
- **Print phonebook entries** in a user-friendly format

---

## 🗂️ Main File

- `PhonebookManager.java`: Core logic of the phonebook system. Manages linked list operations and contact management.

> ⚙️ Requires a `ListNode` class to represent individual contact nodes.

---

## 💡 How It Works

- Entries are stored in a custom `ListNode` object and linked together via the `next` pointer.
- Data is manipulated using methods like `addEntry()`, `modifyEntry()`, `deleteEntry()`, and `sortAlphabetically()`.
- No external libraries are used — everything is implemented from scratch using plain Java.

---

## 🚀 Example Use Cases

- Create and maintain a personal or business contact list
- Practice linked list operations in real-world scenarios
- Extend this into a GUI-based or file-backed system in the future

---

## 👨‍💻 Author

**Abdul Rahman Said**  
Cybersecurity & Java development student  
[GitHub Profile](https://github.com/Abdu1Said) | [LinkedIn](https://www.linkedin.com/in/abdul-rahman-said-67b6852a8)

---

## 📥 How to Run

1. Clone or download this repository
2. Make sure `ListNode.java` is in the same directory
3. Compile and run using:

```bash
javac PhonebookManager.java
java PhonebookManager
