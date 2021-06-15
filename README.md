# Mumsnet_Forumdata

Contents:

Report.pdf:
Text explaining the problem and the analytical approaches.

Raw_data:
Contains the dataset provided by Mumsnet (mumsnet_test.csv)

ForumData.ipynb:
Code used for the analysis. The code performs data visualisation and implements a supervised machine model. See the Report for further details.

Data_visualisation.
Contents:
- Number of messages across forums.pdf:
Bar chart of the number of messages posted to each forum
- Time of recommendations.pdf:
Plot containing information on the time course of the messages on various forums. Each message is represented as a datapoint across a 24 hour day.
- Titles_WordCloud.png:
Word cloud using the title words 
- Frequent_collocations:
Folder containing the most common 2-word combinations on the different forums.
- Recommended_prodcuts.png:
Pie chart depicting the distribution of product categories across the recommendations

Preprocessed_data:
Contains the csv file where the product category (e.g. 'Baby', 'DIY', 'Kitchen & Home') is added as a column.
This information was previously extracted from the URLs through web scraping.
