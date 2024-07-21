# pandas-challenge
Assignment Task 

There are two csv files to be analyzed.  The assignment requires using git to create local files.  Using pandas and Jupyter notebook to write coding for analysis aims. The final script should both contain coding, print result and analysis report. The task requires that use both school data and student data to evaluate the math, reading, or both scores from different view, which like scores by school size, per budge spending, school type, grade and so on. 

Instructions 

1. First of all, I open the file and merge them to be the school data completion file. I did calculation which required by assignment based on such file data. The function and syntax are similar. But how to set the final value to be 2 decimal really took me sometime to learn and solve it. It is not necessary, but I prefer the good looking and learn more syntax.

2. The school summary is the most difficulty part. I have to learn and use what I taught on class to solve all kind of problems. For example, how to give the $ symbol before total budget and per student budget. In order to make it more rational, I searched and learned the apply(lambda X:,.2f) function. Undoubtedly, it is very useful. First of all, I thought this problem might be the most difficult one. I realize I was wrong when I start to  use the pd.cut with the bins stuffs. When I cut designated column with bins, it always went wrong. I did the exactly way as I taught on class. After that, I reviewed the class view and found that column was float type rather than numeric type. When I found the way to get rid of it, coding still went wrong. However, I did not solve it until I remove the $ symbol, and then it succeeded. Finally, before print the result out, I had to add $ symbol back and made it to 2 decimal. This is the most interesting thing in this assignment and I really leaned a lot from it.

3. Another interesting thing was when I used the groupby function, it alway has a warning content. I learned to use the observed = true after I solve this warning problem.
 

Declaration 

During the task, I used some syntax, formula and functions. Some of them from class, some of them from web search. When I made an error or had no idea what was going on, I chatted with ChatGPT and got some suggestions or debug for coding. I figured the problem out first and understood it, and then typed code down. From this view, my work might have some similarity with others. I am a new learner on coding, have to do lots of research and reading for problem solving. 

 
