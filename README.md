# 💳 Assembly Debit Card System

A **text-based debit card simulator** built using **x86 Assembly (MASM)**. This project simulates real-world debit card functionality such as PIN authentication, money deposit, discount-based purchases, and balance checking — all implemented using low-level I/O operations and registers.

![Demo](https://media.giphy.com/media/3o7aD2saalBwwftBIY/giphy.gif)
> 🎥 Replace this with your own GIF demo of the program running in DOSBox or Visual Studio

---

## 🚀 Features

- 🔐 **PIN Authentication** – 3-digit PIN login for user security.
- 💰 **Add Money** – Deposit money into your account.
- 🛒 **Make Purchases** – Enter a bill amount and deduct from balance.
- 🎁 **Discount System** – Auto ₹2 discount on purchases over ₹6.
- 👀 **Check Balance** – View remaining balance anytime.
- 🚫 **Insufficient Funds Alert** – Prevent purchases with low balance.
- 🔁 **Loop for Multiple Transactions** – Continue using the system until you exit.

---

## 🛠 Technologies Used

- **Assembly Language (MASM/TASM)**
- **16-bit x86 Architecture**
- **DOS Interrupts (INT 21h)** for I/O operations
- Registers: `AX`, `BX`, `CX`, `AL`, etc.

---

## 📂 File Structure

