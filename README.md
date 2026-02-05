# Logic & Algorithms: From Tea to Instagram

A foundational repository demonstrating how everyday human logic translates into structured algorithms and backend-oriented thinking.

**Author:** Danny  
**Level:** Aspiring Backend Engineer  
**Project Goal:** Demonstrating the transition from everyday logic to systematic pseudocode.

---

## Why This Repository Exists

Most beginners jump straight into syntax.  
This repository focuses on something more fundamental: **how engineers think**.

The goal is to build algorithmic intuition before touching frameworks, databases, or APIs.

---

## 🟢 Module 1: The Tea Brewing Algorithm

This module demonstrates **Linear Sequence** and **Termination Logic**. It represents the most basic form of an imperative program.

### Original Pseudocode
1. Take a stainless steel pot and place it on a cooker.
2. Set heat to medium.
3. Pour 2 cups of water into the pot.
4. Wait until the water starts boiling.
5. Add 2½ tablespoons of tea powder.
6. Let it cook for exactly 3 minutes.
7. Turn off the cooker.

### Engineering Grade: 7.5/10
**Strengths:** Precise measurements and clear termination (turning off the heat).  
**Key Learning:** Computers require explicit exit conditions to prevent infinite execution and resource leaks.

---

## 🔵 Module 2: Instagram Login System

This module demonstrates a shift toward **backend-style architecture**, utilizing **initialization**, **variables**, and **conditional logic**.

### Pseudocode Logic
- **Program Start:** `Instagram account login`
- **Initialization:**
  - Input: `Instagram is active (Default = YES)`
  - State: `A = 0` (Validation counter)
- **Validation Steps:**
  - `IF` username is filled appropriately → `A = A + 1`
  - `IF` email is filled appropriately → `A = A + 1`
  - `IF` password is filled appropriately → `A = A + 1`
- **Logic Gate:**
  - `IF A >= 3` → Access `Instagram Interface`
  - `IF A < 3` → Return to `Login Page`

### Engineering Grade: 8.5/10
**Strengths:** Use of a counter variable to track state across multiple validation checks.  
**Growth Area:** Transitioning from cumulative counters to strict logical operators (`AND`) to enforce simultaneous credential validation.

---

## 🛠 Skills Demonstrated

- **Flow Control:** Practical use of conditional logic (`IF / ELSE`)
- **State Management:** Variable initialization and mutation
- **Resource Management:** Explicit program termination
- **Technical Communication:** Translating real-world processes into machine-readable logic

---

*Generated as part of my backend engineering learning journey.*