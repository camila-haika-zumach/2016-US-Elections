# 2016 US Election Analysis

## Brief Description

The 2016 US Election Analysis is a data science project that dives into the 2016 United States presidential election. The project uses a dataset from Kaggle, which contains a wealth of information about the election, including primary results, county facts, and demographic details. The analysis aims to provide insights into the election outcome, voting patterns, and the impact of various factors on the results.

## Installation Instructions

To run the analysis, you will need Python and several libraries, such as Pandas, Matplotlib, and Seaborn. You can install these libraries using the following command:

```bash
pip install pandas matplotlib seaborn
```

You can also clone the project repository from GitHub and run the Jupyter Notebook or Python script provided.

## Data Sources

The project uses three main datasets:

1. **County Facts Dataset (df_county_facts):** This dataset contains factual information about various counties in the United States. It includes demographic, economic, and educational statistics, allowing for an in-depth exploration of county characteristics.

2. **County Facts Dictionary Dataset (df_dictionary):** This dataset serves as a dictionary or key for understanding the columns in the County Facts dataset. It provides descriptions and labels for each variable, making the data more interpretable.

3. **Primary Results Dataset (df):** The Primary Results dataset contains data related to the primary elections held during the 2016 U.S. presidential election. It includes primary election results at the county level, such as votes cast for different candidates and parties.

## Code Structure

The project's code is organized as follows:

- **Data Loading:** The initial section loads and prepares the datasets for analysis.
- **Outlier Analysis:** This part focuses on identifying and analyzing outliers, especially in counties with significant vote counts.
- **Qualitative Analysis:** The analysis delves into qualitative aspects, comparing counties in California and Texas, representing Hillary Clinton and Donald Trump's respective strongholds.
- **Results and Visualization:** Findings and insights are presented through various visualizations, charts, and narrative.
- **Future Work:** This section suggests areas for future research or enhancements to the analysis.

## Results and Evaluation

The analysis reveals several key findings. Despite Hillary Clinton receiving more votes, she did not win the election. The results highlight that counties with higher education levels, greater income, and fewer children tended to vote for Clinton. However, the electoral system favored Trump due to the distribution of votes across states.

### Different Strategies for Trump and Hillary

One significant aspect that emerged from the analysis is the distinct campaign strategies employed by Hillary Clinton and Donald Trump. Hillary's campaign focused on mobilizing and appealing to a broader population, emphasizing inclusivity and diversity. In contrast, Trump's campaign targeted specific demographics, particularly college-educated individuals and those in less urbanized areas. This strategy aimed to consolidate support among these groups and secure electoral votes strategically.

## Future Work

Future work on this project could include:

- Analyzing the impact of campaign strategies on election outcomes.
- Exploring the influence of social media and digital campaigns.
- Investigating voter turnout and voter registration patterns.
- Incorporating sentiment analysis of public sentiment during the election period.

## Acknowledgments/References

This project acknowledges Kaggle as the source of the dataset used for analysis.

## License

Copyright (c) 2023 Camila Haika Zumach

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS," WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
