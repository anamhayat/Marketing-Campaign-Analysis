# Marketing-Campaign-Analysis
A/B Testing &amp; Regression Analysis Project 


**Regression analysis** is a statistical method used to examine the relationship between one dependent variable (what you're trying to predict or explain) and one or more independent variables (the predictors or inputs).

### In simple terms:

Regression analysis helps you answer questions like:

* "How does the amount of study time affect exam scores?"
* "How does the price of a house depend on its size, location, and number of bedrooms?"

### Common types of regression:

1. **Linear regression** – models a straight-line relationship:

   * Example: `Exam Score = a + b*(Hours Studied) + error`

2. **Multiple regression** – uses two or more predictors:

   * Example: `House Price = a + b1*(Size) + b2*(Location) + b3*(Bedrooms) + error`

3. **Logistic regression** – used when the dependent variable is categorical (like yes/no, 0/1):

   * Example: Predicting whether a customer will buy a product or not.

### Why use it?

* To **predict** future outcomes.
* To **understand relationships** between variables.
* To identify which variables **matter most** in affecting the outcome.



---

### 🎯 What the project Covers:

* **Definition**: Regression analysis is a statistical tool used to model the relationship between a dependent variable ($y$) and one or more independent variables ($x$) .

* **Regression Line & Equation**:

  * You plot data on a graph and draw the **best-fit line** (the *regression line*).
  * This line’s formula is expressed as:


    * $b_0$: y-intercept (value of $y$ when $x = 0$)
    * $b_1$: slope (rate of change in $y$ for a unit change in $x$)
    * $\hat{y}$: predicted value of $y$ based on the model ([jove.com][1]).

* **Usage Example**:

  * The video illustrates using CO₂ as $x$ (independent variable) and temperature as $y$ (dependent).
  * Once you calculate $b_0$ and $b_1$, you can predict the temperature for a given CO₂ level—for example, plugging in 380 ppm of CO₂ might predict around 14.7 °C ([jove.com][1]).

---

### ✅ Key Takeaways:

* Regression finds the line that best represents the relationship between variables.
* It uses that line’s formula to **predict future or unseen values**.
* Coefficients $b_0$ and $b_1$ quantify the strength and direction of the relationship.

---

### 🔎 Broader Perspective

* **Purpose**: Not just predicting, but also understanding *how strongly* and *in what way* variables relate. For example, a positive $b_1$ means $y$ increases as $x$ increases.
* **Applications**: Widely used in fields like economics, engineering, biology, and machine learning.
* **Extensions**:

  * Multiple regression uses several predictors (e.g., size, location → house price).
  * Logistic regression deals with categorical outcomes (e.g., yes/no decisions).

---



