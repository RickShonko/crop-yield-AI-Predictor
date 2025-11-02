# 🌾 AI for Sustainable Development

This repository demonstrates the design of a **Machine Learning model** that addresses one of the **UN Sustainable Development Goals (SDGs)** — **SDG 2: Zero Hunger**.  
The project showcases how **AI can support sustainable agriculture** by predicting crop yields based on environmental data such as rainfall, temperature, and soil quality.

---

## 🎯 Project Goal

To develop a data-driven solution that helps farmers and policymakers **forecast crop yields** and **optimize food production**, reducing hunger and promoting sustainable resource use.

---

## 🧠 Machine Learning Approach

- **Problem Type:** Regression  

- **Approach:** Supervised Learning  

- **Algorithm Used:** Linear Regression 

- **Libraries:** `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`  

---

## 📊 Dataset
The dataset contains environmental and agricultural data, including:

| Feature | Description |

|----------|--------------|

| `Rainfall` | Annual rainfall in millimeters |

| `Temperature` | Average temperature (°C) |

| `Soil_Quality` | Soil fertility index (0–100) |

| `Crop_Yield` | Actual yield (tons per hectare) |

📁 File: `crop_yield_data.csv`  
*(Synthetic dataset generated for demonstration purposes.)*

---

## ⚙️ Project Workflow
1. **Data Loading:** Import and explore the dataset.  
2. **Preprocessing:** Handle missing values and select relevant features.  
3. **Model Training:** Train a Linear Regression model.  
4. **Evaluation:** Measure model performance using MAE, MSE, and R².  
5. **Visualization:** Plot actual vs. predicted yield for insights.  
6. **Ethical Reflection:** Consider fairness, bias, and sustainability impacts.

---

## 🧩 Example Results

| Metric | Value (Example) |

|--------|------------------|
| Mean Absolute Error (MAE) | 3.25 |

| R² Score | 0.88 |

📈 Visualization:  
The scatter plot below shows how closely the model’s predictions match actual crop yields.  
*(Run the notebook to generate your own plot.)*

---

## 🌍 Ethical Reflection
> **Bias:** A dataset from one region may not generalize globally.  
> **Fairness:** Include data from multiple climates to ensure equal performance.  
> **Sustainability:** Accurate yield prediction reduces waste and improves food security.  

By promoting data-driven decision-making in agriculture, this project contributes directly to **SDG 2: Zero Hunger**.

---

## 🧰 Tools & Environment
- Python 3.10+
- Jupyter / VS Code
- Virtual Environment (`venv`)

### Installation
```bash
# Activate your virtual environment
venv\Scripts\activate     # Windows
# OR
source venv/bin/activate  # macOS/Linux

# Install dependencies
pip install -r requirements.txt

👨‍💻 Author

[Shonko]
AI & Machine Learning Student — PLP Academy
#AI_Assignment | October 2025