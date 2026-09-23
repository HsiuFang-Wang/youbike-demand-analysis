# 🚲 YouBike Demand Analysis

## 北商周邊 YouBike 高需求時段預測

A group project analyzing YouBike demand patterns around National Taipei University of Business (NTUB), combining historical trip data, weather information, and machine learning models to identify high-demand periods.

> **Group Project｜Python 爬蟲與資料分析分組專案**  
> **My Role｜資料視覺化、簡報資訊整理與成果呈現**

---

## 📌 Project Overview

本專題以北商周邊 500 公尺內的 YouBike 站點為研究範圍，分析不同站點、時段、星期與天氣條件下的租借需求，並透過分類模型預測高需求時段。

研究期間：

- 2025/12/01 – 2026/02/28
- 北商周邊 500 公尺內 YouBike 站點
- 結合 YouBike 歷史借車資料與天氣資料

---

## 🎯 Research Question

我們希望回答：

**「什麼時間、什麼條件下，北商周邊的 YouBike 站點比較容易出現高需求？」**

分析面向包含：

- 不同站點的需求差異
- 不同時段的租借需求
- 平日與假日差異
- 天氣條件與需求變化
- 高需求時段預測

---

## 🔄 Project Workflow

YouBike 歷史資料  
↓  
天氣資料（Open-Meteo API）  
↓  
資料清理與整併  
↓  
站點 × 小時資料彙整  
↓  
特徵建立  
↓  
高需求定義  
↓  
Logistic Regression / Random Forest  
↓  
模型評估與結果分析

---

## 📊 High-Demand Definition

為避免不同站點因規模差異而使用相同門檻，本專題以：

**各站點自身租借量的第 80 百分位數（80th Percentile）**

作為高需求判定門檻。

透過站點自身的歷史需求分布判斷高需求，使不同規模站點之間能有較合理的比較基準。

---

## 🤖 Modeling

團隊使用兩種分類模型進行高需求預測：

- Logistic Regression
- Random Forest

並透過 Accuracy、Precision、Recall、F1 Score 與 ROC AUC 等指標評估模型表現。

> 模型建置與程式開發為小組專題成果，並非由我個人獨立完成。

---

## 👩‍💻 My Role

我在本專題主要負責：

- 將團隊完成的資料分析與模型結果整理為視覺化內容
- 整理站點需求、尖峰時段、星期與天氣等分析資訊
- 規劃簡報資訊架構與內容呈現順序
- 將較複雜的分析結果轉化為容易理解的圖表與說明
- 負責專題成果簡報的視覺設計與資訊呈現

透過這次小組專題，我練習的不只是呈現圖表，也包含如何理解團隊的分析結果，並將技術內容重新整理成適合報告與溝通的資訊。

---

## 🛠 Tools & Technologies Used in the Project

- Python
- pandas
- Open-Meteo API
- Logistic Regression
- Random Forest
- Data Visualization
- Machine Learning
- Presentation Design

> **Note:** 上述為整體小組專題使用的技術與工具；我的主要負責範圍為資料視覺化、資訊整理與簡報成果呈現。

---

## 📁 Project Type

**Group Project**

Python 爬蟲與資料分析分組專案｜第 02 組

- 組長：賴子渝
- 組員：王秀方
- 指導老師：江尚瑀

---

## 🔗 Portfolio

More projects:

**GitHub:** https://github.com/HsiuFang-Wang
