# U.S. Trade Flow Composition Analysis and Visualization (2020–2024)

## 📌 Project Overview
The United States, one of the world’s largest economies, plays a critical role in global trade. This project analyzes the U.S. trade network from 2020 to 2024, focusing on three major trade flows: general imports, domestic exports, and foreign exports.

Using data visualization and network analysis, the project aims to uncover key trade structures, identify major partners, and reveal strategic insights for global commerce.

---

## 📊 Data
- Source: DATAWEB http://dataweb.usitc.gov/trade/search/Export/HTS 
- Includes:
  - Trade flow types (imports, exports, re-exports) (2020–2024)
  - Country-level trade relationships (2020–2024)
  - Product categories (section codes) (2020–2024)
  - Port and regional trade data (2020–2024)

---

## 🛠 Methods

### 1. Data Processing
- Cleaned and structured multi-year trade data using **Pandas**
- Created pivot tables for trade flow analysis

### 2. Network Analysis
- Built **directed trade networks** using NetworkX
- Calculated centrality metrics to identify key trade partners
- Extracted top nodes driving global trade flows

### 3. Similarity Analysis
- Constructed district-section matrices
- Applied **cosine similarity** to compare trade patterns across regions and years

### 4. Visualization
- Used **Matplotlib** for data visualization
- Exported network data for **Gephi** to visualize structural changes (2020 vs 2024)

---

## 📈 Key Insights
- Identified core countries acting as central nodes in U.S. trade
- Revealed structural differences between import and export networks
- Detected evolving trade patterns between 2020 and 2024
- Highlighted regional trade similarities using cosine similarity

---

## 💡 Business Impact
- Helps policymakers understand trade dependencies and risks
- Supports businesses in identifying strategic trade partners
- Provides insights into global supply chain structure and resilience

---

## 🔗 Tools & Technologies
- Python (Pandas, NumPy)
- NetworkX (graph modeling)
- Scikit-learn (cosine similarity)
- Matplotlib (visualization)
- Gephi (network visualization)

---

## 📁 Project Structure
- `U.S. Trade(2020-2024)_Final Project.ipynb` → Main analysis notebook
- Data files → Trade datasets (not included due to size)
