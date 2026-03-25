## 📌 Cricket-World-Cup-2023-Analytics

Project Overview

This project focuses on building a **data-driven approach to selecting the best T20 cricket team** using performance analytics.

The goal is to identify players who can:

- Score **180+ runs consistently**
- Defend totals around **150 runs effectively**

Using real T20 cricket data, this project combines **data preprocessing, statistical analysis, and Power BI visualization** to evaluate players across different roles.

---

## 🎯 Objectives

- Analyze player performance across T20 matches  
- Define role-based selection criteria  
- Build a **balanced playing XI**  
- Visualize insights using interactive dashboards  
- Apply analytics for real-world sports decision-making  

---

## 🧠 Player Role Classification

Players are categorized into key roles with specific performance metrics:

### 🟢 Openers

- Batting Average > 30  
- Strike Rate > 140  
- Innings Batted > 3  
- Boundary % > 50  
- Batting Position < 4  

---

### 🟡 Middle Order / Anchors

- Batting Average > 40  
- Strike Rate > 125  
- Innings Batted > 3  
- Avg Balls Faced > 20  
- Batting Position > 2  

---

### 🔴 Finishers / Lower Order

- Batting Average > 25  
- Strike Rate > 130  
- Innings Batted > 3  
- Avg Balls Faced > 12  
- Batting Position > 4  
- Innings Bowled > 1  

---

### 🔵 All-Rounders

- Batting Average > 15  
- Strike Rate > 140  
- Innings Batted > 2  
- Batting Position > 4  
- Innings Bowled > 2  
- Bowling Economy < 7  
- Bowling Strike Rate < 20  

---

### ⚫ Specialist Fast Bowlers

- Innings Bowled > 4  
- Bowling Economy < 7  
- Bowling Strike Rate < 16  
- Bowling Average < 20  
- Dot Ball % > 40  
- Bowling Style = Fast  

---

## 🛠️ Tech Stack

- **Python** – Data Cleaning & Preprocessing  
- **Web Scraping** – Data Collection  
- **Pandas / NumPy** – Data Manipulation  
- **Power BI** – Dashboard & Visualization  
- **DAX** – Calculated Measures  
- **Excel** – Intermediate Analysis  
