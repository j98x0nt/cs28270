java c
Economics 360 Data Analysis Project 
Fall 2024
For this project, students will apply the methods from class to a real set of data.  Below are the milestones at which students are expected to have tangible progress towards completion.
Critical Due Dates:
September 23, 2024:  Project Topic Worksheet due.
October 27, 2024:  Data set (video) and “working” regression model due.
November 18, 2024:  Formatted Tables 1-2 (and scatterplot) due.
December 6, 2024:  Final project due.
1. Pose a question.  What interests you?  Your data set and hypotheses do not have to have obvious Economics overtones, so if you want to study sports or entertainment, that’s okay.  Just make sure you can find data on the topic of interest.  For example: 
•   Your friend says that “for clothing brands, being featured prominently in popular movies has a huge effect on the sales of the brand.”  What is the causal relationship of interest?  Sales revenue is increased (caused) by the brand’s visibility in movies, ceteris paribus.  You should be able to find data on the sales of various clothing brands and the timing and popularity of movies in which they were featured.  If you find significantly higher sales for brands after the movies are released, you can go back to your friend and say, “Aha!  You don’t know diddily about the fashion industry, and I’ve got the data to prove it!”
Think of some claim that has been made in one of your other classes or by a friend/co-worker/family member that you want to test with data.  Then find a sample that contains observations you can use to test the claim.  A good question is:  a) specific, b) capable of being answered empirically, and c) interesting (non-obvious, non-trivial, original).
By Monday September 23 (final submissions collected in class), students must complete the Project Topic Worksheet (distributed in class).  This is scored pass/fail and counts toward the final score (see last page) on the project. Do not to wait until the last day to submit your proposal unless you are very confident everything is in order.  We can go through as many rounds of revision as needed before the due date, so if you want to make sure your idea is both  feasible and suitable for this assignment, consult the instructor ahead of time.  There will be no revisions for credit allowed after the due date.  This includes proposals submitted on the due date and rejected expost. 
2. Data collection.  Go find data!  Data are all around you, waiting to be organized and analyzed. All one has to do is observe the phenomenon of interest and systematically record observations.  Where can you go to observe the “x” and “y” variables in the causal relationship of interest?
End Goal:
•   Data consist of observations (rows) and variables (columns) and have a rectangular
“spreadsheet” layout.  A data set must observe multiple variables for multiple (n) elements.
•   I’m not asking you to formulate your own survey or anything like that; if you’re really
ambitious, you can certainly do it, but there are plenty of suitable sample data sets already collected that you can use (see Data and Writing Resources in D2L).
•   You need enough information to make meaningful statistical inferences, i.e., large enough sample size and variation in your variables.  E.g., it would be hard to infer much about a    small Indiana town that enacts a zoning regulation, based on a comparison with 5 neighboring towns that didn’t (n  = 6 and x  = 1 for only 1 observation!).
Where should you look?
•   Research librarians, Profs. Zoe Mayhook and Bert Chapman, have built the “Costco” of   economic data (http://guides.lib.purdue.edu/Econ360) for our class.  For most topics, you will be able to find a source of data using one of the tools on this page.
•   Don’t worry if you have to go to multiple sources for different variables, e.g., the
unemployment rate across counties from bls.gov, and the murder rate from the FBI.  Consult Ben and/or his lab instructions for how to match them to one another in Stata.  It requires a    little patience, but is relatively painless and makes your data set much more powerful.
•   If you have difficulty deciding on a set of data or finding a set that you can use to test your hypotheses, please consult me, and I will help get you going.
Students will submit a video presenting the following, due October 27:
•   “Working” regression specification,
•   Data set in Stata format, and
•   Codebook, e.g., Word document, explaining variable definitions.
“Present” means a 5-10 minute demonstration in which you open the data set, explain what variables and observations you have, and answer a couple practical questions that will help make the rest of the project easier.  This is scored “pass” (full), “low pass” (½), or “fail” (0) and counts toward the grade on the project (see last page). Note:  an approved Project Worksheet is a prerequisite for this video, even for students that do not meet the topic approval due date.
The University has its own version of YouTube called “Kaltura,” that students should use to record their voice and capture their screen to make this video.  Specifically the feature is called Kaltura Capture (see the Data Set Assignment in Brightspace for a brief tutorial in how to use it).  After recording your video, Capture will upload it to the University’s server and create a URL.  You should submit this URL to earn credit for this milestone in the Project.3. Econometric Analysis.  Students will construct the following tables (using Stata and Excel)  and one figure and combine them into a single (.docx or .pdf) file.  Both tables should be “self- contained” by including a caption and intuitive labels for the rows, columns, and axes.
3a.  “Table 1:  Descriptive Statistics.”  Give a sense of how your variables are distributed.
Construct a professional and easily understandable table of the descriptive statistics on your variables.  This means sample size, sample mean, a measure of variability such as standard deviation, and skewness.  For categorical or binary variables, make it clear how you have made them quantitative and that the means represent proportions, e.g., the proportion that is male, lives in Tippecanoe County, or the proportion of the songs on your streaming history that is a particular genre.  Ask yourself, “Do all the descriptive statistics seem plausible?  If they do not, what are some explanations for their bias?”
•   Carefully explain the units (weekly income?  monthly?  annual?) in the row labels and the unit of observation (county?  state?  occupation-state?) in the caption.
•   Are there missing observations or outliers for any variables?  If so offer an explanation.
•   Does the size of your sample present any concerns about the normality of the sampling distribution?  Speculate about whether the dependent variable’s distribution (skewness, outliers) presents any problems for the Central Limit Theorem.
o Would taking logs help? For clarity present the descriptive statistics in levels, even if you take logs when you do the regression.
3b.  “Table 2:  Regression Estimates:  Effect of              on  .”  Use Stata to estimate a
simple linear regression for the relationship between the (hypothesized) causally related variables:
y(^) = β0  + β1x.
Build up your regression specification with explanatory variables that either:  i) shrink the error variance and improve precision of the estimates, or ii) control for omitted factors in the error term (in the simple OLS specification).  Reference the list you made in the Project Topic Worksheet and add others you collected in the interim.
Create a table like the one in Ben’s lecture notes, showing between 4 and 6 different specifications (1 estimate per column) and enabling the reader to compare the βs of interest by reading across the top row. 
The lower portion of the table should have a row that enables the reader to differentiate the estimates according to what else is included in the model, like the example below.
"Table 2:  Regression Estimates . . . ."


a 
b 
c 
d 
Your 
main x variable with 
units 
[Simple OLS 1 ] 
(s. e. ) 
[Your 1|spec.  b ] 
(s. e. ) 
[Your 1|c ] (s. e. ) 
[Your 1|d] (s. e. ) 





Controls 
None 
[Important control var.] [More control vars.] 
All 
Adjusted R2 




The body of the table should be as self-explanatory as possible, but any information that cannot go in the row labels, etc., should be explained in a caption, e.g., what is included in “All”?
There is a rubric in D2L, where students submit this assignment, listing other criteria for a full pass grade on Table 2.
3c.  “Figure 1:  Use Stata to produce a scatterplot showing the mapping of x to y, and include the estimated regression line on the plot to summarize their co-movement.
By November 18, your polished (full points) version of “Tables 1-2” (and scatterplot) is due in the drop box on Brightspace.  This counts toward your grade on the project (see last page).  If either Table is incomplete or poorly formatted you will earn a “low pass” (½) or “fail” (zero points) on this part, which signals that the student needs to revise it before the final due date.
4. Final Project Report.  On (or before!) December 6, students will turn in the following, by uploading 3 files to the Semester Project folder on Brightspace.
•   A strictly less than 15-minute-long video capturing your on-screen regression estimates and diagnostics (Tables and Figures, see below) and a verbal summary of the topic, estimates, robustness, and conclusions drawn (see rubric below and on D2L).
•   The (cleaned,代 写Economics 360 Data Analysis Project Fall 2024SQL
代做程序编程语言 .dta format) data set you used to produce the results.
•   The Stata do file containing the commands, in the order they appear in your write-up, that you used to produce the regression estimates, test hypotheses, and run other tests.  I should be able to open the data set in Stata and run your do file from start to finish without any errors and re-produce your results. 
o .dta and .do go in the same folder, which allows multiple files per student.
4a. Robustness and Diagnostic Tests.  Extend your causal hypothesis to groups within the sample.  For example:  “stricter parental ratings will have a negative effect on video game sales. But it will have a bigger negative effect on ‘first person shooter’ style. video games.”  Report on a table the results of a specification that involves interacting the x variable of interest with 1 or   more other regressors.  Report the marginal effect of x for each group separately and a standard  error for it. Label this one “Table 3:  Interaction Estimates” . 
Run the B-P and White tests for heteroskedasticity and report the results.  This could take the format of a Table or stating the test stats and conclusions in paragraph form. (the code will be in your do file).  Do not copy and paste a screenshot from the Stata output window, since it is not aesthetically appealing.  Report (and explain in the captions) on Tables 2-3 robust standard errors if warranted. 
Run the RESET to detect functional form. misspecification.  Your most saturated specification in Table 2 should include polynomial and interactions terms that, if omitted, would significantly reduce R2 .  Your do file and your summary of the results should include F statistics to confirm the joint significance of these regressors.
Produce and show in your video the leverage-residuals plot (“Figure 2”) from the full-sample specification with the highest adjusted R squared.  Are there any outliers or influential observations that concern you?  If so your Tables 2-3 should probably exclude the outlier observation(s) and contain a note in the caption explaining your treatment of outliers.  If you decide that the observation(s) should be in the sample, explain your reasoning in the caption.
4b. Results Summary Video.  Prepare all your estimates tables and figures.  Then use video production software to capture your screen and microphone while you display your results and discuss the estimates. 
For a good grade, students need to satisfy all the objectives listed on the rubric.  Moreover they must do so in a strict 15 minute time limit.  I have seen plenty of “A” caliber videos that were   10-12 minutes, so please do not feel obligated to “fill” the time.  Suggestions:
•   Plan out your presentation with an outline ahead of time.  Budget time roughly as follows.
o 2-3 minutes:  a statement of the causal relationship of interest, answers to the first 2 FAQs
o 1-2 minutes:  a summary of the data source you use (answer FAQ #3), including its strengths and limitations.  You can show a list of variable names on screen while discussing this.
o 1-2 minutes:  the regression model specification in equation form. and a written
explanation of the variables you will use in your analysis and the units, e.g.,
individuals or countries, that are observed.  This is where you state hypotheses about parameters you will test, too.
o 1-2 minutes:  the descriptive stats table.  Focus discussion on y and main x variables.
o <1 minute: Figure 1 and discuss 2-D scatterplot and simple OLS line.
o 5-6 minutes:  discuss (on screen) multiple regression tables and supporting statistics and diagnostics.
o 1-2 minutes:  brief summary of your results.  Have you accurately measured the causal relationship of interest?  Again it’s okay if you’re skeptical.
What kind of “natural experiment” would you seek out if you could spend   another semester (doesn’t that sound fun?) studying this and improving your methods?
•   Take advantage of the multimedia format.  Let me read the results on screen while you discuss them.  Don’t read to me.  Give the viewer information through his eyes and ears.
•   Do multiple takes until you get the pace right and learn to where to “trim the fat.”
•  The caliber of verbal communication will befit a college graduate.  A video that is
incomprehensible (because of poor sentence structure, grammar, using words out of
context, or subject-verb disagreement, et al.) will earn you no points.  I will not (nor will  any viewer) waste time trying to decipher poorly composed content.  I have to view more than 50 essays from the class, and I reserve the right to award a failing grade to any 
video that is too hard to understand for grammatical or mechanical reasons.
o Remember it’s your job to communicate your thoughts to the reader—not the viewer’s job to divine what you are trying to say.
Particular Suggestions about the “core” of the report: Table 2.
•   State the null and alternative hypotheses in terms of parameters (βs) that will test the relationship of interest.
•   Discuss the sign (+/-) on β1 ?  Does it confirm your original prediction? ^
•   Discuss the default and robust standard errors of β1  and how statistically different from the null (usually but not always zero) hypothesized value the estimate is.  In practical terms, is  there a “wide” confidence interval around the point estimate?
•   In terms a non-economist could understand, interpret the coefficient estimate:  “ . . . a one unit change in . . . is associated with a . . . .”  Is this a practically large effect?
•   Discuss how well the linear trend “fits” the data.  What is the coefficient of determination (R2 )?
•   Discussing variables in the error term that could create omitted variable bias.  State
specifically what in the error term is related to x (and why, theoretically, you should worry
about this; think education and omitted ability) and whether it would bias β upward or downward.
o This might seem challenging if you haven’t taken a lot of other Econ. theory classes, but consult your instructor or TA about your ideas.
•   Discuss the set of estimates.  How does β change with the addition of controls?  Is this    consistent with controlling for omitted variables and reducing bias (see previous bullet)?
•   Comment on what’s going on with R-2  and standard errors as you add controls.
•   Assess your level of satisfaction with how the multiple regression tackles omitted variable bias.
o It’s okay if you are critical.  Often the omitted factors are very difficult to observe and control for in cross sectional samples.
Table 3
•   Explain why you think this interaction is a relevant test of the robustness of your hypothesis. E.g., “why should 1st person shooters be more adversely affected by ratings guidelines?”
“Oh yeah, because they tend to be more violent than other genres of games.”
•   Does the group with the biggest (absolute value) effect match your hypothesis?
•   Are the marginal effects statistically different between/among multiple groups?  State your null hypothesis, test it to verify this, and report the results.
Project Grading Rubric 
The instructor evaluates students’ videos on the following criteria.  Each criterion will receive a “pass,” “low pass,” or “fail” (0 points) score, (see next page).
1.  Introduction (Pass=5; Low Pass=3):
a.  Describes a novel and interesting empirical question
b.  Adequately addresses the first 2 “FAQs” in empirical analysis
c.  Clearly explains the data source and unit of observation
2.  Description of methods (Pass=5; Low Pass=3):
a.  Includes a regression model with the exhaustive list of controls
b.  Clearly explains the variables and units in the model
c.  Clearly states hypotheses that will be tested statistically
3.  Tables and figures (Pass=5; Low Pass=3):
a.  All assigned parts are present
b.  Are well-labeled, well-formatted, easy-to-read, e.g., no log variables on T1
c.  Are self-contained with informative captions
4.  Empirical methods/results are (Pass=5; Low Pass=3):
a.  Correct and applied consistently with in-class examples, e.g., using log forms of variables
b.  Supported by appropriate testing
c.  Accompanied by Stata code, enabling the reader to reproduce the findings 5.  Conclusion(s) drawn (Pass=5; Low Pass=3):
a.  Explained clearly and concisely
b.  Are consistent with the quantitative results and principles of statistical
inference studied in class
c.  Include the practical significance of the results, e.g., elasticity of y with respect to x, when using a log-log model
6.  Data set (Pass=5; Low Pass=3):
a.  Unit of observation, set of variables match those specified in approved topic proposal and requested by the instructor.
b.  Has value added, e.g., intuitive variable names and/or labels, redundant variables dropped, nonnumeric characters (like %) removed
c.  Is cited and enables the reader to locate its original source(s) 7.  Verbal communication (only “pass” or “fail”):
a.  Video is coherently organized (as described in the instructions)
b.  Transitions from each idea to next smoothly
c.  Contains minimal formatting/grammatical errors
d.  Data and empirical results/methods are described in comprehensible language
Item(s) 
Score 
12 
1[7“Pass”] × 

/10 
3-6 

/20 
Proposal Worksheet (approved by 9/23/24) 
/2 


/10 
Data set video (by 10/27/24) 
/4 
Tables 1-2 (by 11/18/24) 
/4 
Overall Score 

/40 
Overall Score = 1[Item 7 "Pass"](Score, Items 12) + (Score, Items 3 - 6) + (Points on intermediate steps)

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
