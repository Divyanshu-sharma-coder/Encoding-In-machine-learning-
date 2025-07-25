# 🧠 Encoding in Machine Learning

![Encoding Methods](A_README_document_with_a_corresponding_illustratio.png)

## 📌 Introduction

In machine learning, encoding is a crucial preprocessing step for transforming **categorical data** into numerical formats that algorithms can understand. This repository demonstrates three primary encoding techniques:

- Ordinal Encoding
- One-Hot Encoding
- Label Encoding

Each encoding method is applied and explained with code, examples, and visual output.

---

## 🔠 Types of Encoding

### 1. 🔢 Ordinal Encoding
Ordinal encoding assigns **integer values** to categories based on their order or ranking.

**Example**:

Low → 1
Medium → 2
High → 3

Best suited for **ordered categories** (like education levels or satisfaction ratings).

---

### 2. 🧯 One-Hot Encoding
One-hot encoding transforms each category into a **binary vector**. Each new column represents a category with `1` or `0`.

**Example**:
| Category | Low | Medium | High |
|----------|-----|--------|------|
| Medium   | 0   | 1      | 0    |

Used when **categories have no natural order**.

---

### 3. 🔢 Label Encoding
Label encoding assigns each category a **unique integer** — but without considering any order.

**Example**:

Red → 0
Green → 1
Blue → 2

Useful for **tree-based models**, but can be misleading for algorithms that assume ordinal relationships.

---

## 📂 Files

- `encoding_example.ipynb` – Jupyter Notebook with examples of all three encoding methods.
- `A_README_document_with_a_corresponding_illustratio.png` – Image visualization of encoding methods.

---

## ⚙️ Libraries Used

- `pandas`
- `sklearn.preprocessing`
- `matplotlib` / `seaborn` (if plotting)

---

## 🚀 How to Use

1. Clone the repository or download the `.ipynb` notebook.
2. Open in **Google Colab** or **Jupyter Notebook**.
3. Run all cells to see encoding in action.

---

## 🌟 Conclusion

Choosing the right encoding method is critical based on the type of categorical data and the ML algorithm you’re using. Understanding when and how to use these encoders improves model performance and interpretability.

---

## 📸 Preview

![Encoding Visualization](A_README_document_with_a_corresponding_illustratio.png)

---

## 💬 Connect

Made with ❤️ by [Divyanshu Sharma](https://github.com/Divyanshu-sharma-coder)

---
