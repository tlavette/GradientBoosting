# Decision Trees and Ensemble Assignment CMPE-255


**1. Gradient Boosting** <br>
**Colab:** https://colab.research.google.com/drive/1XMbF2VoxarXtyzt4dFmL9CR6EwPgNIS0?usp=sharing <br> <br>
<body>
The model begins by making a very basic prediction, such as the average price of all houses.
Learn from mistakes: It looks at where the initial guess was wrong and trains a small model (a "weak learner") to correct those errors.
Repeat and improve: It adds more small models, each one focusing on fixing the errors of the combined previous models. Over time, it gets better and better at making accurate predictions.<br>
</body>
<br>

**2. Random Forest** <br>
**Colab:** https://colab.research.google.com/drive/1GH_a2vehUXLltdLFjtoR-12R7VRDP74W?usp=sharing <br>
<body> <br>
A Random Forest is a popular ensemble learning method used for both classification and regression tasks in data science. It is built on the principle of combining multiple decision trees (hence the "forest") to improve the model's accuracy and prevent overfitting.

Key Benefits: <br>
*Handles high-dimensional data and complex relationships well.* <br>
*Resistant to overfitting due to ensemble averaging.* <br>
*Can manage missing values and outliers effectively.*  
</body>

**3. AdaBoost** <br>
**Colab** https://colab.research.google.com/drive/1V7jsEc_kT9SruEolj31jLn84Pr-G4Lne?usp=sharing <br>
<body>
 AdaBoost (Adaptive Boosting) is an ensemble learning method designed to improve the performance of weak classifiers by combining them into a strong classifier. It works by sequentially training a series of models (often decision trees with a maximum depth of 1, also known as "stumps") and assigning weights to their predictions based on their accuracy

*Advantages of AdaBoost* <br>
Focuses on difficult examples, which improves accuracy. <br>
Works well with imbalanced datasets. <br>
Robust to overfitting if n_estimators and learning_rate are tuned appropriately. <br>

*Disadvantages of AdaBoost* <br>
Sensitive to noisy data and outliers since they are given higher weights. <br>
Computationally expensive for large datasets due to sequential training.

</body>

**4. Decision Tree** <br>
**Colab** https://colab.research.google.com/drive/1s1yoTA8POE5gxddi27dO_BzgpGfr1MB6?usp=sharing <br>
<body>
A Decision Tree is a simple yet powerful machine learning algorithm used for both classification and regression tasks. It works like a flowchart.
*Nodes* represent decisions or conditions based on input features. <br>
*Branches* represent the outcomes of those decisions. <br>
*Leaves* represent the final predictions or outputs.
<br>
</body>
<br>
<br>

**Youtube:**  https://youtu.be/lfI-OcWlhrw

