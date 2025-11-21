
# 🚀 Java Advanced: Stream API, Lambda & Date Handling

![Java CI](https://github.com/TheComputationalCore/java-advanced-streams-lambda-date/actions/workflows/java-build.yml/badge.svg)
![Java](https://img.shields.io/badge/Java-17-orange)
![Build](https://img.shields.io/badge/Build-Passing-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![Repo Size](https://img.shields.io/github/repo-size/TheComputationalCore/java-advanced-streams-lambda-date)

---

## 📌 Overview

This repository contains **advanced Java programs** demonstrating:

- ✔ Stream API  
- ✔ Lambda Expressions  
- ✔ `java.time` Date and Time Handling  
- ✔ Functional Processing  
- ✔ Real‑world data transformations & filtering  

The project includes **four tasks (Q1.1 – Q1.4)** focused on functional-style Java development.

---

## 📁 Project Structure

| File | Description | Category |
|------|-------------|----------|
| `src/QuestionOne.java` | Converts a list of strings to uppercase using Streams | Q1.1 |
| `src/QuestionTwo.java` | Filters non‑empty strings from a list | Q1.2 |
| `src/QuestionThree.java` | Filters names starting with 'A' using Stream + Lambda | Q1.3 |
| `src/QuestionFour.java` | Calculates user age using `LocalDate` | Q1.4 |
| `screenshots/1.png` | Screenshot for Q1.1 | Screenshot |
| `screenshots/2.png` | Screenshot for Q1.2 | Screenshot |
| `screenshots/3.png` | Screenshot for Q1.3 | Screenshot |
| `screenshots/4.png` | Screenshot for Q1.4 | Screenshot |

---

## 🧠 Task Breakdown

### 🔹 Q1.1 — Convert Strings to Uppercase  
Uses Stream API’s `map()` to transform all strings into uppercase.

### 🔹 Q1.2 — Filter Non‑Empty Strings  
Uses `filter(str -> !str.isEmpty())` to clean the list.

### 🔹 Q1.3 — Filter Students Starting with “A”  
Demonstrates lambda expressions with `startsWith("A")`.

### 🔹 Q1.4 — Age Calculator Using LocalDate  
Parses a birthdate and computes age in **years, months, days**.

---

## 🖼 Screenshots (Grid)

| Q1.1 | Q1.2 |
|------|------|
| ![](screenshots/1.png) | ![](screenshots/2.png) |

| Q1.3 | Q1.4 |
|------|------|
| ![](screenshots/3.png) | ![](screenshots/4.png) |

---

## ▶️ How to Run

### 1️⃣ Clone the repo
```bash
git clone https://github.com/TheComputationalCore/java-advanced-streams-lambda-date.git
```

### 2️⃣ Navigate
```bash
cd java-advanced-streams-lambda-date
```

### 3️⃣ Compile
```bash
javac src/*.java
```

### 4️⃣ Run tasks
```bash
java src/QuestionOne      # Q1.1
java src/QuestionTwo      # Q1.2
java src/QuestionThree    # Q1.3
java src/QuestionFour     # Q1.4
```

---

## 🛠 Tech Stack
- Java 17  
- Stream API  
- Lambda Expressions  
- `java.time.LocalDate`  
- Functional Programming Concepts  

---

## 📦 Requirements
- JDK 8+ (Java 17 Recommended)  
- IDE or terminal  

---

## 🏷 Topics
`java` • `streams` • `lambda` • `functional-programming` • `localdate` • `date-handling`

---

## 📜 License
Distributed under the MIT License.
