# wastetracker

# 📦 Smart Waste Tracker - Final Project Submission
**Course:** CSC 307 - Data Structures and Algorithm Analysis  
**Semester:** Spring 2025

## 👥 Group Members
- Binita Dhakal (w10176598)
- Dikshant Aryal (w10178820)
- Sahaj Soti (w10176281)

---

## 📘 Project Overview
Smart Waste Tracker is a C++ application that simulates an intelligent waste collection system. It models urban waste bins and road connections as a weighted graph to enable optimized route planning for waste collection trucks. The system features:
- Waste level detection with simulated ultrasonic sensors
- Efficient bin collection scheduling
- Overflow alerts via simulated notifications
- Simple GUI potential with Nana (optional)
- Historical data management using SQLite (optional)

---

## 📁 Files Included
- `main-2.cpp` – Main driver of the application
- `HashTable.cpp` – Implementation of custom hash table
- `hashtable.h` – Header file for the hash table
- `2. Project Proposal CS307.pdf` – Original proposal
- `3. Second Draft Final.pdf` – Final revised project description
- `CSC 307 Spring 2025 Demonstration of Basic Functionality.docx` – Milestone 2 (CRUD showcase)
- `Milestone 3 Final Project Deliverable.docx` – Current milestone rubric
- `README.txt` – This documentation

---

## ⚙️ How to Compile
Make sure you're using a C++17-compliant compiler:
```bash
g++ main-2.cpp HashTable.cpp -o SmartWasteTracker
```

---

## ▶️ How to Run
After successful compilation:
```bash
./SmartWasteTracker
```

---

## 🧰 Dependencies
- C++17 or above
- Optional (not needed for CLI demo):
  - Nana GUI library
  - SQLite for data analysis

---

## ✅ Key Features Implemented
- **Custom Hash Table** with full **CRUD** (Create, Read, Update, Delete) operations
- **Graph Representation** of bin networks
- **Simulated Scheduling** based on bin usage
- **Real-Time Monitoring & Overflow Detection**
- **Modular Codebase** for easy maintenance

---

## 📝 Notes
- This project meets all rubric criteria including class definition, use of proposed data structure, implementation of all project proposal functions, and application of CRUD logic throughout.
- GUI and database are planned for future enhancements; current version is CLI-focused.

---

## 📌 Final Thoughts
This system provides a foundation for a smart waste management prototype suitable for further expansion into real-world applications with sensor and IoT integration.
