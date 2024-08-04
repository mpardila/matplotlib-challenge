# matplotlib_challenge

I checked on the Xpert Learning Assistant how to drop the duplicate mice ID and found this syntax: cleaned_df = df.drop_duplicates(subset=['Mouse ID', 'Timepoint'], keep='first').

I checked on the Xpert Learning Assistant for the syntaxis in Panda for variance, standard deviation, and SEM.

I checked on the Xpert Learning Assistant to get additional variables in the plots to make them look like the ones in the starter quote. For example: plt.boxplot how to make the outliers red dots.

I used Claude AI to understand better the "Generate a scatter plot of mouse weight vs. the average observed tumor volume for the entire Capomulin regimen" exercise.

Matt helped me understand what was wrong with the last (greatest) timepoint for each mouse df. When I filtered by Timepoint = 45, my df had only 63 rows, not 249.

I used Claude AI to better understand how to interpret the mean, median, variance, standard deviation, and SEM of the different drugs. I ended up finding the Relative Standard Error (RSE) or Coefficient of Variation of the Mean to express the SEM as a percentage and interpret the variability relative to the mean.
