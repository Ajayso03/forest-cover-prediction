# forest-cover-prediction
Here i have build a system that predict forest cover based on the data given. 
# 🌲 Forest Cover Type Prediction

## 📌 Objective
The goal of this project is to build a machine learning system that can predict the **type of forest cover** for a given 30m x 30m patch of land in the forest.  
The dataset is provided by the **U.S. Forest Service** and was collected from the **Roosevelt National Forest in northern Colorado**.

---

## 📂 Dataset
The dataset contains cartographic variables such as elevation, aspect, slope, soil type, and wilderness area designation.  
The target variable is **Cover_Type**, which represents 7 possible forest cover types:

- **1** - Spruce/Fir  
- **2** - Lodgepole Pine  
- **3** - Ponderosa Pine  
- **4** - Cottonwood/Willow  
- **5** - Aspen  
- **6** - Douglas-fir  
- **7** - Krummholz  

### 🔑 Main Features:
- `Elevation` – Elevation in meters  
- `Aspect` – Aspect in degrees azimuth  
- `Slope` – Slope in degrees  
- `Horizontal_Distance_To_Hydrology` – Distance to nearest surface water features  
- `Vertical_Distance_To_Hydrology` – Vertical distance to water features  
- `Horizontal_Distance_To_Roadways` – Distance to nearest roadway  
- `Hillshade_9am / Noon / 3pm` – Hillshade indices  
- `Horizontal_Distance_To_Fire_Points` – Distance to nearest wildfire ignition points  
- `Wilderness_Area` – 4 binary columns (presence/absence)  
- `Soil_Type` – 40 binary columns (presence/absence)  

---

## 🛠️ Project Workflow
1. **Data Preprocessing** – Handling categorical/binary features and scaling numeric variables.  
2. **Exploratory Data Analysis (EDA)** – Understanding feature distribution and correlations.  
3. **Model Training** – Using classification models such as:
   - Decision Tree  
   - Random Forest  
   - Gradient Boosting (XGBoost/LightGBM)  
4. **Model Evaluation** – Accuracy, Confusion Matrix, and Classification Report.  
5. **Deployment** – Optional deployment with **Streamlit** for interactive predictions.  

---

## 📊 Results
- Achieved **high accuracy** with ensemble methods such as **Random Forest** and **Gradient Boosting**.  
- Feature importance showed that **Elevation, Soil_Type, and Wilderness_Area** play key roles in classification.  

---

## 🚀 How to Run
### 🔧 Requirements
Install dependencies:
```bash
pip install -r requirements.txt
