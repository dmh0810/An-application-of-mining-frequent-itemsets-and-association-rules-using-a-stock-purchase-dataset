# Market Basket Analysis: an application of mining frequent itemsets and association rules using a stock purchase dataset
This contains the code for my seminar paper for the elective module "Empirische Kundendatenanalyse: Eine praxisorientierte Einführung" in Winter Term 2019/2020 of Department of Marketing, Faculty of Business and Economics, Goethe-University Frankfurt am Main


*Abstract:*

*Market Basket Analysis is a widely used approach to identify sets of products that are often purchased together. One method of Market Basket Analysis involves mining frequent itemsets and association rules between items in a large database. Knowledge gained from this analysis can be essential for diverse marketing activities such as product placements or promotional campaigns. This paper demonstrates the implementation of the APRIORI algorithm on the stock purchase data in 2019 of ING-DiBa Bank to discover sets of shares that were often bought together and the correlation between these itemsets.
Keywords: market basket analysis, frequent itemsets, association rules, Apriori algorithm, stock purchase*



**Introduction:**

Mining association rules is a popular approach in detecting relationships among items in a set of transactions (Hahsler, Grün, and Hornik 2005). Identifying frequent itemsets, together with mining association rules, contributes to the widely implemented Market Basket Analysis. The knowledge of which sets of products customers normally buy together is an essential part in determining “next best offer”, which can significantly invigorate sales outcomes or marketing campaigns and help discover regularities in shopping behavior of customers.
This paper illustrates the application of Market Basket Analysis, using a real dataset of stock purchase in 2019 provided by the ING-DiBa, to identify which shares customers often jointly purchased. To mine frequent sets of stocks and association rules in the data, I adopt the algorithm APRIORI and use R packages arules and arulesViz. My main objective in this paper is to address the following questions: 1) Which combinations of stocks did ING-DiBa customers usually buy? and 2) Which rules can describe the association between these frequent sets of stocks? Hence, the paper focuses more on the aspect of a methodological implementation and less on providing a theoretical conceptualization of Market Basket Analysis. Furthermore, my paper has one major implication for the practice of conducting a market basket analysis by presenting methods to optimize the outcomes of the APRIORI algorithm.
The rest of the paper is organized as follows: the next session provides a brief theoretical background on the method. In the third session, I present in detail my methodological approach along with interpretations of results drawn from the dataset. Subsequently, I apply the concept of redundant rules, closed rules and the method of sampling to optimize the mining process. Finally, I conclude with a summary of most notable findings, certain limitations that should be accounted for in my paper and implications for future research.
