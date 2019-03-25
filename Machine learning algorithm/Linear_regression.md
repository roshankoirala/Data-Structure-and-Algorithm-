# What is linear regression?

Ans: You are given a set of data or relation between an dependent variable and some independent variable. Your job is to find a line or plane or hyperplane depending on the number of dimension (or the number of indendent variables). Finding such a linear relation is called linear regression. We usually use the method of least square to find such a line (or plane/hyperplane)

# What is least square fit?

Ans: Suppose you have a set of data $ (X_i, y_i) $. When you have purposed line of best fit as $ y = A + BX $ then for a particular $ X_i $ the line predicts its $y$ value to be $y_i^{pred} = A + B X_i$. The difference $ y_i - y_i^{pred} = y_i - A - B X_i $ is called the resudue. Our aim is to find a line such that the sum of square of residue of all the points of the training set is as least as possible. That is we want to minimize the function, called cost function given below: 
$$ J = \sum_{i = 1}^N (y_i - A - B X_i)^2 $$

Hence, the method of finding the line os best fit by minimizing the sum of square of residue of called the least square fit. Sometimes, the fitted line itself is called the last square fit. 



# Keep adding the questions here. May be use ipython for LaTeX. 


