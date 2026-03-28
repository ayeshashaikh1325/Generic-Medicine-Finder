# 💊 Generic Medicine Finder
### A Generic–Brand Medicine Comparison Engine

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Domain](https://img.shields.io/badge/Domain-Healthcare-red)

---

## 📌 Overview
A data-driven web-based tool that helps users find affordable generic 
substitutes for branded medicines in India. Built after personally 
witnessing the financial burden of expensive branded medicines, this 
engine uses salt-based matching and fuzzy search to instantly identify 
cheaper alternatives with identical active ingredients.

> 💡 Generic medicines are 30–85% cheaper than branded medicines  
> despite containing the **same active pharmaceutical ingredients.**

---

## 🎯 Objectives
- Identify branded medicines and retrieve their chemical compositions
- Find accurate generic substitutes via salt (API) matching
- Calculate and display price differences and potential savings
- Deliver results through a clean, responsive web interface

---

## ⚙️ How It Works
```
User Search → Fuzzy Matching → Salt-Based Mapping → Price Comparison → Results
```

1. **Exact/Fuzzy Search** — handles misspellings and partial inputs (RapidFuzz)
2. **Salt Matching** — maps branded medicines to generics via active ingredient
3. **Price Sorting** — displays cheapest generic first
4. **Savings Calculation:**
```
Savings% = (Brand Price - Generic Price) / Brand Price × 100
```

---

## 📂 Dataset
- **Sources:** CDSCO, Jan Aushadhi (PMBJP), NPPA, ICMR
- **Files:** `brands.csv`, `generics.csv`, `compositions.csv`
- **Validation:** Cross-checked with 1mg & NetMeds

---

## 📈 Results
| Metric | Value |
|--------|-------|
| Exact Search Accuracy | 100% |
| Fuzzy Search Accuracy | ~92–95% |
| Price difference (Brand vs Generic) | 30–85% cheaper |
| Max price gap observed | Up to 300% |
| Search response time | 50–120ms |

---

## 🛠️ Tech Stack
| Layer | Technology |
|-------|-----------|
| Frontend | HTML, CSS, Vanilla JavaScript |
| Backend | Python Flask |
| Matching Engine | RapidFuzz, Pandas |
| Storage | CSV (brands, generics, compositions) |

---

## 🚀 Features
- 🔍 Live search with autocomplete suggestions
- 💊 Generic substitute cards with composition details
- 💰 Price comparison & savings percentage display
- 📱 Responsive design — mobile & desktop friendly
- ⚡ Results in under 200ms

---

## 🔮 Future Scope
- Integration with CDSCO & Jan Aushadhi live APIs
- ML-based substitute prediction for complex multi-salt drugs
- Android/iOS mobile app
- Multilingual support (Hindi, Marathi, Tamil)
- AI-powered chat assistant

---

## 👤 Author
**Ayesha Shaikh**  
Supervised by: Dr. Jagdeesh Tawde | Vishwakarma University, Pune
