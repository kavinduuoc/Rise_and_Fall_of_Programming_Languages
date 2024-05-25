Rise and Fall of Programming Languages

Description
This project analyzes the trends in the popularity of various programming languages and technologies over time using data from Stack Overflow. By measuring the number of questions about each technology, we aim to get an approximate sense of how many people are using these technologies and which ones are growing or shrinking in popularity.

Data Source
The data used in this project comes from the Stack Exchange Data Explorer, which includes more than 16 million questions from Stack Overflow. Each question is tagged with relevant topics or technologies.

Objective
The main goals of this project are:

1.To analyze the relative popularity of programming languages such as R, Python, Java, and JavaScript over time.
2.To visualize trends and changes in the popularity of these languages.
3.To determine which tags are growing in popularity and which are declining.

Project Workflow

1.Data Collection: Obtain the dataset with one observation for each tag in each year, including the number of questions asked in that tag in that year and the total number of questions asked in that year.

2.Data Preparation: Calculate the fraction of questions that year for each tag to get a sense of their relative popularity.

3.Analysis:
Examine the trends for R to determine if it's growing or shrinking.
Visualize the changes over time using line plots.
Compare the trends for R, dplyr, and ggplot2.
Identify the most asked-about tags overall using group_by and summarize.
Analyze the trends for major programming languages such as JavaScript, Java, and C#.
Explore trends for mobile operating systems like Android, iOS, and Windows Phone.

Key Findings

The fraction of questions about R has been increasing over time, indicating growing popularity.
Both dplyr and ggplot2 tags are also increasing in popularity.
Python has seen significant growth, while languages like C# are receiving fewer questions over time.

How to Run the Code

To reproduce this analysis, follow these steps:

Clone this repository: git clone https://github.com/kavinduuoc/Rise_and_Fall_of_Programming_Languages.git
Navigate to the project directory: cd Rise_and_Fall_of_Programming_Languages
Open the R script in your R environment (e.g., RStudio).
Run the script to generate the plots and analyses.

Conclusion and Future Work

This analysis provides insights into the changing landscape of programming languages and technologies. Future work could involve:

Extending the analysis to include more tags and technologies.
Using more sophisticated statistical models to predict future trends.
Exploring the impact of major technological events on the popularity of certain tags.

Acknowledgements

Thanks to Stack Exchange Data Explorer for providing the data and DataCamp for guiding the initial project setup.

Contact Information
For any questions or feedback, feel free to contact me kavindugayanthauoc@gmail.com
