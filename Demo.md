## Video demo challenge
In this exercise we're going to explore a dataset involving the effect of diet on early growth of chicks. We will use two useful packages: R Color Brewer, which creates nice color palettes and R Markdown to turn our analysis into a final report.

For the submission you'll record a 3 - 5 minute video demonstrating how to carry out any part of the exercise and post it to the Canvas Discussion thread.

1. Download and read the comma-separated file "ChickWeight.cvs"

2a. First, explore the data. How many chicks are in the dataset? How many different diets are in the experiment?

2b. What are the range of chick weights in the dataset?

2c. What chick was the heaviest? Lightest?

3. To vizualize the basics of the data, plot weight versus time.

4. Create a multipanel plot of the first four chick weight versus time. Useful function: par()

5. Plot a histogram of the weights of the chicks at the final day of the experiments (i.e. only the chicks who made it to the last day).

6. Create a boxplot where the x-axis represents the different diets and the y-axis is the weights of the chicks at the final day of the experiments.

7. Find the last time entry for each chick in the dataset and plot a histogram of these times.

8. Try using the package R Color Brewer to generate color palettes. Go to http://colorbrewer2.org/ to vizualize palettes. You can choose palettes that are colorblind safe, print friendly, etc.

8a. Install R Color Brewer

8b. Re-do final plot with new colors and solid lines instead of points and lines

9. Now, let's put this into R Markdown, a package that makes nice final reports of your code and figures. Go back and make sure your plots have interpretable axes labels and titles. If you're interested, change the colors and point/line types to make your figures more vizually appealing.

9a. Install R Markdown

9b. Use R Studio to create new R Markdown file with the relevant code and output that you generated above. Create an HTML document 
