# Basic Numpy:




## 🔹 What is NumPy?

* **NumPy** = **Numerical Python**
* It’s a **Python library** used for **fast calculations** with large sets of numbers.
* At its core, it provides an object called an **ndarray** (N-dimensional array), which is like a **super-powered list**.

---

## 🔹 Why use NumPy instead of normal Python lists?

* **Speed**: NumPy runs much faster (written in C under the hood).
* **Convenience**: You can do math on entire arrays without writing loops.

Example:
### Addition:


<img width="336" height="160" alt="image" src="https://github.com/user-attachments/assets/4d270a5c-8680-47dd-b350-9d06d828084e" />


```python
import numpy as np

a = np.array([1, 2, 3, 4])
b = np.array([10, 20, 30, 40])

print(a + b)   # [11 22 33 44]
print(a * b)   # [10 40 90 160]
print(a.mean())  # 2.5
```

With plain Python lists, you’d need loops to do this.

---

## 🔹 What can NumPy do?

1. **Array operations** (addition, multiplication, square roots, etc.)
2. **Linear algebra** (matrix multiplication, solving equations)
3. **Statistics** (mean, median, standard deviation)
4. **Random numbers** (used in machine learning & simulations)
5. **Data handling** (foundation for pandas, scikit-learn, TensorFlow, etc.)

---

## 🔹 Real-world uses

* **Data science** → analyzing big datasets
* **Machine learning** → preparing input data
* **Image processing** → treating images as arrays of pixels
* **Scientific computing** → simulations, numerical solutions

---

👉 In short: **NumPy = the foundation for numerical and scientific computing in Python.**








