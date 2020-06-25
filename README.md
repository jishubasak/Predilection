# Predilection
In The News: Predicting Winning Political Candidates From News Tone using GDELT dataset

<p align="center"><img src="https://github.com/jishubasak/Predilection/blob/master/catalog/poster.png"></p>

## Introduction
Predicting the future seems to be one of mankind's deepest fascinations, and why ever not? The ability to foresee future events presents a luxury of practical benefits. For one, it enables businesses to forecast sales and predict the next occurrence of equipment failure. It also allows investors to make an informed decision on which stocks to buy or which parcels of land would be most profitable for the new year. Moreover, it helps medical professionals have an idea of how long a patient would stay in the hospital based on her health records. Getting ahead gives one the necessary time to prepare or anticipate an emerging situation, and thus take prompt action to either mitigate the risk or take advantage of the opportunity.

Although the science of forecasting finds applications in many different fields, it is not a complete stranger in the spheres of politics. The United States Presidential Elections is perhaps one of the most important political events, anticipated not only by Americans but as well as the rest of the world. This phenomenal transfer of power from one leader to another could either maintain the status quo or entirely redefine the world order. Thus, there is a strong, concerted effort among researchers to get the pulse of the voters either through social weather surveys, online polls, and other predictive methods.

Marketing intelligence company IDC reports that the entire global datasphere will grow to about 175 zettabytes by 2025. With the emergence of disruptive technologies like Big Data and AI, our ability to predict future events has become more accurate than ever before. In this project, the authors explore the predictive power of Big Data in predicting election results.

## Problem Statement

With more than 321 million monthly active users in 2018, Twitter has become one of the most influential modes of digital communication. It doles out as an online platform for people to "tweet" their thoughts, ideas, and opinions about almost all topics imaginable. These, of course, include their views about politics, and by extension, their feelings towards certain political figures, however positive or negative.

Taking advantage of this trend, many groups of researchers and programmers have mined data from Twitter, among other social media channels, and use this information to gauge people's political sentiments and therefore predict election results. In fact, a relevant paper was published by BBN Technologies, an American research and development company, showing how a candidate's popularity on Twitter can be leveraged to predict the election outcome. The authors of the said publication have collected approximately 13 billion global Twitter messages and demonstrated how they can be used for predicting the results of the Venezuelan, Paraguayan and Ecuadorian Presidential election of 2013.

While online literatures abound on using Twitter analytics for "nowcasting" the results of the polls, there are very few mentions of utilizing the Global Database of Events, Language, and Tone (GDELT) when making such a political forecast, if at all. GDELT is an immensely rich pool of data, containing some trillions of rows of various types of information from different parts of the world. A more detailed explanation of GDELT is provided at the latter part of this notebook.

In this project, the authors intend to explore the potential predictive power of online news coverage with respect to the winnability of a certain political candidate. One of the motivations of this project is to devise an alternative measure to social weather surveys in gauging the sentiment of voters. Since news articles, as they should be, are technically less biased as compared to tweets or posts on social media, it may be inferred that the model would give a more reliable output.

## Results
There is now more data that ever before because of our increasingly interconnected world. The advent of disruptive technologies such as the Internet-of-Things (IoT) and the rise of social media platforms like Twitter and Facebook have led to a massive explosion of data, making it an almost infinite resource. Considered as the new oil, this extremely rich pool of information (more popularly known as Big Data) are now being mined, wrangled, and processed to find answers that can address a suite of business and societal challenges.

Predicting election outcomes is one problem that can be solved with data. In this report, we have demonstrated how data from news coverage can accurately predict which candidate will win the poll. However, it has to be noted that the model is not country agnostic. Meaning to say, what works for the US might not be as effective in the Philippines. This may be attributed to some factors such as difference in political dynamics, the number of media outlets present in the country, among other things.

For future work, the same approach could be experimented on different political posts such as vice president, senator, or congressman. Instead of conducting the predictive analysis on a national level, a state-wide analysis may as well be explored.

##### Jupyter Notebook Explanation

Each time series for a candidate was saved as a pickle file from the data wrangling notebook. These files are loaded and saved as separate variables.

The files relevant to this study are the daily time series for the number of mentions and articles per candidate and the number of mentions and articles per canidate weighted by their tone.
This can be accessed through the Wrangler Notebook.

You can access the methodology and rest of the work in the Technical Report Jupyter Notebook
