# Meta-Capstone-Projects
Capstone Projects from Meta Marketing Professional Certification

Week 1: Getting to Know the Data


This week is all about descriptive statistics. I learned about measures of central tendency, measures of dispersion, frequency tables, scatter plots, and 
correlation coefficients. These all can be important tools for understanding your marketing data. For this Capstone Week 1 assignment, I used these tools 
to better understand the data in the Capstone Dataset spreadsheet.
The spreadsheet consist of - 
a Facebook Ad campaign and an AdWords Ad campaign. The data is collected for every day of the year 2019, so we have 365 lines of campaign data to analyze! 
Ultimately, we want to determine whether one of these ad campaigns is more effective, in terms of conversions, compared to the other. But before we address 
that question, we should get a better understanding of the conversion data for each of the campaigns.
To better understand how effective our campaigns are at producing conversions, we’re going to begin by analyzing the relationship between a campaign’s number 
of clicks and the corresponding number of conversions. 
Let’s do this by calculating 
(1.) the measures of central tendency, 
(2.) some measures of dispersion, and 
(3.) the frequency and correlation data for a campaign’s clicks and conversions.
We’ve learned how to do all of these things with our spreadsheet software. Below, we show you the results we get for the Facebook Ad data. We started by creating 
a new sheet in our Capstone Dataset spreadsheet and copy-and-pasting the “Date,” “Facebook Ad Clicks,” and “Facebook Ad Conversions” data into the first three 
columns of our new sheet. This makes it easier to work with that specific data for the calculations that follow! 
Note: for your Capstone Week 1 assignment, we are doing these calculations for “AdWords Ad Clicks” and “AdWords Ad Conversions.”
1. Calculate Measures of Central Tendency
For this first set of calculations, let’s determine the mean, the median, and the mode for both the number of “Clicks” and the number of “Conversions.” 
we can calculate the mean using the =AVERAGE formula. In our example below, we displayed the result for “Clicks” in cell E2, and for “Conversions” in cell E6.
we can calculate the median using the =MEDIAN formula. In our example below, we displayed the result for “Clicks” in cell E3, and for “Conversions” in cell E7.
we can calculate the mode using the =MODE formula. In our example below, we displayed the result for “Clicks” in cell E4, and for “Conversions” in cell E8.
In our example, we show you the results for the Facebook Ad Clicks and the Facebook Ad Conversions. For your Capstone Week 1 assignment calculate the 
mean, median, and mode for AdWords Ad Clicks and AdWords Ad Conversions. 
2. Calculate the Standard Deviations
Now that we have determined the “middle” values for our ad campaigns let’s get a sense of how much variance from the middle value we should expect from our data. 
We’ll do this by calculating the standard deviation for our “Clicks” data and our “Conversions” data. This tells us how “spread out” our data is. 
we can calculate a standard deviation using the =STDEV formula. 
3. Create a Frequency Table for Conversions; Analyze the Correlation between Clicks and Conversions
Finally, let’s get a clearer picture on how much correlation there really is between our ad clicks and the number of conversions we get through the ad. 
Do more clicks on the ad really lead to more sales? We’ll address this question by, first, creating a frequency table that tells us exactly how many days of the year we recorded specific numbers of conversions: less than 6 conversions, 6 - 10 conversions, 11 - 15 conversions, and greater than 15 conversions (see example below). Then, we’ll analyze how much these conversions correlate to the number of clicks by creating a scatter plot for Conversions v. Clicks, and by calculating the correlation coefficient for these two variables. Recall from our reading on “Frequency, Contingency, and Scatter Plots” how to perform these tasks in Excel or Google Sheets:
we can create a frequency table byusing the =COUNTIF and =COUNTIFS formulas to count the number of occurrences for each grouping of conversions (i.e., “<6” occurrences, “>5” but “<11” occurrences, “>10” but “<16” occurrences, and “>15” occurrences). In our example below, you can find our frequency table in the area highlighted with the red “3a.”
You can create a scatter plot by using the “insert chart” functions in your spreadsheet software. (Refer to your software documentation for more information.)  In our example below, you can find our scatter plot in the area highlighted with the red “3b.”
You can calculate a correlation coefficient using the =CORREL formula. In our example below, we displayed the result for “Clicks” in cell E10, and for “Conversions” in cell E17.

Week 2: Understanding Your Data Samples


we learned some important questions to ask about your data samples. The answers to these questions can be essential to determining what kind of analysis we will ultimately be able to perform with our data! For example, we learned how to create histograms for our data samples, which help you determine what kind of shape best describes the distribution of your data. It’s important to know this because many analyses require that our data has a specific kind of distribution shape (for example, a normal distribution curve). Similarly, in later weeks we’ll be learning several types of analyses that require specific types of variables. So, it’s important that you are able to determine what types of variables we are working with. For this Capstone Week 2 assignment, we want to use the skills you’ve learned to better understand the distributions and variables in your Capstone Dataset spreadsheet.

1. Create Histograms for ‘Clicks’ and ‘Conversions’ Data
A distribution shows the probability of possible outcomes occurring within your dataset.
Distributions are represented by a distribution curve. This week we learned how to visualize the distribution of values by creating histograms. Histograms are a type of bar chart, where each bar represents a value range and the number of data values that fall into that range. We call these ranges “buckets.” The height of each bar in your histogram will be determined by the number of data values that fall into each “bucket.” So, the bars in your histogram just represent the frequency for each value or value range in your chart. Review this week’s reading, “Distribution,” for a refresher on how to create a histogram in Excel and Google Sheets.
In our Capstone Project we have begun to focus on our data for “Clicks” and “Conversions” from each of the ad campaigns (Facebook and AdWords) in our Capstone Dataset. For this first part of our Capstone Week 2 assignment, we want to determine whether our data for “Clicks” and “Conversions” falls under a normal distribution curve. To do this, use your spreadsheet software to create two histograms—one for the “Clicks” data and one for the “Conversions” data.
For our “Clicks” data create a histogram with a bucket size of 10.
For our “Conversions” data create a histogram with a bucket size of 2.
Evaluate our histograms: Do they show a Normal distribution?
For our Capstone Week 2 assignment create histograms for AdWords Ad Clicks and AdWords Ad Conversions, then determine whether they fall under a normal distribution curve. 
2. Determine What Variable Types we’re Working With
Now, the question of “Independent” versus “Dependent” cannot be answered until we have set up a hypothesis test for our data, which we will do next week. But we can determine whether our variables are “Quantitative,” “Qualitative,” “Continuous,” “Discrete,” “Nominal,” and “Ordinal” just by looking at the data values and considering how they were collected (or calculated, as the case may be). 
our Capstone Week 2 assignment, we want to determine the variable types for all the AdWords variables in the Capstone Dataset.
Place each of these variables:                                                                                                                                         (1.) AdWords Ad Views,                                                                                                                                               (2.) AdWords Ad Clicks,                                                                                                                                                  (3.) AdWords Ad Conversions,                                                                                                                                            (4.) Cost per AdWords Ad,                                                                                                                                                (5.) AdWords Click-Through Rate,                                                                                                                                        (6.) AdWords Conversion Rate,                                                                                                                                           (7.) AdWords Cost per Click. 
Into one of the following variable types.
Quantitative-Continuous
Quantitative-Discrete
Qualitative-Nominal
Qualitative-Ordinal

Week 3: Testing Your Hypothesis


we focused on the experimental design process and hypothesis testing. This is where the rubber really starts to hit the road when we’re analyzing data!  For this Capstone Week 3 assignment, we want to use what we’ve learned about experimental design, and marketing studies in particular, to formulate and test a hypothesis for our Capstone Dataset spreadsheet.
we discussed the full design process involving five basic steps:
Questioning
Hypothesis
Required Variables
Choosing a Measurement Approach
Selecting an Analysis
For this week’s Capstone assignment,we are going to evaluate the question, and we’ve already gathered the required data into your Capstone Dataset spreadsheet. So, we will not need to worry about steps 1. and 4., above. Also, we will save step 5. for next week. This week we will focus on steps 2. and 3. of the full experimental design process: formulating a hypothesis and testing it!

1. Formulate a Hypothesis to Answer Your Evaluation Question
Marketing studies begin with an evaluation question. We noted how these evaluation questions come from many sources. Sometimes we get them from our manager as they evaluate business needs. The question may come directly from a stakeholder or client. we may even come up with an evaluation question ourself, when thinking about our marketing efforts and audience, or ways to help our company.
It’s these evaluation questions that motivate us to form hypotheses—proposed answers to the question at hand—that we can then test through our analysis of data.
For this Capstone Week 3 assignment we are going to analyze the Capstone Dataset data with the following evaluation question in hand:
The first task we are going to address this week is to write a hypothesis statement that answers this evaluation question. 
good hypothesis addresses three parts:
Three Parts of a Clear Hypothesis:
What will change?
How will it change?
What will cause the change?
we should try to formulate our hypothesis to address these three questions. For example, a good hypothesis for the evaluation question above might say something like: “Our number of conversions will be greater if we advertise on platform X rather than platform Y” (where X and Y are one of the platforms, AdWords or Facebook). This hypothesis answers the evaluation question in a way that addresses the three parts of a clear hypothesis. 

2. Determine Your Independent and Dependent Variables
Once we have formulated our hypothesis, we will need to consider what variables from our dataset are required to test that hypothesis.we will typically manipulate one set of variables to see how changes in those variables influence changes measured in some other set of variables. In a test like this, we call the variable that we manipulate an independent variable. The variable whose effect we measure is called a dependent variable. In terms of the parts of a clear hypothesis statement, the dependent variable will be what addresses the question of “what will change;” and the independent variable will be what addresses the question of “what will cause the change.” So, we should be able to infer our independent and dependent variables from the hypothesis formulated above!
Consider the evaluation question and our hypothesis for this assignment to determine the independent and dependent variables for testing your hypothesis. 
3. Test Your Hypothesis
It’s time to test our hypothesis. It is quite clear from the evaluation question we were given that our test will involve a comparison: we were asked to compare Facebook and AdWords Conversion data. This is typical of marketing analytics questions!
hypothesis tests are framed in terms of the question: “Is there a  difference?” 
we learned how this question implies two possible answers, or two hypotheses:
We call the first hypothesis (H0) the null hypothesis. We refer to the second hypothesis (H1) as the alternative hypothesis. Hypothesis tests are designed to determine which of these hypotheses—the null hypothesis or the alternative hypothesis—is the true one. This is what we need to do for the hypothesis formulated above.we should begin by getting clear on what the null and alternative hypotheses are for our hypothesis test. 
Here are the things you should do to test your hypothesis:
a. Calculate the mean values for the “Facebook Ad Conversions” and “AdWords Ad Conversions” data we were given in our Capstone Dataset. (Remember: we can do this in Excel or Google Sheets with the =AVERAGE formula.) This will tell whether there is any overall difference between “Facebook Ad Conversions” and “AdWords Ad Conversions.”
b. Next,we need to determine whether this overall difference is a statistically significant difference.we learned to do this by comparing the p-value for our data to some given Alpha value (𝛂). 
They are giving an Alpha of 5% (𝛂 = 0.05); but we will need to calculate the p-value for ourself.we can calculate the p-value in an Excel or Google Sheets spreadsheet by applying the t-test formula  
(In the t-test formula, “A:A” refers to the column of “Facebook Ad Conversions” data and “B:B” to the column of “AdWords Ad Conversions.”) If our t-test formula gives  a p-value that is less than 𝛂, then that means the difference between “Facebook Ad Conversions” and “AdWords Ad Conversions” is a statistically significant difference. 
c. Given what we’ve discovered about whether there’s a statistically significant difference in the data, what does this tell us about whether to accept the null hypothesis or the alternative hypothesis?
d. Finally, putting it all together: What’s our conclusion about our main hypothesis? Is there a difference, and is it what our hypothesis predicted

Week 4 assignment is to run a model that answers this question.


1. Choosing a Model
we looked closely at three common types of models and how to run them using the Tableau software. Those models were: Simple Linear Regression, Cluster Analysis, and Time Series Analysis. We also discussed Classification Analyses, though more briefly and without running one in Tableau. For all these models, there are specific requirements that must be met for you to even be able to run them and obtain accurate results. This is why we have spent so much time considering how to choose the right model for the specific analysis you might be asked to run. We’ve collected all these considerations into a “Choosing A Model” checklist, included below, that you can use to help you decide what model to run for this week’s assignment.
The first consideration when choosing a model involves understanding that each type of model was designed to meet a specific purpose. So, the very first thing you want to do when choosing a model is to determine whether the purpose of a model matches the objective behind your analysis! For example, if you are asked for an estimate of what your company’s profits are projected to be over each of the next three months, a Time Series Analysis could be a good modeling technique for answering this question. That’s because Time Series Analysis models are designed for forecasting, i.e., predicting the value of some value (like profits) at future times (like each of the next three months).
After you’ve narrowed your choice of model according to purpose, you next have to consider variable requirements. For example, the variables you’re concerned with in the question given above are “Facebook Ad Conversions'' and “Facebook Ad Clicks.” You’ve learned how to characterize these variables by type (such as quantitative v. qualitative, and independent v. dependent). This information is important because each model requires variables of specific types. So, if you consult our checklist below, you can see that you need a quantitative independent variable and a quantitative dependent variable in order to run a Cluster Analysis.
Finally, once you’ve determined a model you’d like to run, based on purpose and variable requirements, you must look at your data to make sure it meets a set of certain assumptions. Your data must meet these assumptions in order to give you accurate results! For example, you might determine that Simple Linear Regression fits your analysis in terms of purpose and variable types, but does your distribution for these variables meet the “normality” assumption, under that model in the “Choose A Model” checklist? (Notice that much of the work that you’ve done in previous weeks of the Capstone project will help you determine whether your data meets such assumptions.) Refer again to this week’s readings and videos for a refresher on what all of these assumptions mean.
For your Week 4 Capstone question:
Refer to the “Choose A Model” checklist below and determine:
Which model’s purpose best addresses the question at hand.
Which model’s variable requirements are met by the question at hand.
Which model’s assumptions are met by the Capstone Dataset data.
2. Run Your Model
Now that you have determined the model that will best address your question, it’s time to run it!
you learned how to use Tableau to run three of the model types described above: Simple Linear Regression, Cluster Analysis, Time Series Analysis. (Hint: one of these is the model that best addresses the question at hand.) We recommend that you use Tableau to run your model. However, if you have other tools to run your model, feel free to use those instead. But for this exercise, you are required to produce a visualization chart, similar to the one below, which shows the results of your analysis. You will need to take a screenshot of your visualization and paste it into your Capstone Slide Deck slides for week 4. As we’ve seen from this week’s discussions, Tableau is an excellent tool for producing such visualizations.
Finally, remember that the purpose of running models is to be able to analyze specific results (such as predicting a value for a specific future date, or segmenting data to see the habits of a specific group, etc.). Once you have run your model for this week’s assignment, you should be able to read a specific result for Facebook Ad Conversions v. Facebook Ad Clicks directly from your visualization chart! 
Using your chart, state what your model shows to be the expected number of Facebook Ad Conversions for a day of 50 Facebook Clicks.



