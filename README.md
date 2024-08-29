# SpaceX Mission Analysis 🚀

## Project Overview
This project aims to analyze SpaceX's mission data to predict the success of rocket landings and identify key factors that contribute to mission outcomes. Leveraging data from the SpaceX API and Wikipedia, we conduct extensive data wrangling, exploratory data analysis (EDA), and predictive modeling using machine learning algorithms. The project also features interactive visualizations and dashboards to provide actionable insights into SpaceX’s launch strategies, site performance, and orbital success rates.

## Objective
The primary objectives of this project are:
- To predict the success of SpaceX missions based on various factors such as launch sites, payload mass, and orbital inclinations.
- To analyze the impact of different variables on mission outcomes and identify key predictors of success.
- To create interactive visualizations that help stakeholders understand SpaceX's mission strategies and performance.

## Data Collection
The data used in this project was collected from two primary sources:
1. **SpaceX API**: Data on SpaceX launches, including launch sites, payloads, and mission outcomes, was retrieved using the SpaceX API.
2. **Wikipedia**: Additional information was scraped from Wikipedia to enrich the dataset with relevant historical data.

You can find the Jupyter notebooks used for data collection here:
- [API Data Collection Notebook](link-to-your-notebook)
- [Web Scraping Notebook](link-to-your-notebook)

## Data Wrangling
Data cleaning and preprocessing were performed to ensure the dataset was suitable for analysis. Key steps included:
- Handling missing values and outliers.
- Converting categorical variables into numerical formats.
- Creating new features to enhance model performance.

The complete data wrangling process is documented in the following notebook:
- [Data Wrangling Notebook](link-to-your-notebook)

## Exploratory Data Analysis (EDA)
Exploratory Data Analysis was conducted to uncover patterns and relationships within the data. Key insights include:
- The distribution of launches across different sites.
- The relationship between payload mass and mission success.
- Analysis of orbital inclinations and their impact on landing outcomes.

Visualizations and insights can be explored in the EDA notebook:
- [EDA Notebook](link-to-your-notebook)

## Predictive Modeling
Various machine learning models were employed to predict mission success:
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Decision Tree**
- **K-Nearest Neighbors (KNN)**

The best-performing model achieved an accuracy of over 94%, demonstrating its effectiveness in predicting landing outcomes. Model training and evaluation details are available in the following notebooks:
- [Model Training Notebook](link-to-your-notebook)

## Results
Key findings from the predictive analysis include:
- Launch site `X` has the highest success rate, making it a critical factor in mission planning.
- Payloads within the range of `A-B` kg have a higher probability of successful landings.
- Orbital inclinations between `C-D` degrees are more likely to result in mission success.

These results are supported by detailed visualizations and metrics available in the results notebook:
- [Results Notebook](link-to-your-notebook)

## Interactive Visualizations
Interactive maps and dashboards were created using Plotly Dash and Folium to visualize the geographical distribution of launch sites and the success rates of various missions. These tools allow for dynamic exploration of the data, providing stakeholders with valuable insights.

Explore the interactive visualizations here:
- [Interactive Visualization Notebook](link-to-your-notebook)

## Future Work
Potential improvements and extensions for this project include:
- Incorporating real-time data feeds from SpaceX's live API.
- Enhancing the model by including additional features such as weather conditions.
- Developing a web application to allow users to input data and receive mission success predictions.

## Contributors
- **Akhilesh Yadav** - [GitHub Profile](https://github.com/MathTechWhiz)
  
Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/MathTechWhiz/SpaceX_Mission_Analysis/issues).

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

This `README.md` provides a thorough overview of your project and guides users through understanding, setting up, and using your analysis.
