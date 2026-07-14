# History of the FIFA World Cups (1930–2022)
## Exploratory Data Analysis (EDA)
The objective of this project is to conduct an Exploratory Data Analysis (EDA) using historical data from the FIFA World Cups, from the first tournament held in 1930 through the 2022 tournament.
Exploratory Data Analysis is one of the most important stages of a data science project, as it allows us to understand the structure of the dataset, identify quality issues, detect patterns, find relationships between variables, and generate hypotheses for further analysis.
During this study, the following techniques will be applied:
- Data cleaning
- Handling missing values
- Handling inconsistencies
- Descriptive statistics
- Data visualization
- Data-driven storytelling
At the end, a historical overview of the evolution of the World Cup will be constructed using the data available in the dataset.

# Data Quality Assessment

Before performing any data cleaning procedure, it is essential to evaluate the quality of the dataset.

At this stage, we will investigate aspects that may compromise future analyses, such as:

- missing values;
- duplicate records;
- inconsistencies;
- incorrect data types;
- column standardization;
- value distribution.

The objective is to understand the current state of the dataset before making any modifications.

# Data Cleaning

Data cleaning is one of the most important stages of an Exploratory Data Analysis (EDA).

Even datasets obtained from reliable sources may contain issues such as duplicate records, inconsistent text formatting, incorrect data types, or non-standardized column names.

Cleaning the data ensures that subsequent analyses are accurate, reproducible, and easier to interpret.

In this section, we will:

- detect duplicate records;
- standardize column names;
- inspect data types;
- standardize textual values;
- identify potential inconsistencies.

# Descriptive Statistical Analysis

Descriptive statistics summarize the main characteristics of a dataset through numerical measures.

Rather than inspecting individual observations, descriptive statistics provide an overview of the data distribution, central tendency, variability, and spread.

In this section, we will explore the numerical variables available in the FIFA World Cup dataset by computing statistical measures such as:

- mean;
- median;
- mode;
- variance;
- standard deviation;
- coefficient of variation;
- minimum and maximum values;
- quartiles;
- percentiles;
- range.

These measures provide the foundation for understanding the behavior of the dataset before moving on to visual analysis.

# Univariate Analysis

After computing the descriptive statistics, the next step is to investigate the distribution of each numerical variable individually.

Univariate analysis helps answer questions such as:

- Is the data normally distributed?
- Are there any outliers?
- Is the distribution symmetric or skewed?
- Where are most observations concentrated?
- How much variability exists?

To answer these questions, we will combine numerical summaries with graphical representations.

## Summary of the Univariate Analysis

The univariate analysis provides a detailed understanding of each numerical variable independently.

By combining descriptive statistics with histograms and boxplots, we can identify:

- the overall shape of each distribution;
- the presence of skewness;
- the spread of the data;
- potential outliers;
- variables with low or high variability.

It is important to emphasize that outliers in historical datasets are not necessarily data quality issues. Instead, they often represent unique historical events that should be preserved rather than removed.

# Bivariate Analysis

While univariate analysis focuses on individual variables, bivariate analysis investigates the relationship between pairs of variables.

Understanding these relationships helps identify trends, correlations, and historical patterns that cannot be observed by analyzing variables independently.

Throughout this section, we will answer questions such as:

- Has the tournament attendance increased over time?
- Did the number of participating teams influence the number of matches?
- Is there a relationship between attendance and tournament size?
- How has the FIFA World Cup evolved throughout its history?

The objective is not only to visualize relationships, but also to interpret the historical evolution of the tournament through data.

## Summary of the Bivariate Analysis

The bivariate analysis revealed how the main numerical variables interact throughout the history of the FIFA World Cup.

The combination of correlation analysis, line charts, and scatter plots makes it possible to identify historical trends and relationships that are not evident when variables are analyzed individually.

These findings establish the foundation for the next stage of the analysis, where categorical variables such as champion countries, host nations, and winning continents will be explored to uncover the historical narrative of the tournament.

# Categorical Analysis

Categorical variables describe qualitative characteristics of the FIFA World Cup rather than numerical measurements.

Unlike numerical variables, categorical variables are analyzed through frequencies, proportions, and comparisons between categories.

This section aims to answer questions such as:

- Which country has won the most World Cup titles?
- Which nations have hosted the tournament most frequently?
- Which continent has dominated different periods?
- Which head coaches have won multiple titles?
- Which captains lifted the trophy?

The objective is to explore the historical evolution of the tournament through its categorical attributes.

## Summary of the Categorical Analysis

The categorical analysis provides a historical perspective on the FIFA World Cup by examining the frequency of key qualitative variables.

Unlike numerical analysis, which focuses on measurements and distributions, categorical analysis highlights the historical dominance of countries, continents, coaches, and captains.

These results reveal how success has been distributed throughout the history of the tournament and establish the foundation for deeper historical comparisons in the following sections.

# Key Findings

Throughout this exploratory data analysis, several important historical patterns emerged from the FIFA World Cup dataset.

The following findings summarize the most relevant insights obtained from the analyses performed in this notebook.

---

## Tournament Growth

The FIFA World Cup has experienced substantial growth since its first edition in 1930.

Both the number of participating teams and the number of matches increased over time, reflecting the global expansion of the tournament.

This growth was also accompanied by a significant increase in overall attendance.

---

## Attendance Trends

Tournament attendance generally increased throughout the decades.

Although some editions experienced temporary declines due to historical circumstances or organizational factors, the long-term trend demonstrates the continuous growth of football's global popularity.

---

## Expansion of the Competition

The evolution of participating teams clearly shows that FIFA expanded the tournament in multiple stages.

Each expansion resulted in a larger number of matches, confirming the strong relationship between tournament size and competition format.

---

## Dominant Nations

World Cup titles have historically been concentrated among a relatively small number of national teams.

Although many countries have participated in the tournament, only a limited group has consistently reached the highest level of success.

This finding highlights the long-term competitive dominance of traditional football nations.

---

## Continental Dominance

The history of the FIFA World Cup has largely been shared between Europe and South America.

These two continents have consistently dominated the competition, while other continents have yet to secure a World Cup title.

The balance of power between European and South American teams has shifted throughout different historical periods.

---

## Competitive Finals

Most World Cup finals have been decided by small goal margins.

This suggests that championship matches are generally balanced, regardless of the relative strength of the finalists.

Several finals required extra time or penalty shootouts, reinforcing the highly competitive nature of the tournament.

---

## Historical Consistency

Some countries have reached the World Cup final repeatedly, even when they did not always become champions.

Final appearances provide a broader measure of long-term competitiveness than titles alone.

---

## Evolution of Individual Awards

The dataset also illustrates the historical evolution of individual awards such as:

- Golden Ball;
- Golden Boot;
- Golden Glove;
- Best Young Player.

The presence of missing values in these variables reflects the historical introduction of these awards rather than data quality issues.

---

## Historical Evolution of Tournament Identity

The official match balls and mascots demonstrate how the FIFA World Cup has evolved beyond a sporting competition into a global cultural event.

Each edition introduced visual elements that became part of football history.

---

## Data Quality Assessment

The dataset presented a high level of overall quality.

The exploratory analysis identified few structural issues, and most missing values were historically justified rather than resulting from data collection errors.

This provides confidence that the analyses presented throughout this notebook are reliable.