java c MATHS 7107 Data Taming Primary Examination Written Questions

A committee has been established to organise 200-year anniversary celebrations in each Australian capital city. A large statue has been built and needs to be moved to each city for the celebration. The following tibble contains some of the information that the committee has gathered
The variables in the table are: ● Name: the name of the state or territory ● population: the number of people residing in the state ● urban pop: the percentage of the state’s population who lives in the state’s capital city ● Capital city: the name of the state’s capital city ● Year: the year the city became the state’s capital city, which is used for planning where the statue needs to be. (a) For each of the variables in the dataset identify the type of variable, ie. is it quanti- tative continuous, quantitative discrete, categorical nominal or categorical ordinal. Make sure you write a short description justifying your choice. (b) For each variable state whether the corresponding column in the tibble is the correct data type. If it is incorrect, say what the correct data type should be. Log−Log plot 7 - 6 - 5 - 4 - 3 - 2 - 1 - 0 - −1 - −2 - −3 - −4 - −2 −1 0 1 log(x) Figure 1: Log-Log plot of data for Question 2. 2. (a) Assume that a data set consists of continuous variables x and y, which are related by the formula y = αxk . Using the logarithm laws, show that the Log-Log plot of this data will be a straight line. (b) Using the straight line in part (a), write down the: i). gradient of the line, ii). the value at which the line cuts the vertical axis. (c) Using the Log-Log plot in Figure 1 determine the explicit relationship between x and y.

x1 x2 x3 x4 x5 1 0 2 -1 3 Table 1: Dataset for Questions 3 and 4. 3. For this question, use the dataset in Table 1. (a) Transform the dataset in Table 1 to x* by applying Min-Max scaling. Calculate your answers to 2 decimal places.
(b) What are the minimum and maximum values of the transformed dataset x* ? Give exact values for your answers.
4. For this question, use the dataset in Table 1. (a) Find the mean x and (sample) standard deviation σx of the dataset. Calculate your answers to 2 decimal places.
(b) Standardise the dataset by calculating the z-scores xj() for each xj . Calculate your answers to 2 decimal places.
(c) What is the mean x and standard deviation σx* of the transformed data set. Give exact values for your answers. 5. Show that when x 0 the Box-Cox transformation is continuous at λ = 0, by showing that

We are looking to measure the amount of pollen in the air. We have built 31 cubic boxes, each one with a pollen counter in it. The side lengths of each box is recorded in the list (s1,..., s31 ), where the side lengths are measured in metres. We collect pollen counts from the air samples inside each box, and record the pollen counts in box j as pj . We expect to find a good linear fit with the modelpj = β0 + β1 zj + ϵj , N(0,σ) (1) where zj = sj(3) . We use R to fit our linear model to the data and we obtain the following output:
pollen_lm <- lm(p ~ z, pollen) > summary(pollen_lm) Call: lm(formula = p ~ z, data = pollen) Residuals: Min -22 . 195 1Q -6 .719 Median -0 . 049 3Q 6 .826 Max 20 .877 Coefficients: Estimate Std代 写MATHS 7107 Data TamingJava 代做程序编程语言 . Error t value Pr(>|t| ) (Intercept) 6 . 23517 3 . 59069 1 .736 0 . 0931 . z 1 .31177 0 . 05785 22 . 675 <2e-16 ***

Signif . codes: 0 ‘’ 0.001 ‘’ 0.01 ‘’ 0.05 ‘ . ’ 0 . 1 ‘ ’ 1 Residual standard error: 11 . 27 on ##### degrees of freedom Multiple R-squared: 0 . 9466, Adjusted R-squared: 0 . 9448 F-statistic: 514.1 on 1 and ##### DF, p-value: < 2 . 2e-16 ● Note that we have replaced the number degrees of freedom with #####, and so you need to calculate this number. (a) Use the information in the output to write the equation for the line of best fit in Equation (1) with the appropriate values substituted. (Round off your answer to 4 decimal places.) (b) From the output,what is the estimate of the standard deviation of the errors? (Provide your answer to 2 decimal places.) (c) With this model, what is the prediction for the pollen count in a box of side length 4.3m? (Round off your answer to the nearest whole number of pollen grains.) (d) Write down the details for the two t-tests performed when fitting this linear model. State the null and alternative hypotheses, and the distribution being tested against (including the number of degrees of freedom). (e) What are the relevant P-values for the tests? Are the estimates for the model param- eters significant at the 95% level? (f) Use the graphs in Figures 2 – 4 to determine if the assumptions for fitting a linear model are satisfied. (Make sure you refer to specific Figures in your answers.) In addition, for the independence assumption, come up with at least one reason why the assumption may not be satisfied. Residuals vs Fitted o1

o17

O O O4

50 100 150 Fitted values lm(p ~ z) Figure 2: A residuals vs fitted graph for the linear model in Question 6. Scale−Location

o14

o17 O

50 100 150 Fitted values lm(p ~ z) Figure 3: A scale–location graph for the linear model in Question 6. Q−Q Residuals

1 17

4

−2 −1 0 1 2 Theoretical Quantiles lm(p ~ z) Figure 4: A Q-Q plot of residuals for the linear model in Question 6. 7. A medical test for a certain disease has the following confusion matrix:

No disease Has disease Test negative 100 20 Test positive 50 180 A true positive is where a patient has the disease and the test is positive. (a) Calculate the sensitivity of the test. Provide an exact answer or 3 significant figures of precision.
(b) Calculate the specificity of the test. Provide an exact answer or 3 significant figures of precision.
(c) Calculate the accuracy of the test. Provide an exact answer or 3 significant figures of precision.
(d) Based on your results from parts (a)–(c), would you estimate that the AUC (area under the curve) for the ROC curve is closest to: ● between 0.65 and 0.90 ● between 0.45 and 0.55 ● between 0.1 and 0.35 ● between −0.35 and −0.1 ● between −0.9 and −0.65 Justify your reasoning. (e) What does an AUC value close to 0 tell you about your prediction model? If this was the case, how could we improve the model?
 
   加QQ codinghelp Email: cscholary@gmail.com

