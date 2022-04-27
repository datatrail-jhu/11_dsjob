A common part of a data science interview often involves some type of take-home analysis. Sometimes, the analysis will take a few hours to a few days and you'll be given a week from time of receipt to when you have to return the analysis to the company. Other times, you'll have two hours from time of receipt. The company will inform you of the format and then you'll be off to complete the project!  

Think of the take-home as a homework assignment. You have your notes and resources (aka the Internet) at your disposal and will be working from the comfort of your computer. This means that when you get the project, the first thing you should do is read the instructions. Then, read the instructions again. Keep reading the instructions throughout the process. You wouldn't want to do poorly on this assignment because you were unable to follow instructions. Often these projects will describe a scenario that you may find yourself in at the company. This is helpful for two reasons: One, It makes the project realistic, since it's based off something that actually happened in real life and two, it gives you an idea of the types of problems and data you'd be working with at the company. It gives you a chance to see if you'd like the work!

For example, consider the hypothetical situation that data scientists at Etsy, "a global online marketplace, where people come together to make, sell, buy, and collect unique items," give you a take-home assignment during your interview where they provide sales data from their site and information about changes to their site over time. It is then your job to determine what changes were most effective. It would be your job to read the instructions, determine what you need and what you have to answer the question and then to analyze the data.

After reading the instructions through at least twice, it's time to plan. Take time to think about the question and devise a plan. Think about the following questions: What information would I want to have in a perfect world to answer this question? What variables do I actually have? How many observations do I have? What type of analysis should I use? Predictive? Inferential? What statistical analysis would be appropriate for this type of data? How do I plan to visualize the results? And, what would that look like? As you begin to answer these questions and devise an approach, you'll want to keep it simple. Remember, this is only supposed to take you a few hours so you're limited in how much you'll be able to get done. Start with simple models and then work toward more complex. This is how all analyses should be done, so this will demonstrate that you have a reasonable approach to analysis, rather than just starting with the most complex, confusing, and newest approach out there. 

Finally, you should be forming your data science question at this point in time. The questions you'll want to ask in your analysis will likely not be spelled out explicitly in the assignment. It will be your job to determine what the right questions to ask are and what you'll do to answer them. Consider what the instructions say, form the specific questions you'll ask in your analysis and be sure that these questions are in-line with what the instructions ask of you. 

For our hypothetical Etsy example, maybe we decide we're most interested in answering the question: "Do large overhauls to the website increase sales more than small changes?" This seems like a reasonable place to start and a fairly straightforward question to answer. For this question we'd need to determine from the data we've been given which changes were large and which were small. Then, we'd need to calculate changes in sales associated with each website change. We'd use these data in our analysis to answer our question of interest. However, this is not the only question we could have asked. Thus, we would want at this point to refer back to the instructions to make sure the questions we're asking actually fit with what was asked of us in the assignment. We'd want to determine all the question (or questions!) we'll answer with our analysis at this point in time and ensure that they're appropriate for the assignment.

At this point you should also be deciding on what tools you'll use. In an ideal world you'll know at this point what tools and programming languages the company uses and you would demonstrate knowledge of those. However, do not use tools with which you're unfamiliar if you won't be able to complete the assignment. Better to use tools you know and complete the project than to flail trying to learn a completely new language while completing this project.

After determining the questions we'll ask during the analysis and with a general plan in hand, it's time to do the analysis! The first step should always be data cleaning. Be sure that the data are what you expect them to be. Are there missing values? Do the values you have make sense? Are there outliers in your variables of interest? Explore the data and become comfortable with the information you have before moving on. The amount of cleaning you'll have to do will depend on the data you've been given. For shorter assignments you will likely be required to do less than longer assignments, but you'll always want to check clean the data before moving on to analyses. Trusting the data and not checking it before an analysis is a red flag to any data scientist -- you always want to check the data before analysis.

Once you have your dataset in a workable format, you'll always want to do an exploratory data analysis. Generate some exploratory plots that help you better understand your data. How many observations do you have? What are the typical values taken for each of your variables of interest? How are they related to one another?  

In our hypothetical Etsy example from above, maybe you would plan to do an exploratory analysis looking at sales over time. You'd generate a plot to look at the relationship between these two variables.

You'd determine whether or not there are outliers. You'd work to understand any spikes or dips in sales. You'd consider seasonal effects. Basically, you'd think about any results you generate. Then, after understanding this relationship, you could add in information about when changes to the site were made and start to understand how those affected sales.

Whether the assignment asks for an inferential or predictive analysis, you'll likely want to carry out some type of regression analysis to assess the relationship between variables. When you carry out your regression start simple. Your model can become more complex from here if need be, but always start with a simple model and understand and interpret that model before generating anything more complicated. 

For our hypothetical Etsy example, the prompt suggests that this is an inferential analysis looking to better understand the effects of website changes on sales. The assignment does not ask us to predict anything, so we wouldn't want to use predictive analysis tools. We'd start by assessing the relationship between sales and time. If sales have gone up linearly over time, we'd use linear regression. If there was not a linear relationship, then we'd consider a more appropriate analytical approach, but we'd start with the simplest (while still appropriate) approach possible.

After you've carried out your analysis, you'll want to convey your results effectively -- this could require a few plots or tables. Regardless, you'll want to generate visualizations that demonstrate the results of your analysis in an effective an appropriate manner. Be sure that axes are labeled, that the text and points are large enough and that the appropriate graph has been used. 

For our hypothetical Etsy example, you'd certainly want to visualize sales over time. You'd want to be sure the axes are labeled clearly and that the title of your plot explained the important message being conveyed by the plot. You'd additionally want to include either a table of your regression results or a visualization demonstrating the regression line on the data. You'd want to summarize all important results using effective tables and figures.

With the analysis complete and your question answered, it's time to get the project ready to go back to the company. You don't want to hand them an analysis that is messy or a report that can't be easily followed. Refer to the information in the "Written and Oral Communication in Data Science" course in this course set to generate an effective report or presentation (depending upon what they ask you to do!).  Remember, communication is an important skill of a data scientist! Communicating the results of the take-home assignment effectively is part of the interview. Throughout your analysis process you'll have written code and generated plots that do not need to be in your final report or presentation. After you've done the analysis, you'll want to take the time to determine what code and which plots you'll need to tell a story. Organize your thoughts and plan how you'll want your final report to be organized. Once organized, it's time to write up your report. Be sure this report tells a story. It should include the questions you were asking, a description of the dataset, an explanation of your approach, your analysis, your results, and a conclusion. Include clear explanations of what you did, the code, and all necessary graphs and tables. For our purposes, this will likely be an R Markdown report, which is a great  way to communicate an analysis effectively. Last but not least, you'll likely be tired at this point in the process but don't skip proofreading. Take the last few minutes to read what you've written, to check for typos, and to make sure it all makes sense. Attention to detail is important for data scientists, so be sure to hand over an analysis that has been proofread and is clear. 

To finish off this lesson, we wanted to include an example take-home analysis that you may be given on a data science interview. This first example provides you a good idea with something that applicants may be asked to complete in their interview. This example comes from the Data Science team at The Hershey Company. All of the information you see in this lesson would be the information that would be provided to the applicant. This would be provided in the form of a two page document. The document begins with a brief explanation of the exercise. This introduction gives the applicant an idea of how much data they'll be working with and what their goal is, which in this case is to predict dollar sales.

Accompanying this document there would be three datasets that the applicant would use to complete this task.

Additionally, the applicant is provided a description of the promotion tactics included in the dataset:

The applicant also gets a data dictionary, or an explanation of what each variable in the dataset is.

Last but not least, the applicant would be provided further directions and scoring criteria. This part of the document should be read multiple times, as it makes clear what the applicant is expected to do and in what form your response should be submitted. Specifically, for this example, when you go to consider what tools you're going to use, after reading the directions, it becomes clear that you're limited to either R or Python. When it comes to considering what type of analysis you'll be doing, you know off the bat that this is prediction (and not inference), since the title is "Predictive Modeling Exercise." The directions also specify that at least two models should be used. You want to be sure you follow this instruction. And, you must explain why you chose one method over the other. It is specified in the directions that two files must be submitted. Thus, you need to be sure if you're the applicant that you submit both files at the end. The authors of this take-home also give you a little bit of direction. They inform the applicants that they'll be using root mean squared error to assess the predictions and will be looking at how you thought through and addressed the analysis.

Our second example comes from Wikimedia Foundation. The full example can be found on GitHub using the link on the video. This task would be asked of applicants who have applied to be a Data Analysts in the Discovery department at the Foundation. The example task that the applicant would be provided first gives the applicant some background about the type of data they'll be working with. The applicant is informed that the team is interested in clickthrough rate and zero results rate. These two terms are defined in this background information and the applicant is informed that they'll be working with Event Log data.

After the background, the applicant's task is laid out. The instructions here specify that a reproducible report must be generated (You know how to do that in R Markdown!).There are then four questions that the applicant must answer using the data they're provided. 

After defining the task, the dataset is explained, defining each variable and its type.

Last but not least, an example session is provided to give the applicant some idea of what the data they'll be working with looks like. And, with that the applicant is off to complete the Task! The goal here was not to provide enough information to walk you step-by-step through each example and explain how to complete the task. Instead, the goal here was to give you an idea of what types of tasks are asked of data scientists during interviews. That said, the data are available for the Wikimedia example, so feel free to play around with the data and give it a go!

In this lesson, we've introduced the take-home data analysis that is a part of most data science interviews. We've discussed how to approach this part of the interview and provided two examples of the types of tasks that applicants are asked to complete during their interview process.