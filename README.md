# Generic-Data-Structure-Library 

---

This repository contains a comprehensive implementation of custom data structures using linked lists. The library provides functionality for various types of linked lists (singly, doubly, circular) and also includes stack and queue implementations. The library is designed for learning, experimentation, and usage in projects where custom implementations are required.  

---

## **Features**  

- **Singly Linear Linked List**  
  - Insertions: First, Last, At Position  
  - Deletions: First, Last, At Position  
  - Display and Count  

- **Singly Circular Linked List**  
  - Insertions: First, Last, At Position  
  - Deletions: First, Last, At Position  
  - Display and Count  

- **Doubly Linear Linked List**  
  - Insertions: First, Last, At Position  
  - Deletions: First, Last, At Position  
  - Display and Count  

- **Doubly Circular Linked List**  
  - Insertions: First, Last, At Position  
  - Deletions: First, Last, At Position  
  - Display and Count  

- **Generic Stack and Queue**  
  - Stack: Push, Pop, Display, Count  
  - Queue: Enqueue, Dequeue, Display, Count  

---

## **Technologies Used**  

- **Language**: C++  
- **Data Structures**: Linked Lists, Stacks, Queues  
- **Templates**: For flexibility and type safety  

---

## **Usage**  

### 1. Clone the repository  
```bash  
git clone https://github.com/Darshchavan/custom-linked-list-library.git  
```  

### 2. Include the library in your project  
Use the appropriate class template for your requirements (e.g., `SinglyLL`, `DoublyLL`).  

### 3. Compile and Run  
Make sure to compile with a C++ compiler supporting templates (e.g., g++).  
```bash  
g++ -o main main.cpp  
./main  
```  

---

## **Examples**  

```cpp  
#include "SinglyLL.h"  // Include the specific class header

int main() {
    SinglyLL<int> sll;
    sll.InsertFirst(10);
    sll.InsertLast(20);
    sll.InsertAtPos(15, 2);
    sll.Display(); // Output: | 10 | => | 15 | => | 20 | => NULL

    sll.DeleteAtPos(2);
    sll.Display(); // Output: | 10 | => | 20 | => NULL
    return 0;
}
```  

