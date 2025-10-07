# DSA_Heaps


# 🧮 DSA Heap Problems

This repository contains my daily practice and Java implementations of **Heap-based problems** in Data Structures and Algorithms (DSA).  
I’ll be updating this repo regularly as part of my #VenkatToSDEin90Days journey 🚀.

---

## 📔 Current Progress
✅ **Completed:**  
- Kth Largest Element (Min Heap Approach)

🕒 **Coming Next:**  
- Kth Smallest Element (Max Heap Approach)  
- Top K Frequent Elements  
- Heap Sort  
- Connect Ropes to Minimize Cost  
- Merge K Sorted Arrays  
- Find Median from Data Stream  

---

## 🧠 Problem 1: Kth Largest Element

### 📍 Problem Statement  
Given an array of integers and an integer `k`, find the **Kth largest element** in the array.

### 💡 Approach  
1. Create a **Min Heap** of size `k`.  
2. Insert each element into the heap.  
3. If heap size > `k`, remove the smallest element.  
4. After processing all elements, the heap top is the **Kth largest**.

### 🧩 Example  
**Input:** `arr = [3, 2, 1, 5, 6, 4], k = 2`  
**Process:**  
- Insert elements → maintain heap of size 2  
- Final heap = [5, 6]  
- **Output:** `5`

### ⏱️ Complexity  
- Time: `O(n log k)`  
- Space: `O(k)`

---

## 💻 Language Used
- **Java**

---

## 📚 Learning Source
Concepts learned from:
- Kunal Kushwaha’s DSA Series  
- Striver’s DSA Sheet (Heap Section)

---

## 🗓️ Daily Progress Log
| Date | Problem | Status |
|------|----------|--------|
| Oct 8, 2025 | Kth Largest Element | ✅ Completed |
| — | — | 🔜 Next problem coming soon... |

---

## ✍️ Author
**Venkat Akumarti**  
> #VenkatToSDEin90Days 🚀  
> Java | DSA | Problem Solving
