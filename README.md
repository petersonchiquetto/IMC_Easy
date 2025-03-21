# 🏗️ IMC-Easy  

**IMC-Easy** is a minimalist Python project that calculates Body Mass Index (BMI) using a simple logical structure. The goal is to demonstrate Python syntax applied to variables, user input, mathematical operations, and conditional statements.  

---

## 📂 Project Structure  

The project follows a simple architecture:  

```
IMC-Easy/
│── imc_easy.py   # Main script containing the calculation logic
│── README.md     # Project documentation
```

---

## 🖥️ Implementation & Syntax  

The code utilizes key Python concepts:  

✅ **User input:** `input()` to collect weight and height.  
✅ **Type conversion:** `float()` to ensure accurate numerical calculations.  
✅ **Mathematical operations:** Division and exponentiation to compute BMI.  
✅ **Conditional statements:** `if`, `elif`, and `else` to classify BMI.  
✅ **String formatting:** `f-strings` to display the formatted result.  

### 🔍 Main Code  

```python
# User input
weight = float(input("Enter your weight (kg): "))
height = float(input("Enter your height (m): "))

# BMI calculation
bmi = weight / (height ** 2)

# Display result with formatting
print(f"Your BMI is: {bmi:.2f}")

# Conditional classification
if bmi < 18.5:
    print("You are underweight.")
elif bmi < 25:
    print("You have a normal weight.")
else:
    print("You are overweight.")
```

---

## 🏃‍♂️ How to Run?  

1️⃣ Install **Python 3** if you haven’t already.  
2️⃣ Download or clone this repository:  

```bash
git clone https://github.com/your-username/IMC-Easy.git
```

3️⃣ Run the script in the terminal:  

```bash
python imc_easy.py
```

---

## 🎯 Project Goals  

This project aims to:  

✅ Demonstrate a clear and concise Python syntax implementation.  
✅ Practice handling user input and output in the terminal.  
✅ Apply mathematical operators and control structures.  
✅ Serve as an educational example for Python beginners.  
