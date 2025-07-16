# 🫁 Pulmonary Disease Risk Analysis – Power BI Dashboard

This interactive Power BI dashboard explores the key factors that may contribute to pulmonary (lung) disease using a medical dataset. The analysis compares the impact of **environmental** risks (such as smoking and pollution exposure) with **genetic** background (family history), offering a data-driven understanding of potential causes.

---

## 📊 Dashboard Overview

The dashboard consists of two main pages:

### ✅ Page 1: Pulmonary Disease Risk Summary
- 📌 High-level indicators:
  - Total disease cases
  - Disease rate
  - Average age of patients
- 📈 Visual breakdowns:
  - Pollution exposure distribution
  - Smoking impact
  - Age group analysis
  - Gender distribution
  - Family history comparison

### 🔍 Page 2: Deep Risk Factor Analysis
- 🧬 Environmental vs Genetic risk breakdown
- Detailed visuals comparing:
  - Pollution exposure vs family history
  - Smoking impact on non-genetic cases
  - Family history prevalence by age group
- ⚠️ **Key Takeaway:**  
  > 69.8% of patients had **no family history**, highlighting environmental risks — especially pollution — as major contributors.

---

## 🛠️ Tools & Techniques Used

- **Power BI Desktop**
- Data preparation using **Power Query**
- Custom **DAX measures** to:
  - Calculate disease rates
  - Analyze group proportions
  - Convert binary values to readable labels
- Interactive **Slicers** for:
  - Gender
  - Smoking status
  - Pollution exposure
  - Age groups

---

## 📁 Dataset Overview

- **Source:** Synthetic lung disease dataset
- **Fields:**
  - `AGE`, `GENDER` (0 = Female, 1 = Male)
  - `SMOKING`, `POLLUTION`, `FAMILY_HISTORY`
  - `DISEASE` (1 = diagnosed, 0 = not diagnosed)

---

## 🎯 Key Insights

- **Environmental exposure** (pollution, smoking) appears more influential than genetic history.
- **69.8%** of diagnosed patients reported **no family history**, suggesting external risk factors are more dominant.
- **Pollution exposure** significantly increases disease occurrence, even in **non-smokers**.
- **Younger patients** are more likely to have a family history than older ones, hinting at shifting risk patterns.

---

## 🚀 Future Enhancements

- Add additional variables like stress, physical activity, or nutrition (if available).
- Build a predictive model using machine learning on the same dataset.
- Publish the report online with a Power BI public link (optional).

---

## 👤 Author

**Umniyat Hausawi**  
Aspiring Data Analyst | Career shifter to data | Passionate about healthcare analytics  
📍 Riyadh, Saudi Arabia

---

