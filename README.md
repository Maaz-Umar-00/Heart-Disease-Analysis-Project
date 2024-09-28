<h1 style="font-family: 'Poppins', sans-serif; font-weight: 700; color: #1c1c1c; background: white; padding: 15px; border-radius: 10px; text-align: center; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5); letter-spacing: 1px; text-transform: capitalize; font-size: 1.5rem;">
<span style="color: #333333;">Heart disease analysis</span>
</h1>



## Overview:
This project is designed to unlock the potential of heart disease data, transforming it into actionable insights that can shape healthcare strategies. By diving deep into the data, we aim to discover key risk factors, patterns, and trends that can lead to more effective healthcare interventions, improving both patient outcomes and operational efficiency.

### Key Objectives:

- **Pinpointing high-risk populations:** By identifying which groups are most at risk, healthcare providers can prioritize resources and design targeted interventions, ultimately reducing the burden of heart disease.
- **Proactive healthcare planning:** Analyzing trends in the data can help forecast future healthcare needs, allowing for earlier intervention and more personalized care strategies for at-risk individuals.
- **Optimizing resource allocation:** Insights from the data will help in making informed decisions about where to allocate healthcare resources most effectively, ensuring better patient care and minimizing costs.
- **Strategic policy development:** With data-backed insights, healthcare organizations can refine their policies and strategies, improving the efficiency of treatments and enhancing overall healthcare delivery.

This project aims to provide healthcare providers with the intelligence they need to make smarter, data-driven decisions. By aligning heart disease insights with operational goals, the results will enable more efficient healthcare management, better patient care, and ultimately a healthier population.

The **SQL** queries used to **analyze** the data can be found [here](https://github.com/Maaz-Umar-00/Heart-Disease-Analysis-Project/blob/main/02_heart_diseases_data_analysis.ipynb).\
The **SQL** queries used to **clean** the data can be found [here](https://github.com/Maaz-Umar-00/Heart-Disease-Analysis-Project/blob/main/01_heart_disease_data_cleaning.ipynb).



## Data Structure & Initial Checks.
The dataset used for this analysis is sourced from [https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data]) and includes the following features:
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol Level
- Fasting Blood Sugar
- Resting ECG Results
- Maximum Heart Rate
- Exercise Induced Angina
- Oldpeak (depression induced by exercise)
- Slope of the Peak Exercise ST Segment
- Number of Major Vessels (0-3)
- Thalassemia
- Target Variable (Heart Disease Presence)

## Installation
To run this project, you will need to have the following installed:
- Python 3.x
- Pandas
- Plotly
- Matplotlib
- NumPy

You can install the necessary libraries using pip:
```bash
pip install pandas plotly matplotlib numpy
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/heart-disease-analysis.git
   cd heart-disease-analysis
   ```

2. Load the dataset and perform data analysis and visualization using Jupyter Notebook or your preferred IDE.

3. The analysis and visualizations are saved in the `interactive_plots` folder. You can view them directly in your browser.

## Visualizations
This project includes several visualizations:
- Box plots to identify outliers in various health metrics.
- Bar plots showing the distribution of heart disease by age and gender.
- Histograms displaying cholesterol levels and blood pressure distributions.
- Interactive plots for a more detailed examination of the data.

## Conclusion
Through this analysis, we aim to provide insights into heart disease trends and risk factors. The findings can be beneficial for healthcare professionals, researchers, and individuals interested in understanding heart health better.

## Acknowledgments
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Heart+Disease) for providing the dataset.
- Plotly and Matplotlib for their excellent data visualization libraries.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
