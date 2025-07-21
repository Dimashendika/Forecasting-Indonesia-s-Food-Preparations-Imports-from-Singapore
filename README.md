# Forecasting Indonesia’s Food Preparations Imports from Singapore

To forecast Indonesia’s import value of food preparation products (HS Code 210690) from Singapore using ARIMA time series analysis, based on ASEAN trade data (2013–2023)

---

## 📌 Objective
- Identify the top imported food preparation products.
- Understand which ASEAN countries are the largest suppliers.
- Analyze historical trends in trade values (2013–2023).
- Forecast 2024 import value using time series modeling.

##  Dataset Overview

- **Source**: International Trade Centre Data
- **Years**: 2013–2023
- **Countries**: Indonesia (as reporter) importing from Malaysia, Philipphines Singapore, Thailand, and Vietnam
- **Trade Type**: Imports only
- **Unit of Measure**: Trade value (USD Thousand)
- **Product Scope**: Focused on 11 selected FMCG-related HS Codes
- **Link**: https://www.trademap.org/Index.aspx?nvpm=1%7c%7c%7c%7c%7c%7c%7c%7c%7c%7c%7c%7c%7c%7c%7c%7c%7c

---

###  Selected HS Codes:

| HS Code | Product Name (Label)                                       | Description (English)                                                                            |
| ------- | ---------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| 110100  | Wheat or meslin flour                                      | Milled flour from wheat or meslin, a key raw material for bakery and food processing industries. |
| 150790  | Refined soya-bean oil (excl. crude or chemically modified) | Edible refined soybean oil used in cooking, frying, and industrial food production.              |
| 151620  | Hydrogenated vegetable fats and oils                       | Solid or semi-solid fats used in baking and food manufacturing (e.g., margarine).                |
| 160414  | Prepared/preserved tuna (whole or in pieces)               | Canned or preserved tuna products for direct consumption or foodservice.                         |
| 170410  | Chewing gum                                                | Flavored gum products, often sugar-coated, used for confectionery.                               |
| 190190  | Malt extract and starch-based food preparations            | Ingredients used in cereals, energy bars, and infant food, often for nutritional value.          |
| 190540  | Rusks and toasted bread                                    | Dry baked goods, typically long shelf-life, used as snacks or breakfast foods.                   |
| 190590  | Bread, pastry, cakes, biscuits, etc.                       | A wide range of baked goods including cookies, pastries, and cakes.                              |
| 210390  | Preparations for sauces and condiments                     | Mixed seasonings and ready-made sauces (excl. soy sauce), often used in fast-moving kitchens.    |
| 210690  | Food preparations, n.e.s.                                  | Other processed or mixed food items not classified elsewhere (e.g., instant food mixes).         |
| 220299  | Non-alcoholic beverages (excl. juice, milk, beer, water)   | Flavored drinks such as energy drinks, iced tea, or soda (excluding common categories).          |

---

## 🧰 Tools & Libraries
- `Python`
- `Pandas`,
- `Matplotlib`,
- `Seaborn`
- `statsmodels` (for ARIMA forecasting)
- `Jupyter Notebook`

---

## 📊 Key Results
- HS 210690 ("Food preparations, n.e.s.") was the **top imported product** in 2023: **248.36 million USD**.
- **Singapore and Malaysia** were the main suppliers (101M and 90M USD respectively).
- Trade surged post-COVID (2020–2022) before declining slightly in 2023.
- **Forecast for 2024** using ARIMA: **91 million USD**  
  - 📌 **Actual 2024 import value (from trade data): 88 million USD** — highly accurate prediction.

---


