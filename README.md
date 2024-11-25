# **Analyzing Health Disparities: The Relationship Between Obesity, Diabetes, and Environmental Factors in U.S. Counties**

## **Description**

Our project focused on analyzing whether there is a significant relationship between the number of fast food restaurants and the prevalence of health conditions such as obesity and diabetes. To explore this, we utilized descriptive statistics, examined regional patterns, and conducted regression analyses to identify trends and potential correlations. Each team member contributed by addressing a specific research question, allowing us to build a comprehensive understanding of how fast food availability might influence public health outcomes. This approach enabled us to investigate broader public health challenges and disparities.

### **Motivation**
The project aims to investigate the potential relationship between the number of fast food restaurants and the prevalence of health conditions like obesity and diabetes. By identifying trends and correlations, we can better understand how the availability of fast food impacts public health and propose data-driven interventions to address these challenges.

### **Technologies Used**
- Python
  - Libraries: `pandas`, `matplotlib`, `hvplot`, `numpy`, `scipy.stats`
- Jupyter Notebook
- Data Sources: Food Environment Atlas
- Visualization Tools: Saved plots in PNG and HTML formats

### **Challenges**
The team overcame challenges such as cleaning complex datasets, handling missing geographical data, and interpreting statistical results for meaningful insights.

---

## **Table of Contents**
1. [Description](#description)
2. [Installation Instructions](#installation-instructions)
3. [Usage](#usage)
4. [Credits](#credits)


---

## **Installation Instructions**
1. Clone the repository or download the project folder.
2. Ensure you have Python installed on your machine (version 3.8 or higher recommended).
3. Install the required Python libraries:
   ```bash
   pip install pandas matplotlib hvplot scipy numpy


## **Usage**
1. Each team member’s Jupyter Notebook contains the code for their specific analysis question:
   - **Carlos_Analysis**: Descriptive analysis and comparison of obesity and diabetes rates between metropolitan and population loss counties.
   - **dataExploration**: Analysis to explore relationships between obesity/diabetes rates and number of fast-food restaurants.
   - **Data_Emiliano**: Descriptive analysis of how the age factor could protect more or make more vulnarable to the population to the effects of fast food on health

2. **Visualizations**:
   Each notebook saves plots and maps into a shared `Visualizations` folder for easy access. These include scatter plots, bar charts, and geographic maps.
   - **Carlos_Visualizations**:png files of bargraphs, scatterplots, and a html of an interactive regional map of relationships between obesity/diabetes rates in metropolitan and population loss counties.
   - **output_data_ages**:png files of the histogramas and scatterplots of the t-test to determine the relationship between the number of fast-food restaurants and health deseases for the population over 65 and the popultion under 18 years old
   - **Images**: png files of descriptive analysis and scatterplots of relationships between obesity/diabetes rates and number of fast-food restaurants.

3. **Steps to Run**:
   - Open the relevant Jupyter Notebook.
   - Run the cells sequentially to reproduce the analysis.
   - Access saved visualizations in the `Visualizations` folder for insights.

The repository also includes the Written Report in PDF and the presentation named "All about obesity" in PDF.


## **Credits**
- **Team Members**:
  - **[Carlos Fernando Sánchez Lozano]**: Developed the `Carlos_Analysis` Jupyter Notebook and created the `Carlos_Visualizations` folder, where all images generated from the notebook are stored.
  - **[Emiliano Zarza Camacho]**: Analysis to explore whether the population's age plays a positive or negative role in the relationship between obesity/diabetes rates and the number of fast-food restaurants. You can find it on `Data_Emiliano`
  - **[Itzel Vázquez Sánchez]**: Analysis to explore relationships between obesity/diabetes rates and number of fast-food restaurants.

**Data Source**: 
  - [Food Environment Atlas](https://www.ers.usda.gov/data-products/food-environment-atlas/data-access-and-documentation-downloads/). (United States Department of Agriculture)
 

