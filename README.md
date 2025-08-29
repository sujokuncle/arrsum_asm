# Assembly Programs – Addition of Numbers in Array

This repository contains simple **x86 Assembly (NASM, Linux syscall)** programs that perform addition of numbers stored in an array. Two approaches are implemented: **8-bit addition** and **16-bit addition**.

---

## 📌 1. 8-bit Array Addition

* Adds single-digit numbers stored in an array.
* Result is correct only if the sum is **less than 10** (since it directly converts to a single ASCII digit).
* Suitable for demonstrating **basic addition logic and looping with arrays**.

---

## 📌 2. 16-bit Array Addition

* Adds multiple numbers (array elements) with a sum that may exceed a single digit.
* Handles results up to **two digits** by dividing the sum into quotient and remainder.
* Demonstrates **conversion of numeric sum into ASCII** for proper multi-digit display.

---

## ✅ Summary

* **8-bit Addition** → Works for single-digit sums.
* **16-bit Addition** → Supports larger sums and correct multi-digit display.
