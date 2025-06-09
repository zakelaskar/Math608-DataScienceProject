# 🧮 Python Sorting Analysis: TimSort vs PowerSort

This project was developed as part of the **Math 608 - Data Science course**. It explores the transition from **TimSort** to **PowerSort** in **Python 3.11**, explaining the underlying reasons, working mechanisms, and performance differences between the two sorting algorithms.

---

## 📌 Objective

To compare TimSort and PowerSort with a focus on:
- Algorithm structure and internal steps
- Edge-case performance
- Time and space efficiency
- Real-world relevance and application in Python

---

## 🧠 What Are TimSort and PowerSort?

### **TimSort**
- A hybrid sorting algorithm (Merge Sort + Insertion Sort)
- Default in Python from version 2.3 to 3.10
- Optimized for partially sorted data
- Stable sort

### **PowerSort**
- Introduced in Python 3.11
- Improved worst-case performance over TimSort
- More consistent in edge-case behavior
- Uses "power values" to determine merge order

---

## 🔬 Key Concepts Explained

- **Identifying Runs**: Sub-sequences of ordered elements
- **Merge Rules**: How runs are combined in each algorithm
- **Performance Analysis**: On average and worst-case datasets
- **Python 3.11 Transition**: Why the standard sorting method changed

---

## 📊 Slide Highlights

- Step-by-step simulation of sorting `[5, 7, 8, 4, 2, 1, 3, 10, 12, 11, 9, 15]`
- Diagrams of merge stacks in TimSort
- Power calculations and merge strategy in PowerSort
- Summary tables comparing speed, space, and reliability

---

## 📂 Contents

```bash
Math608-DataScienceProject/
│
├── Data Science Project.pptx         # Full slide deck
├── README.md                         # Project documentation
📈 Why Python Switched to PowerSort
More predictable behavior with irregular datasets

Lower memory usage

Tighter performance bounds

Alignment with CPython’s performance goals
```

📜 License
This project is for educational and research purposes. Please contact for reuse or collaboration.

## 📬 Contact

**Zakir Elaskar**  
📧 [zelaskar@csuchico.edu](mailto:zelaskar@csuchico.edu) | [elaskarzakir@gmail.com](mailto:elaskarzakir@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/zakelaskar)


