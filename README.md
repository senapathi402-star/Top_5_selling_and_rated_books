# 📚 Amazon Top 5 Selling & Rated Books — Data Analysis

> **Tools Used:** Python | Pandas
> **Dataset:** 400 Amazon India Bestseller Books | 4 Columns

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/senapathi402-star/Top_5_selling_and_rated_books/blob/main/Top_5_selling_and_rated_books.ipynb)

---

## 📌 Objective

Amazon wants to find the **Top 5 Selling Books** and **Top 5 Rated Books** in India on their platform using Python and Pandas.

---

## 🗃️ Dataset Structure

| Column | Type | Description |
|--------|------|-------------|
| `Book Name` | object | Name of the book |
| `Author Name` | object | Author of the book |
| `Rating` | float64 | Customer rating (out of 5) |
| `Price` | object | Price in Indian Rupees (₹) |

- **400 rows × 4 columns**

---

## 🏆 Top 5 Selling Books (by sales rank)

<img width="684" height="200" alt="image" src="https://github.com/user-attachments/assets/57ae34cd-ca21-4098-8869-7f39317e9e40" //>

| # | Book Name | Author | Rating | Price |
|---|---|---|---|---|
| 1 | Maths Concept King All Formulas and Theorem | Gagan Pratap Sir | 4.7 | ₹239 |
| 2 | BlackBook of English Vocabulary May 2024 | Nikhil Gupta | 4.5 | ₹299 |
| 3 | Atomic Habits | James Clear | 4.6 | ₹476 |
| 4 | My First Library: Boxset of 10 Board Books | Wonder House Books | 4.5 | ₹399 |
| 5 | Lucent General Knowledge | Binay Karna | 4.4 | ₹209 |

---

## ⭐ Top 5 Rated Books (after removing duplicates)

<img width="940" height="261" alt="image" src="https://github.com/user-attachments/assets/36214700-23ca-4ff0-b8be-45d617b2b090" />

| # | Book Name | Author | Rating | Price |
|---|---|---|---|---|
| 1 | Shrimad Bhagwat Geeta Yatharoop (Hindi) | A.C. Bhaktivendanta Swami Prabhupada | **4.8** | ₹200 |
| 2 | Maths Concept King All Formulas and Theorem | Gagan Pratap Sir | 4.7 | ₹239 |
| 3 | PW Calculus Core Fear No More Calculus | Sachin Jakhar | 4.7 | ₹460 |
| 4 | All In One English Core Class 12th | Prerna Kain Srishti Agarwal | 4.7 | ₹370 |
| 5 | Atomic Habits | James Clear | 4.6 | ₹476 |

---

## 🔍 Key Insights

- Dataset contains **400 book records** with duplicates found during sorting
- After removing duplicates using `drop_duplicates()` — **unique books extracted**
- **Shrimad Bhagwat Geeta** has the highest rating of **4.8** on Amazon India
- **Atomic Habits by James Clear** appears in both Top 5 Selling AND Top 5 Rated lists
- Educational and competitive exam books dominate the bestseller list in India

---

## 🛠️ Pandas Concepts Used

- `pd.read_csv()` — loading CSV data into a DataFrame
- `df.head()` — retrieving top 5 selling books
- `df.info()` — checking column names, data types, null counts
- `df.iloc[]` — accessing rows by position
- `df.nlargest(n=5, columns='Rating')` — finding top 5 rated books
- `df.drop_duplicates()` — removing duplicate book entries
- `df.loc[]` — accessing rows by label

---

## 📁 Files in this Repository

| File | Description |
|------|-------------|
| `Top_5_selling_and_rated_books.ipynb` | Jupyter Notebook with full analysis |
| `BestSeller Books of Amazon.csv` | Amazon India bestseller books dataset |
| `top5_selling.png` | Screenshot — Top 5 Selling Books output |
| `top5_rated.png` | Screenshot — Top 5 Rated Books output |
| `README.md` | Project documentation |

---

## ▶️ How to Run

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install pandas
   ```
3. Open the notebook in Jupyter or Google Colab
4. Run all cells from top to bottom

---

## 👤 Author

**Senapathi Krishna Sai**
Data Analyst | SQL | Python | Tableau | Excel

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/senapathi-krishna-sai-a54721388)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/senapathi402-star)
