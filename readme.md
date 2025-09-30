# İzmir Traffic Accident Analysis

This project is developed for analyzing traffic accidents in İzmir. The dataset contains traffic accidents that occurred between 2021-2022.

## 📊 Dataset

- **Source**: İzmir Municipality Traffic Data
- **Date Range**: 2021-2022
- **Total Records**: 13,339 accident records
- **Data Format**: CSV (semicolon separated)

### Data Columns
- `date`: Accident date
- `street`: Street name
- `direction`: Direction information
- `location`: Location details
- `type`: Accident type (Property Damage, Injury Accident, Chain Accident, etc.)
- `accidentTime`: Accident time
- `interventionTime`: Intervention time

## 🚀 Installation

1. Install required packages:
```bash
pip install -r requirements.txt
```

2. Start Jupyter Notebook:
```bash
jupyter notebook
```

## 📈 Analysis

The project includes the following analyses:

- **Data Cleaning**: Removing missing values and unnecessary records
- **Accident Type Filtering**: Analyzing only traffic accidents (excluding breakdown records)
- **Date Analysis**: Monthly and yearly accident distributions
- **Location Analysis**: Accident density by street and direction

## 📁 File Structure

```
├── data.csv                 # Raw dataset
├── data_anaylsis.ipynb     # Main analysis notebook
├── requirements.txt        # Python package requirements
└── readme.md              # This file
```

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas**: Data manipulation
- **Matplotlib & Seaborn**: Visualization
- **Jupyter Notebook**: Analysis environment
- **NumPy**: Numerical computations

## 📝 Notes

- Dataset contains Turkish characters
- Breakdown records and other non-traffic events are filtered during analysis
- Date format: DD.MM.YYYY
