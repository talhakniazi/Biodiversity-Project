# 🌿 Biodiversity in National Parks

## 📌 Project Overview

This project explores biodiversity data from multiple U.S. National Parks using Python for data analysis and visualization.  
The analysis focuses on species observations, conservation status, endangered species distribution, protected species percentages, and park-wise biodiversity trends.

Using datasets containing species information and park observations, this project uncovers patterns in wildlife conservation and species diversity through exploratory data analysis (EDA) and visualizations.

---

# 🎯 Objectives

The main objectives of this project are:

- Analyze biodiversity across national parks
- Explore conservation statuses of different species
- Identify endangered species observation trends
- Compare species categories across parks
- Examine protected vs non-protected species
- Visualize biodiversity data using charts and heatmaps

---

# 📂 Datasets Used

## 1. observations.csv
Contains species observation counts across national parks.

### Columns:
- scientific_name
- park_name
- observations

---

## 2. species_info.csv
Contains species category and conservation information.

### Columns:
- category
- scientific_name
- common_names
- conservation_status

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📊 Project Analysis

## 1. Data Loading and Exploration

The datasets were loaded using Pandas and explored to understand:
- Dataset dimensions
- Missing values
- Unique parks
- Species categories
- Observation distributions

### Key Findings
- 23,296 observation records
- 5,824 species records
- 4 national parks included in the dataset

---

## 2. Conservation Status Analysis

Species were grouped by category and conservation status to identify protected and endangered wildlife.

### Key Findings
- Mammals and Birds had the highest number of protected species
- Vascular Plants had the largest total species count
- Endangered species were relatively small in number compared to total species

---

## 3. Total Observations by National Park

Observation counts were aggregated for each park to compare biodiversity activity.

### Key Findings
- Yellowstone National Park had the highest observations
- Great Smoky Mountains National Park had the lowest observations

---

## 4. Species Observations by Category

Species observations were analyzed across categories such as:
- Mammals
- Birds
- Fish
- Amphibians
- Reptiles
- Plants

### Key Findings
- Vascular Plants dominated total observations
- Amphibians and Reptiles had the fewest observations

---

## 5. Park-wise Category Analysis

Species categories were compared across all national parks.

### Key Findings
- Yellowstone consistently showed the highest biodiversity observations
- Vascular Plants were dominant in every park

---

## 6. Endangered Species Analysis

Endangered species observations were isolated and analyzed separately.

### Key Findings
- Mammals had the highest endangered observations
- Gray Wolf showed the highest endangered observation counts
- Yellowstone National Park recorded the highest endangered species observations overall

---

## 7. Protected Species Percentage

Species were classified into:
- Protected
- Non-Protected

### Key Findings
- Mammals had the highest percentage of protected species
- Vascular Plants had the lowest protection percentage

---

## 8. Heatmap Visualization

A heatmap was created to visualize species observations across parks and categories.

### Key Findings
- Yellowstone had the darkest concentration due to high observations
- Amphibians and Reptiles showed lower observation density

---

## 9. Squirrel Species Analysis

A focused analysis was performed on squirrel species observations across parks.

### Key Findings
- Yellowstone National Park had the highest squirrel observations
- Carolina Northern Flying Squirrel was the only endangered squirrel species observed

---

## 10. Least Observed Species

Species with the lowest total observations were identified.

### Key Findings
- Whooping Crane had the lowest observation count
- Several endangered species appeared among the least observed wildlife

---

# 📈 Visualizations Included

The project includes multiple visualizations such as:

- Bar Charts
- Grouped Bar Charts
- Heatmaps
- Conservation Comparisons
- Species Observation Analysis

---

# 📌 Conclusion

This analysis highlights important biodiversity and conservation patterns across U.S. National Parks.

The findings show that:
- Yellowstone National Park has the richest biodiversity observations
- Vascular Plants dominate ecosystem observations
- Mammals contain the highest number of endangered observations
- Protected species represent only a small portion of total biodiversity

The project demonstrates how data analysis and visualization can provide valuable insights into wildlife conservation and ecosystem monitoring.

---

# 🚀 Future Improvements

Possible future enhancements include:

- Interactive dashboards using Plotly or Tableau
- Geographic visualizations using maps
- Time-series biodiversity analysis
- Machine learning models for conservation prediction

---

# 📎 Author

Muhammad Talha Khan

Freelance Python Developer & Data Analyst
