# BasketPuzzle Project

## Problem Identification and Analysis
In modern marketing, analyzing the patterns of products that consumers place in their shopping carts is a crucial task. To achieve this, it is essential to understand consumer consumption patterns and identify which products are frequently purchased together.  
Therefore, the goal of this project is to analyze consumer shopping cart patterns to determine which product combinations lead to successful transactions, ultimately establishing an effective marketing strategy.  
Furthermore, to differentiate our project from similar existing studies, we plan to segment consumers into retail and wholesale categories based on their purchase history and implement an algorithm that recommends customized package products tailored to each group.  
This approach is expected to provide more valuable insights for real-world business strategies.

## Project Objectives
The objective of BasketPuzzle is to analyze consumer purchase histories to discover patterns among products and represent these insights as quantified data. We aim to establish an API pipeline and visualize the analysis results as charts on the web for easy user access. Through this process, sellers can develop more effective marketing strategies and improve customer satisfaction, while consumers will enjoy a better shopping experience with personalized recommendations.

## Key Features
1. Visualize shopping cart data through charts
2. Provide a shopping trend list chart
3. Product search function
4. Quantify purchase ratios for segmented customers (retail, wholesale)
5. Analyze and recommend related products based on purchase history

## Development Tools and Languages
The shopping data analysis will be conducted in a Python-based Jupyter Notebook environment. Python libraries such as Pandas, NumPy, and Matplotlib will be used for data analysis, preprocessing, and computation.  
Additionally, we will use Apriori or FP-Growth for association rule learning, as well as the K-Means algorithm for customer segmentation.  
Finally, the back-end API will be built using Flask, and the analysis results will be visualized on the web using JavaScript, React, and Chart.js.