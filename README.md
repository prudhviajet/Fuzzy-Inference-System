# Fuzzy-Inference-System

### Question:
<p>Implement Fuzzy Inference System (FIS) using MATLAB fuzzy logic toolbox. The goal is to find the rating of the sales of a store. The evaluation criteria are based on the following four input parameters. The output of the system is the sales rating of a given store in the range [0, 10].</p>
<p><b>Inputs:</b></p>
<ul>
  <li>Daily Customer : Measured on a scale of 0-10 (Higher rating corresponds to more customers)</li>
  <li>Electronics items: Measured on a scale of 0-10 ((Higher rating corresponds to more options)</li>
  <li>Groceries items: Measured on a scale of 0-100 (Higher rating corresponds to more options)</li>
  <li>Competitors in the vicinity : Measured on a scale of 0-10 (Higher rating corresponds to more competition)</li>
</ul>
<p><b>Output:</b></p>
<ul>
  <li>Sales Rating: In the range [0, 1]</li>
</ul>

#### Solution:
<p>
To determine the relation between output and all different inputs we used CORREL function in excel. The CORREL formula in excel is used to find out the correlation coefficient between the two variables. It returns the correlation coefficient of the array 1 and array 2.<br><br>
When we used CORREL function between sales and daily customers we get a value 0.155826, 0.212413 when done between sales and electronic items, 0.257607 when done between sales and grocery items and finally -0.24297 when done between sales and competition. The correlation coefficient between sales and competition is negative because if competition is inversely related to sales. So in these four values correlation coefficient between sales and daily customers is the lowest, so we will ignore this consider remaining three inputs.<br><br>
Linguistic Variables are variables with a value made up of linguistic concepts (also known as linguistic words) rather than numbers, such as poor, average, good and so on.
The fuzzy rule base is a set of IF-THEN statements that store the practical knowledge of human operators about the process.
</p>

### Fuzzy Logic Designer:
![Screenshot (2092)](https://user-images.githubusercontent.com/84682126/154078397-db68c4de-c418-45f3-a7a2-1051f1e05b59.png)
