# Biodiversity Analysis of Species in National Parks

## Project Overview
This project focuses on analyzing biodiversity data from national parks to uncover insights about species and their conservation statuses. The analysis uses two datasets: one containing species information and the other detailing their recorded observations in four major national parks. The project aims to identify trends in conservation, species sightings, and the relationship between species and their habitats.

---

## Datasets

### 1. `species_info.csv`
- **Rows**: 5,824
- **Columns**:
  - `category`: The type of species (e.g., Mammal, Bird).
  - `scientific_name`: Scientific name of the species.
  - `common_names`: Common names of the species.
  - `conservation_status`: Conservation status (e.g., Endangered, Species of Concern, In Recovery).
- **Key Notes**:
  - Missing conservation statuses for 5,633 rows.
  - Contains unique categories like Mammal, Bird, Reptile, etc.

### 2. `observations.csv`
- **Rows**: 23,296
- **Columns**:
  - `scientific_name`: Scientific name of the species.
  - `park_name`: Name of the national park where the species was observed.
  - `observations`: Number of recorded observations in the past 7 days.
- **Key Notes**:
  - No missing data.
  - Four unique park names: Great Smoky Mountains National Park, Yosemite National Park, Bryce National Park, and Yellowstone National Park.

---

## Key Questions Explored

1. **Are certain types of species more likely to be endangered?**
   - Analysis revealed that mammals and fish are more likely to be endangered compared to other categories like birds or plants.

2. **Which species were most spotted at each park?**
   - Identified the most frequently observed species in each park by analyzing the observations data.

3. **Are the differences between species and their conservation statuses significant?**
   - A Chi-Square test was performed to evaluate the significance of these differences.

---

## Tools and Libraries
- **Python**
  - Libraries: Pandas, Matplotlib, Seaborn, Scipy
- **Jupyter Notebook** for interactive analysis and visualization.

---

## Visualizations
Key visualizations include:
- Bar charts to compare species categories and their conservation statuses.
- Scatterplots of species observations by park.
- Heatmaps to display relationships between species and their habitats.

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install required Python libraries:
   ```bash
   pip install pandas matplotlib seaborn scipy
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook biodiversity_analysis.ipynb
   ```
4. Run all cells to reproduce the analysis and visualizations.

---

## Insights
- **Mammals** and **fish** are disproportionately represented among endangered species.
- **Great Smoky Mountains National Park** recorded the most diverse species sightings.
- The differences in conservation statuses across species categories are statistically significant.

---

## Future Work
- Expand the analysis by incorporating additional datasets (e.g., climate data).
- Build interactive dashboards using Plotly or Tableau.
- Investigate specific threats to endangered species and suggest conservation measures.

---

## Author
**Ata Shaikh**
- Data Science Enthusiast
- Connect with me on [LinkedIn](https://www.linkedin.com/in/theatashaikh) or [GitHub](https://github.com/theatashaikh).

---

### License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
