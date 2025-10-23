# ICS-Quadratic-Grader-Mulako-Muyoba

**Name:** Muyoba Mulako  
**Student ID:** 202407184  
**Course:** ICT251 – Web Technologies  
**Lecturer:** Mr. Z. Kaluba  

---

## 📘 Project Description
This is a single-file web application built using **HTML** and **JavaScript**.  
It performs two main functions:

1. **Quadratic Equation Solver**  
   - Solves equations of the form **ax² + bx + c = 0**  
   - Displays the discriminant (D = b² - 4ac)  
   - Identifies the nature of roots (real distinct, real equal, or complex)  
   - Shows results clearly formatted and rounded to a few decimal places  

2. **Grading System**  
   - Converts numeric scores (0–100) into letter grades  
   - Uses the exact grading scale provided in the assignment  
   - Handles edge cases correctly (e.g., 85 → A+, 49 → D)

---

## ⚙️ How to Run
1. Download or clone this repository.  
2. Open the file **index.html** in any web browser (double-click).  
3. Works **offline** — no installation or server required.  
4. Optionally, use **Live Server** in VS Code for instant reloads while editing.

---

## 🧮 Test Cases

### 🔹 Quadratic Solver
| a | b | c | Expected Result |
|---|---|---|-----------------|
| 1 | -3 | 2 | D = 1 → Roots: x₁ = 2, x₂ = 1 |
| 1 | 2 | 1 | D = 0 → One real repeated root x = -1 |
| 1 | 0 | 1 | D = -4 → Complex roots x₁ = i, x₂ = −i |

### 🔹 Grading System
| Score | Expected Grade |
|--------|----------------|
| 100 | A+ |
| 85 | A+ |
| 75 | A |
| 65 | B+ |
| 60 | B |
| 55 | C+ |
| 50 | C |
| 49 | D |
| 0  | D |

---

## 🗂️ Repository Structure
