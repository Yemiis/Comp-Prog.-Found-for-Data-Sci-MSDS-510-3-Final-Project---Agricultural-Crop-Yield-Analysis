## 📊 Dataset

The dataset used in this project is an agricultural crop yield dataset containing approximately **1,000,000 simulated records**. It includes multiple environmental and farming-related variables used to analyze crop performance and yield patterns.

### Key Features:
- Region
- Soil Type
- Crop Type
- Rainfall (mm)
- Temperature (°C)
- Fertilizer Usage (True/False)
- Irrigation Usage (True/False)
- Weather Condition
- Days to Harvest
- Yield (tons per hectare)

### Purpose:
This dataset is used to:
- Analyze relationships between environmental factors and crop yield
- Compute statistical metrics such as averages and percentages
- Evaluate the impact of irrigation and fertilizer on productivity
- Identify patterns and correlations within agricultural data

### Notes:
- The dataset is simulated and used for academic purposes
- Stored as a compressed `.zip` file for efficient upload and download
- Extract the file before running the notebook

### Usage:
Place the dataset in the `data/` folder before running the analysis:

```python
df = pd.read_csv("data/crop_yield.csv")
link: https://www.kaggle.com/datasets/samuelotiattakorah/agriculture-crop-yield
