# MarketInsights2023
Unravelling Financial Dynamics through Statistical Analysis and Prediction Modelling. Utilized Yahoo Finance library for reliable data acquisition and preprocessing, empowering investors with actionable insights for strategic decision-making.

# Project  Overview

This report presents a comprehensive inquiry into the financial performance of four prominent companies  from 4 different industries each throughout the year 2023. Employing rigorous statistical techniques and robust data analysis, this study endeavors to address pivotal questions crucial for informed investment decisions. Through meticulous examination, I seek to unravel the intricacies of stock market dynamics, shedding light on key metrics such as stock price evolution, daily return averages, moving averages, inter-stock correlations, and risk assessment. 

Furthermore, I aim to extend the boundaries of knowledge by exploring advanced predictive methodologies, particularly focusing on the application of Long Short-Term Memory 
(LSTM) models, FeedForward Neural Network and ARIMA model to forecast future stock behaviors. As a practical demonstration, we present a predictive model tailored to anticipate the closing price of multiple stock. 

This analysis is structured to provide a comprehensive overview of our methodology, findings, and implications. It serves as a scholarly contribution to finance, offering insights that can inform academic discourse and guide practical investment strategies. Through our rigorous analysis, we contribute to a deeper understanding of financial markets and empower stakeholders with actionable insights. 

# Objectives

Through rigorous statistical analysis and data-driven methodologies, this study seeks to address the following key inquiries regarding the financial performance of four finance companies over the entirety of 2023: 
1. What are the patterns and trends in the change of stock prices over time for the selected companies?
2. What is the average daily return of the stocks, and how does it vary across the companies studied?
3. How do moving averages reflect and elucidate the performance trends of the various stocks?
4. What is the correlation between different stocks, and how does it impact diversification strategies?
5. How can the risk associated with investing in a particular stock be quantified and assessed?
6. Can future stock behavior be predicted, and to what extent can prediction models assist in forecasting the closing price of a stock?

These research questions serve as the guiding framework for our comprehensive analysis, aiming to provide nuanced insights into the financial dynamics of the selected companies and inform investment decision-making processes. 

# Dataset Description 

The dataset utilized in this study comprises one year of stock price data for 16 prominent financial firms from 5 different industries, sourced directly from Yahoo Finance through Yahoo Finance library. The dataset has been meticulously collected and cleaned, ensuring its reliability and accuracy for analysis purposes. 

Data Source: Yahoo Finance library
Timeframe: One year
Companies Included: 
A] Finance Indurstry: Goldman Sachs, Bank of America, Wells Fargo and JP Morgan Chase.
B] Entertainment Industry: Netflix, Disney, Paramount and Comcast. 
C] Technology and Energy Industry: Apple, Microsoft, Exxon Mobil Corp and NextEra Energy.

# Repository Structure

The project is structured into three distinct parts. As previously noted, our analysis encompasses four diverse industries: Entertainment, Finance, Technology, and Energy. Specifically, I conducted separate analyses for the Entertainment and Finance sectors using Julia and Python, respectively. Subsequently, I delved into the analysis of Technology and Energy sector stocks using R programming.

1. Folder "Entertainment Industry"
   + Prediction Notebook.html - Contains the implementation of Prediction models using Python. File type is html, which can be opened directly using a browser.
   + Predictions Notebook.ipynb - Containes the implementation of Prediction models using Python. File type Python Jupyter Notebook.
   + Project Analysis File.html - Contains the implementation of Data Analysis using Julia. File type is html, which can be opened directly using a browser.
   + Project Analysis File.ipynb - Containes the implementation of Data Analysis using Julia. File type Python Jupyter Notebook.
   + Project PPT Presentation.pdf - Contains PPT Presentation on the project.
   + Project Resport.pdf - Contains detailed report including all insights on the project.

3. Folder "Finance Industry"
   + Final Project Code.html - Contains the implementation of Data Analysis using Python. File type is html, which can be opened directly using a browser.
   + Final Project Code.ipynb - Containes the implementation of Data Analysis using Python. File type Python Jupyter Notebook.
   + Final Project Presentation.pdf - Contains PPT Presentation on the project.
   + Final Project Report.pdf - Contains detailed report including all insights on the project.

4. Folder "Technology Vs Energy Industry"
   + Project Source Code.Rmd - Contains the implementation of Data Analysis including all insights using R Programming. File type is R markdown. Need R studio to open and run this file.
   + Project Source Code.html - Contains the implementation of Data Analysis including all insights using R Programming. File type is html, which can be opened directly using a browser.

# Tools and Technologies

This project leverages a suite of sophisticated tools and technologies designed to handle complex data analysis and predictive modeling across multiple programming languages. Here is a breakdown of the primary tools and technologies used:

### Programming Languages

  + **Python:** Utilized for data preprocessing, analysis, and implementation of predictive models. Python's extensive libraries and frameworks support a wide range of statistical and machine learning techniques.
  + **Julia:** Employed for high-performance numerical analysis and computational science tasks. Julia's capabilities are particularly advantageous for handling large-scale and complex datasets efficiently.
  + **R:** Used for data analysis and visualization in the Technology and Energy sectors. R's rich ecosystem of packages makes it ideal for statistical modeling and inference.

### Libraries and Frameworks

  + **Yahoo Finance Library:** The primary source for acquiring reliable and up-to-date financial data. This library allows for easy access to historical stock price data, which is critical for our analysis.
  + **Pandas and NumPy:** Essential Python libraries for data manipulation and numerical calculations. These tools are used extensively for data cleaning, transformation, and preparation for modeling.
  + **Scikit-learn:** A Python library for implementing machine learning algorithms. It is used for building regression models and conducting various other statistical analyses.
  + **TensorFlow and Keras:** Utilized for designing and training advanced neural network models, including Long Short-Term Memory (LSTM) networks, which are pivotal in predicting stock price movements.
  + **ARIMA (AutoRegressive Integrated Moving Average):** Implemented in Python, this model is used for time-series forecasting to predict future stock prices based on past trends.
  + **Matplotlib and Seaborn:** Python libraries for data visualization. These tools are instrumental in creating insightful, interactive charts and graphs that elucidate the data’s underlying patterns and trends.
  + **Jupyter Notebook:** Provides an interactive environment for live-code execution, visualization, and narrative text. It is used for documenting the workflow and analysis for reproducibility and collaboration.
  + **R Markdown:** Used within R Studio for creating dynamic analysis documents that combine code execution, formatted text, and visualizations in a single document.

# Getting Started
To help you get up and running with this project, follow the instructions below. This guide will cover the required software, environment setup, and instructions for running the analysis.

### Prerequisites
Before cloning the repository, ensure you have the following software installed:

1. Python (version 3.8 or later) - for data analysis, predictive modeling, and visualization.
2. Julia (version 1.5 or later) - for high-performance numerical analysis.
3. R (version 4.0 or later) - for statistical analysis and visualization.
4. Anaconda - for managing Python packages and environments, including Jupyter Notebook.

### Running the Analysis
#### Python Analysis
  + **Entertainment and Finance:** Navigate to the relevant subfolder and open the .ipynb or .html files with Jupyter Notebook or a web browser, respectively.
  + Run the code cells sequentially for data analysis and prediction.

#### Julia Analysis
  + **Entertainment Industry:** Open the .ipynb or .html files related to Julia analysis, and execute the analysis by following the notebook's structure.

#### R Analysis
  + **Technology and Energy:** Open the .Rmd file in RStudio to run the analysis directly, or use the .html files to explore the results interactively.

### Exploring the Project Outputs
  + **Presentations:** Review the .pdf files available in each folder for detailed presentations on the project findings.
  + **Reports:** Check out the comprehensive reports in .pdf format that encapsulate key insights, analyses, and findings.

### Contribution Guidelines
If you'd like to contribute to this project, feel free to open an issue or create a pull request with your proposed changes.
