
# 🚀 Mini Project – Text File Conversion Performance Analysis

This mini project compares the performance (in terms of time taken) of different programming languages in converting large text files to **uppercase**. The objective is to benchmark how efficiently **C, C++, Java, R, and Python** handle text file processing across varying file sizes.

---

## 📌 Objective

To compare and analyze the time taken by different languages to convert text files of various sizes (200MB–1000MB) into uppercase format.

---

## 🧪 Experiment Setup

- Languages Used: **C, C++, Java, R, Python**
- Task: **Convert all characters in a text file to uppercase**
- File Sizes:  
  - 200 MB  
  - 400 MB  
  - 600 MB  
  - 800 MB  
  - 1000 MB

---

## 📊 Sample Result Table

| File Size | Time Taken (in seconds) |
|-----------|--------------------------|
|           | C | C++ | Java | R | Python |
|-----------|----|-----|------|----|--------|
| 200 MB    | 12 | 15  | 18   | 20 | 25     |
| 400 MB    | 20 | 25  | 30   | 35 | 40     |
| 600 MB    | 34 | 36  | 40   | 45 | 53     |
| 800 MB    | 45 | 50  | 55   | 60 | 75     |
| 1000 MB   | 55 | 60  | 70   | 80 | 100    |

---

## 🔍 Methodology

![g2](https://github.com/user-attachments/assets/11823075-7f08-433a-836f-26e1db28fc96)


---

## 🧠 Observations

- C and C++ consistently performed the fastest.
- Python and R showed noticeably higher execution times as file size increased.
- Java provided a good balance between performance and ease of use.

---

## 📈Visualization

You can use `matplotlib` or similar tools to plot:

- X-axis: File Sizes (MB)
- Y-axis: Time Taken (seconds)
- One line per language



