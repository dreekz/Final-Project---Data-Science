# Data-Science-Project-Hit---Portugal-Investments
## Portugal Real Estate 

### The research question: 
The goal of this project is to use classification models to identify properties that are good for investment.  

### Why:
In recent years, Jews who could prove that they were
deported from Spain, could submit an application to
the Portuguese authorities and the Jewish community
living in Porto or Lisbon, and ask for citizenship in
Portugal only by proving that they are descendants of
those deported from Spain

At the end of 2022, the Portuguese government
decided to tighten the conditions for obtaining
citizenship and a Portuguese passport for the
descendants of those deported from Spain, and from
now on you also have to show affinity to the state of
Portugal
One of these ways is to invest or purchase real estate in
Portugal.

We decided to check whether it is possible to analyze
the information on properties in Portugal using the
Remax Portugal website, and to determine what is a
good property for investment in Portugal

The goal is to help those Jews who want to become
citizens in Portugal and are now faced with the
tightening of the conditions for obtaining citizenship

### DATA: 
The Data we scrapped from https://www.remax.pt/en/
before handling and cleanning we gained 11665 properties for buy
and 1452 properties to rent.


### ALGORITHMS: 
At first we built a linear regression equation to predict rents for rental properties.

the model we achieved
We operated on properties to buy.

We calculated the monthly profits on the property that the property owner receives from rent, and subtracted the monthly expenses that the property owner loses,
which is the mortgage and current monthly expenses such as taxes, insurance and the like.

After data preparation and EDA, we built a base of machine learning and classification models.



### TOOLS: 
Selenium
Beautiful Soup 
Pandas
matplotlib 
Regression
classification
sklearn.  

### CONCLUSIONS: 
It can be observed that the accuracy results were
XGBoost 0.688
SVM 0.697
Gaussian NB 0.651
Dec Tree 0.665
Random Forest 0.683
KNN 0.671
LR 0.683

we saw the best model we checked was the SVM 
with the 0.697 accuracy
=======
# Portugal Real Estate Investment Analysis

## Project Overview
This data science project aims to identify lucrative real estate investment opportunities in Portugal using classification models. Our work is particularly relevant for individuals seeking Portuguese citizenship through property investment, in light of recent changes to citizenship requirements.

## Project Video Presentation

We've created a video presentation that provides an in-depth overview of our project, methodology, and findings. This video offers a comprehensive look at our work on Portugal real estate investment analysis.

[![Portugal Real Estate Investment Analysis](https://img.youtube.com/vi/5A7JlxqHDtU/0.jpg)](https://www.youtube.com/watch?v=5A7JlxqHDtU)

In this video, my partner and I walk you through:
- The motivation behind our project
- Our data collection and analysis process
- Key insights from our machine learning models
- Practical applications of our findings for potential investors

We recommend watching this video to get a full understanding of our project's scope and impact.

## Table of Contents
1. [Project Video Presentation](#project-video-presentation)
2. [Research Question](#research-question)
3. [Background](#background)
4. [Data](#data)
5. [Methodology](#methodology)
6. [Tools and Technologies](#tools-and-technologies)
7. [Results](#results)
8. [Conclusions](#conclusions)
9. [Installation and Usage](#installation-and-usage)
10. [Contributing](#contributing)
11. [License](#license)

## Research Question
How can we use data science and machine learning techniques to identify properties in Portugal that are good for investment, particularly for individuals seeking citizenship?

## Background
Recent changes in Portuguese law have tightened the conditions for obtaining citizenship for descendants of those deported from Spain. This change affects many Jewish individuals who could previously apply for Portuguese citizenship based on their heritage. Now, applicants must demonstrate a stronger connection to Portugal.

One way to demonstrate this affinity is through real estate investment in Portugal. This new requirement has created a need for informed investment decisions in the Portuguese real estate market. Our project aims to assist potential investors in making data-driven decisions about property investments in Portugal, serving both their citizenship goals and financial interests.

## Data
We collected our data through web scraping techniques, focusing on the Remax Portugal website (https://www.remax.pt/en/). Our dataset includes:
- 11,665 properties for sale
- 1,452 properties for rent

This comprehensive dataset includes various features such as:
- Property location
- Price
- Size (square meters)
- Number of bedrooms and bathrooms
- Property type (apartment, house, etc.)
- Various amenities and characteristics

The diversity and scale of our dataset allow for robust analysis and modeling, as demonstrated in our [video presentation](#project-video-presentation).

## Methodology
Our approach to this project involved several key steps, which are detailed in our [project video](#project-video-presentation). In summary:

1. Data Collection: We employed web scraping techniques using Selenium and Beautiful Soup to gather data from the Remax Portugal website.

2. Data Cleaning and Preprocessing: We handled missing values, standardized formats, and prepared the data for analysis.

3. Exploratory Data Analysis (EDA): We conducted thorough EDA to understand the distributions, relationships, and patterns within our data.

4. Feature Engineering: We created new features and transformed existing ones to better capture the factors influencing property investment potential.

5. Model Development: 
   - We built a linear regression model to predict rental prices for properties.
   - We developed classification models to identify properties with good investment potential.

6. Model Evaluation and Comparison: We assessed and compared the performance of various classification models to determine the most effective approach for our problem.

Each of these steps played a crucial role in our analysis, and you can see them explained in more detail in our video presentation.

## Tools and Technologies
Our project leveraged a variety of data science tools and technologies:
- Python: Our primary programming language
- Pandas: For data manipulation and analysis
- Matplotlib and Seaborn: For data visualization
- Scikit-learn: For implementing machine learning models
- XGBoost: For gradient boosting classification
- Selenium and Beautiful Soup: For web scraping
- Jupyter Notebooks: For interactive development and documentation

## Results
We developed and compared several classification models to identify properties with good investment potential. Here are the accuracy scores for each model:

- XGBoost: 0.688
- Support Vector Machine (SVM): 0.697 (best performing)
- Gaussian Naive Bayes: 0.651
- Decision Tree: 0.665
- Random Forest: 0.683
- K-Nearest Neighbors (KNN): 0.671
- Logistic Regression: 0.683

As explained in our [video presentation](#project-video-presentation), the Support Vector Machine (SVM) model performed best with an accuracy of 0.697, suggesting it's the most reliable for identifying potentially good investment properties.

## Conclusions
Our analysis provides valuable insights for individuals looking to invest in Portuguese real estate, particularly those seeking citizenship:

1. Model Performance: The SVM model, with its 0.697 accuracy, offers the most reliable predictions for identifying good investment properties. However, the relatively close performance of several models suggests that a ensemble approach might yield even better results in future iterations.

2. Investment Indicators: Through our feature analysis, we identified key factors that contribute to a property's investment potential, including location, size, and specific amenities.

3. Market Insights: Our data revealed interesting patterns in the Portuguese real estate market, such as price variations across different regions and property types.

4. Citizenship Considerations: While our model focuses on financial returns, we also considered factors that might be relevant for citizenship applications, such as property location in relation to cultural or historical sites.

5. Limitations and Future Work: We acknowledge that real estate investment is complex and influenced by many factors. Future work could incorporate more dynamic data, such as market trends and economic indicators, to further improve our predictions.

For a more detailed discussion of our findings and their implications, please refer to our [video presentation](#project-video-presentation).

## Installation and Usage
To use this project:

1. Clone this repository

2. Install required packages: requirements.txt

3. Navigate to the `notebooks/` directory to run the analysis step-by-step.

For a guided walkthrough of our analysis process, watch our [video presentation](#project-video-presentation).

## Contributing
We welcome contributions to improve the analysis or extend the project. If you're interested in contributing:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
5. Push to the branch (`git push origin feature/AmazingFeature`)
6. Open a Pull Request

Please feel free to open issues for discussion or to report bugs.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

We hope this project provides valuable insights for potential investors in the Portuguese real estate market. For any questions or further information, please don't hesitate to reach out or refer to our detailed [video presentation](#project-video-presentation).
