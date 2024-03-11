# DSC520-Survival-Analysis
 An assignment for DSC520 at GCU that focused on the creation and analysis of Kaplan-Meier survival curves.

Check out the full report [here.](https://github.com/jhould007/Survival-Analysis/blob/main/Survival%20Analysis.ipynb)

# Assignment instructions
It is important to have experience analyzing data where time to a given event is the dependent variable. The task will be to compare the survival distribution between groups, estimate the survival distribution, and model the effect of explanatory variables on the outcome variable. Then, differentiate between the use of the Poisson distribution to estimate the rate of event occurrence and survival analysis to estimate time lapse between events.

For this activity, perform the following:

* Access the "Echocardiogram Data Set," located in the topic Resources.
* Using the topic Resources, familiarize yourself with the differences between survival analysis and the Poisson distribution, with an emphasis on parameter estimation (e.g. λ = E(X)).
* Explore the data, perform initial descriptive statistics tests, and explain and visualize your findings. Use the kable() function to visualize the data.
* Explore the following R packages: devtools, survival, tidyverse, survminer, survival, and load them into your project.
* Formulate a question that can be answered by performing survival analysis.

Calculate the Kaplan-Meier Estimator in Python:
1. Import the lifelines and matplotlib packages.
2. Explore the KaplanMeierFitter filter and build a kmf object using the response variable.
3. Print the kmf object you generated.
4. Analyze the data with the kmf.fit().
5. Generate a KM curve.

Visualize Survival Data:
1. Familiarize yourself with the matplotlib package.
2. Create a detailed, visually appealing plot of the data using kmf.plot(title=’Kaplan-Meier Survival Curve’, xlabel=’Time’, ylabel=’Survival Probability’).

Generate K-M Curves with the Predictor:
1. Stratify the analysis into standard vs. experimental using fit method with strata parameter.
2. Display the strata using print().
3. Plot the strata using plot().
4. Plot the overall survival, stratified by the appropriate variable.


 Perform Log-Rank Analysis:
1. Familiarize yourself with the logrank_test().
2. Test the difference between survival curves using results = logrank_test(durations_A, durations_B, event_observed_A=event_A, event_observed_B=event_B).
3. Examine and interpret the log-rank output.
4. Plot the K-M curve and include the log-rank test.

Answer Formulated Question: <br>
Were you able to answer the question you formulated? If yes, state the answer and explain. If no, continue the analysis until you can answer the question.
Then, submit a professionally written and formatted software-based technical report. Make sure the documentation contains the code, relevant plots, your analysis, and the appropriate citations and references.

While APA style is not required for the body of this assignment, solid academic writing is expected, and documentation of sources should be presented using APA formatting guidelines, which can be found in the APA Style Guide, located in the Student Success Center.

This assignment uses a rubric. Review the rubric prior to beginning the assignment to become familiar with the expectations for successful completion.

You are not required to submit this assignment to LopesWrite.      
