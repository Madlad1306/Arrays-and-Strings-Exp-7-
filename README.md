# Array and String in C++

**AIM:**
To study and implement the usage of arrays and strings in C++.

**SOFTWARE USED:**
Visual Studio Code (VS Code)

---

## ARRAYS IN C++

**Definition:**
An array is a data structure that stores multiple values of the same data type in contiguous memory locations.

### 🔹 Key Points

* Stores **homogeneous data** (all elements of the same type)
* **Fixed size** → must be declared at compile time
* Elements are accessed using an **index (0 to n-1)**
* Provides **random access**

### 🔹 Types of Arrays

* **One-Dimensional** → Linear data storage
* **Two-Dimensional** → Matrix-like storage
* **Multi-Dimensional** → Higher-order structures

### 🔹 Advantages

* Fast access and modification
* Easy to implement for fixed-size problems

### 🔹 Limitations

* Fixed size (no resizing possible at runtime)
* No bounds checking (out-of-range access leads to errors)

### 🔹 Common Operations

* Traversal
* Insertion
* Deletion
* Searching (linear/binary)
* Sorting (ascending/descending)

### 🔹 Usage in Advanced Structures

* Matrices
* Vectors
* Stacks & Queues

---

## STRINGS IN C++

**Definition:**
A string is a sequence of characters used to represent textual data.

### 🔹 Types of Strings in C++

1. **C-Style Strings (Character Arrays)**

   * Implemented as an array of characters ending with `\0`
   * Functions: `strlen()`, `strcpy()`, `strcmp()`
   * Requires manual size management

2. **`string` Class (STL)**

   * Part of Standard Template Library
   * Dynamic sizing, automatic memory management
   * Built-in functions:

     * Concatenation (`+`)
     * Comparison (`==`)
     * Substring extraction (`substr()`)
     * Character access (`[]`, `.at()`)

### 🔹 Advantages of `string` Class

* No manual memory handling
* Safer and more flexible than C-style strings
* Easy to use with `cin` and `cout`

---

## ALGORITHMS

### 1️⃣ Reverse the Array

**Steps:**

* Input array
* Swap elements from start and end moving inward
* Print reversed array

---

### 2️⃣ Sum and Average of Array

**Steps:**

* Input array
* Accumulate sum using loop
* Divide by total elements to get average

---

### 3️⃣ Reverse a String

**Steps:**

* Input string
* Traverse from end to beginning
* Build reversed string and display

---

### 4️⃣ Check Palindrome String

**Steps:**

* Input string
* Compare characters from both ends
* If mismatch found → Not palindrome
* Else → Palindrome

---

## 📌 CONCLUSION

* Arrays in C++ allow **efficient storage and manipulation** of fixed-size, homogeneous data.
* Strings provide **text handling**, with STL `string` class offering a **safer and more flexible approach**.
* Implementing operations like **reversing, summation, average, and palindrome checking** strengthens the understanding of **loops, indexing, and conditional logic** in C++.

---
