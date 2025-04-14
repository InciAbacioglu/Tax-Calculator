# Tax Calculator (C Version)

A simple C program that calculates tax based on the user's age and salary using progressive tax brackets. The tax thresholds vary depending on age groups.

---

## 💡 Description

The user is prompted to enter their age and salary. Based on the age group, the program applies a specific base threshold and calculates the tax using the formula:

Tax = (16% of threshold) + (25% of amount exceeding the threshold)

Age-based thresholds:
- Age 18–35 → Threshold: 17000
- Age 36–50 → Threshold: 23000
- Age 51–74 → Threshold: 29000
- Age 75–95 → Threshold: 14000

If the age is not in a valid range, the program prints an error message.

---

## 🧪 Sample Output

Please enter your age :  
42  
Please enter your salary :  
30000  
Your tax amount is 2700.00

---

## ⚙️ Compilation & Run

Use the following commands to compile and run the program:

gcc tax_calculator.c -o tax  
./tax

---

## ✅ Requirements

- Any C compiler (GCC recommended)  
- Works on Linux, macOS, Windows (via terminal or cmd)

---

Made with ❤️ by İnci Mercan Abacıoğlu  
Project: C Practice – Conditionals and Arithmetic
