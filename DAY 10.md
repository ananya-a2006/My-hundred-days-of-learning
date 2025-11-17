 🐍 Day 10 – Array Operations: Broadcasting & Vectorized Math

📚 Topics Covered:
- Broadcasting  
- Vectorized Math  
- Array Arithmetic  
- Element-wise Operations  

 🧩 1. Broadcasting

Broadcasting allows NumPy to perform arithmetic operations on arrays of **different shapes** without manually reshaping them.

NumPy compares dimensions from the **rightmost side**, and if a dimension is `1`, it can be stretched to match the other array.

Broadcasting helps in:
- Adding scalars to arrays  
- Adding row/column vectors to matrices  
- Fast mathematical operations  

 ⚡ 2. Vectorized Math

Vectorized math means performing operations on entire arrays **without loops**.

NumPy supports:
- Arithmetic (`+`, `-`, `*`, `/`)  
- Exponentiation  
- Square root, log, exponential  
- Trigonometry (`sin`, `cos`, `tan`)  

Vectorized operations are extremely fast because they run in optimized C code.

🧠 3. Importance of Broadcasting & Vectorization

| Feature | Description |
|--------|-------------|
| Speed | Faster than normal Python loops |
| Clean Code | No need for manual iteration |
| Efficient | Uses optimized NumPy backend |
| Used In | ML, data science, image processing |

💡 4. Real-World Uses

- Scaling datasets  
- Adding bias in neural networks  
- Matrix operations  
- Image pixel adjustments  
- Scientific formulas  
