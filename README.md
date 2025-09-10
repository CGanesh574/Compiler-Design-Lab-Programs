

# 🖥️ Compiler Design Programs

This repository contains a collection of **Lex** and **C programs** implemented for Compiler Design coursework.
Programs are organized into two main folders:

* **Lab-Programs** → Core compiler design experiments
* **Assignment-Programs** → Additional assignment-based tasks

---

## 🔹 Lab Programs

Located in [`Lab-Programs/`](Lab-Programs/).
These cover fundamental problems in compiler construction.

<details>
<summary>📘 Program List</summary>

* **Program1.l** → Detects valid identifiers
* **Program2.l** → Recognizes C keywords
* **Program3.l** → Classifies operators (arithmetic, relational, logical, bitwise, assignment)
* **Program4.l** → Identifies constants, comments, identifiers, and operators in C
* **Program5.l** → Distinguishes vowels and consonants
* **Program6.l** → Finds functions and comments in C code
* **Program7.c** → Demonstrates top-down parsing using brute-force backtracking

</details>

---

## 🔹 Assignment Programs

Located in [`Assignment-Programs/`](Assignment-Programs/).
These are additional exercises designed to strengthen concepts.

<details>
<summary>📘 Program List</summary>

* **Program1.l** → Lex program for identifier recognition
* **Program2.l** → Recognizes different forms of real numbers in programming languages

</details>

---

## 🚀 Usage

To run a Lex program:

```bash
lex filename.l
gcc lex.yy.c
./a.out   # or ./a.exe on Windows
```
