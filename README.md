# 🚂 IronNexus - Railway Management System

A comprehensive real-time railway management system built in C++ 
using custom data structures (no STL containers).

## 👥 Group Members
- Ayesha Ali | 22i-2128
- [Muhammad Abdullah] | [22i-0802]
- [Dayyan Azhar] | [23i-6028]

## 📚 Course
Data Structures — Spring 2026 | NUCES

## 🏗️ System Architecture

| Module | Data Structure | Description |
|--------|---------------|-------------|
| Train Registry | AVL Tree | Fast insertion, deletion, search of trains |
| Coach Management | Doubly Linked List | Flexible coach ordering and traversal |
| Railway Network | Graph + Dijkstra | Shortest path between stations |
| Seat Management | Hash Table + BST | Fast booking and ordered seat display |
| Logging System | Stack | Recent-first operation logging |

## ✨ Bonus Features
- ⏪ Undo/Redo operations
- 🗺️ Path caching optimization for Dijkstra
- 🌳 Hierarchical file format for AVL Tree
- 🎨 Colored terminal I/O

## 🛠️ How to Run

### Visual Studio
1. Open `DSA_PROJ.sln`
2. Build → Start (Ctrl + F5)

### G++ (Linux/Mac)
```bash
g++ -std=c++14 main.cpp Coach.cpp Logger.cpp Network.cpp Seat.cpp Train.cpp UI.cpp UndoRedo.cpp -o IronNexus
./IronNexus
```

## 📁 File Structure 
├── Common.h        # Shared constants, enums, utilities
├── UI.h / UI.cpp   # Terminal I/O helpers
├── Train.h/.cpp    # Module 1 - AVL Tree
├── Coach.h/.cpp    # Module 2 - Doubly Linked List
├── Network.h/.cpp  # Module 3 - Graph + Dijkstra
├── Seat.h/.cpp     # Module 4 - Hash Table + BST
├── Logger.h/.cpp   # Module 5 - Stack
├── UndoRedo.h/.cpp # Bonus - Undo/Redo
└── main.cpp        # Entry point

## ⚙️ Constraints
- No STL containers used
- Custom memory management with pointers
- Crash-proof edge case handling
