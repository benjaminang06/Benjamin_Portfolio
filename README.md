# Benjamin's Programming Portfolio

Hey there! I’m Benjamin—a data scientist with an Applied Mathematics background who loves solving business problems. I like to think of this portfolio as a programming diary: each project snapshot captures what sparked my curiosity at that moment. I hope you enjoy exploring these experiments and getting to know me.

### [Project 1: The First Step Towards Data-Driven Esports: A Match Results Tracker](https://github.com/benjaminang06/mlwebapp/blob/clean-code/README.md)
**Description:** Developed a full-stack web app for storing and visualizing scrim and tournament match results, giving teams access to historical logs and an interactive performance dashboard.

**Key Results:**  
- Centralized over 200 match records, eliminating dozens of Excel files  
- Reduced pre-game analysis time by 40% through automated summaries  

<table>
  <tr>
    <td align="center">
      <strong>Landing Page</strong><br/>
      <img src="https://github.com/user-attachments/assets/3493f6e7-e962-4bbe-8e5d-86020c0f07d2" alt="Landing Page" width="400"/>
    </td>
    <td align="center">
      <strong>Match History</strong><br/>
      <img src="https://github.com/user-attachments/assets/59d790c6-d959-48d5-a799-1f2c35990bb3" alt="Match History" width="400"/>
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Match Upload Page 1</strong><br/>
      <img src="https://github.com/user-attachments/assets/ebd8342a-63ae-4a93-948e-da95da6b55f7" alt="Match Upload Page 1" width="400"/>
    </td>
    <td align="center">
      <strong>Match Upload Page 2</strong><br/>
      <img src="https://github.com/user-attachments/assets/1c1ed3c3-548d-403c-aef6-a09f6a16afc5" alt="Match Upload Page 2" width="400"/>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <strong>Team Statistics</strong><br/>
      <img src="https://github.com/user-attachments/assets/bb14ddb3-9ae0-443d-aaf7-bad14131c586" alt="Team Statistics" width="800"/>
    </td>
  </tr>
</table>


### [Project 2: An Integrated Approach to Next Best Offer Modeling for Financial Products: A Multi-Model Architecture](https://github.com/benjaminang06/Next_Best_Offer/blob/main/README.md) 

**Description:**  
Develop an ensemble recommendation system that suggests the next best financial product based on customer characteristics and transaction history.

**Approach:**  
- **Collaborative Filtering:** Leverage user–item interaction data to surface products favored by similar customers.  
- **Content-Based Filtering:** Match customer profiles to product attributes (e.g., interest rates, fees, credit limits).  
- **Propensity Models:** Train XGBoost classifiers to predict the likelihood of each customer adopting a given product.  
- **Ensemble Combination:** Combine outputs by tuning the weights assigned to each product from each model to maximize overall hit rate.

**Key Steps:**  
1. Data ingestion and feature engineering on customer demographics, account balances, transaction patterns.  
2. Construction of separate recommendation pipelines for each model family.  
3. Weight optimization: tune model-specific product weights to maximize hit rate on a validation set.  
4. Ensemble ranking and blending of weighted scores.  
5. Validation using AUC, precision@K, and lift metrics.

**Results:**

![image](https://github.com/user-attachments/assets/789560c4-40ac-4ada-b0aa-105eca42bfcc)
### [Project 3: Insights from UAAP Basketball Data Through Topology](https://github.com/benjaminang06/Topological-Data-Analysis)

**Description:** Leveraged Topological Data Analysis (TDA) using Giotto TDA to uncover unique player subgroups in UAAP basketball beyond traditional positions.

**Key Results:** Identified new player roles and strategies, offering novel insights for team management and tactical planning. Demonstrated the practical applications of TDA in sports analytics.

![Mapper Algorithm visualization of UAAP dataset, highlighting the proportion of centers in each node](https://github.com/benjaminang06/Topological-Data-Analysis/assets/104061155/8554bac4-a75c-4f5f-a0ef-3f3129e17000)

### [Project 4: Linear Regression Visualized: Building Intuition Behind Ordinary Least Squares](<REPO_LINK>)

**Description:**  
Throughout my college journey, I relied on Grant Sanderson’s (3Blue1Brown) Manim videos to master concepts from linear algebra to neural networks and cryptography. For my Ateneo statistics teaching demo, I built on that inspiration—using Manim to animate Ordinary Least Squares regression and bring to life how the best-fit line emerges by minimizing the sum of squared residuals, while forging a clear link between the algebraic formulas and geometric intuition.

**Key Highlights:**  
- Step-by-step animation of data points, candidate lines, and error bars  
- Visual demonstration of how the SSE (sum of squared errors) changes as the line moves  
- Interactive breakdown of slope and intercept adjustments  


https://github.com/user-attachments/assets/856ca5fc-6bc7-41eb-bd60-63dfd2004dc3



### [Project 5: Time Series Analysis and Forecasting using ARMA Models: A Case Study of the Philippine Stock Exchange](https://github.com/benjaminang06/TimeSeries)

**Description:** Developed an ARMA model to predict future trends in the Philippine Stock Exchange Composite Index using historical data from 1987 to 2022.

**Key Results:** Identified the AR(1) model as the best fit with a MAPE of 6.62%, providing highly accurate forecasts. This model helps stakeholders make informed investment decisions by anticipating market movements.

![PSEI 2 and 3 Year Forecast](https://github.com/benjaminang06/TimeSeries/blob/main/IMG_1056.jpeg)



### [Project 6: Fake News Detection in Filipino News Sources](https://github.com/benjaminang06/Fake-News-Classifier)

**Description:** Developed a binary classification model to differentiate between fake and real news articles from Filipino sources using Dense, LSTM, and Convolutional Neural Networks (CNNs).

**Key Results:** Achieved over 90% accuracy in detecting fake news, demonstrating the effectiveness of deep learning in content verification.

![Summary of Accuracy Metrics for the classification models](https://github.com/benjaminang06/Fake-News-Classifier/blob/main/Summary%20of%20Accuracy%20Metrics.png)

### [Project 7: Agent-Based Modeling of Economic Behavior in the Car Industry](https://github.com/benjaminang06/Modeling-Economic-Behavior)

**Description:** Utilized the AgentPy library to simulate consumer purchasing behavior in the car market, integrating normal distributions for agent characteristics.

**Key Results:** Created a realistic simulation of the car market, with visualizations made using matplotlib and seaborn to analyze consumer behavior and market dynamics.

![Simulation results showing market behavior and consumer interactions](https://github.com/benjaminang06/Modeling-Economic-Behavior/blob/main/Simulation%20Results.png)

### [Project 8: 8-Puzzle Algorithm Solver](https://github.com/benjaminang06/8-Puzzle)

**Description:** Implemented various search algorithms to find the solution for the 8-puzzle problem, demonstrating algorithm efficiency and optimization.

**Key Results:** Developed functions that efficiently navigate from any given initial state to the goal state, showcasing different search strategy strengths.

![Solution path for an 8-puzzle problem](https://github.com/benjaminang06/8-Puzzle/blob/main/8-Puzzle.png)

### [Project 9: 3D Rotating Shuttle Simulation](https://github.com/benjaminang06/Rotating-Shuttle)

**Description:** Applied linear transformations to generate a 3-dimensional rotating shuttle, exploring computer graphics and transformation matrices.

**Key Results:** Created a visually appealing 3D model of a shuttle, demonstrating the application of linear algebra in computer graphics.

![3D rendering of a rotating shuttle](https://github.com/benjaminang06/Rotating-Shuttle/blob/main/shuttle.gif)

Feel free to explore each project for more detailed information and insights. Thank you for visiting my coding portfolio!
