# UniManage

A console-based university management system built in Java, demonstrating practical implementation of core data structures. The system manages students, courses, enrollments, waitlists, and supports undoing the last action performed.

---

## Features

- **Student Management** — Add and search students using a Binary Search Tree (BST) for fast lookups by ID
- **Course Catalog** — Maintain courses using a doubly linked list, with full catalog display
- **Enrollment System** — Enroll students into courses with automatic capacity checking
- **Waitlist Queue** — Students are automatically queued when a course is full, and moved into the course when a spot opens
- **Undo Functionality** — Stack-based undo system to reverse the last add-student or add-course action
- **Drop Course** — Drop a student from a course, automatically pulling the next student from the waitlist

---

## How to Run

### Requirements
- Java JDK 8 or higher

### Steps
1. Clone or download the repository
2. Navigate to the `src` folder
3. Compile and run:

javac *.java
java src.UniManage

---

## Data Structures Used

| Data Structure | Used For | Files |
|---|---|---|
| Binary Search Tree | Storing and searching students by ID | `StudentBST.java`, `StudentNode.java` |
| Doubly Linked List | Course catalog | `CourseList.java`, `CourseNode.java` |
| Queue | Course waitlists | `WaitlistQueue.java`, `QNode.java` |
| Stack | Undo last action | `UndoStack.java` |

---

## Project Structure

    01-unimanage/
    ├── src/
    │   ├── Course.java          # Course entity
    │   ├── CourseList.java       # Doubly linked list for course catalog
    │   ├── CourseNode.java       # Node for course linked list
    │   ├── QNode.java             # Node for waitlist queue
    │   ├── Student.java           # Student entity
    │   ├── StudentBST.java        # Binary search tree for students
    │   ├── StudentNode.java       # Node for student BST
    │   ├── UndoStack.java         # Stack for undo functionality
    │   ├── UniManage.java         # Main program with menu-driven interface
    │   └── WaitlistQueue.java     # Queue for course waitlists
    └── README.md

---

## Menu Options

1. Add Student
2. Add Course
3. Enroll Student in Course
4. Drop Student from Course
5. Undo Last Action
6. Display Course Catalog
7. Exit

---

## Team

Built collaboratively by Abdul Manan, Tayyab Mangi, and Safiullah.

---

## Semester

**3rd Semester — BS Computer Science**
Sukkur IBA University
