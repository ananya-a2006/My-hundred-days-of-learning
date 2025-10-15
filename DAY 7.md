🧩 Day 7 – Modules & Practice

📚 Topics Covered:
- What are Modules?  
- Importing Modules  
- `math` Module  
- `random` Module  
- `datetime` Module  


📘 What is a Module?

- A **module** in Python is a file containing code (functions, variables, or classes) that can be reused in other programs.  
- It helps in **organizing and reusing** code efficiently.  
- Python has many **built-in modules** (like `math`, `random`, `datetime`) and allows creation of **user-defined modules**.

🔹 Importing Modules

Modules are imported using the `import` keyword.

 🔹 The `math` Module

Used for performing **mathematical operations** such as square roots, powers, trigonometric functions, etc.

### Common Functions:
| Function | Description | Example |
|-----------|--------------|----------|
| `math.sqrt(x)` | Square root of x | `math.sqrt(25)` → 5.0 |
| `math.pow(x, y)` | x raised to power y | `math.pow(2, 3)` → 8.0 |
| `math.pi` | Constant value of π | `3.14159...` |
| `math.ceil(x)` | Rounds up | `math.ceil(4.2)` → 5 |
| `math.floor(x)` | Rounds down | `math.floor(4.8)` → 4 |

🔹 The `random` Module

Used for generating **random numbers** or making random choices.  
It’s commonly used in games, simulations, and data sampling.

### Common Functions:
| Function | Description | Example |
|-----------|--------------|----------|
| `random.randint(a, b)` | Random integer between a and b | `random.randint(1, 10)` |
| `random.random()` | Random float between 0 and 1 | `random.random()` |
| `random.choice(seq)` | Random element from a list/tuple | `random.choice(['red', 'blue'])` |
| `random.shuffle(list)` | Randomly reorders items in a list | `random.shuffle(mylist)` |

 🔹 The `datetime` Module

Used to work with **dates and times**.

### Common Functions:
| Function | Description | Example |
|-----------|--------------|----------|
| `datetime.datetime.now()` | Current date and time | `2025-10-09 21:35:00` |
| `datetime.date.today()` | Current date | `2025-10-09` |
| `strftime()` | Format date/time | `now.strftime("%d/%m/%Y")` |
