# pandas-challenge

# https://stackoverflow.com/questions/30503321/finding-count-of-distinct-elements-in-dataframe-in-each-column, Site design / logo 2023 Stac Exchange Inc; user contributions licensed under CC BY-SA rev 2023.11.13.870 -- used to understand the "nunique" method.

# https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.cut.html, PyData Sphinx Theme 0.13.13, instructor Matt Bosworth demonstrated how referencing pandas.org and understanding what goes into making each function operate correctly can help answer your own question when the results from your code are not formatting or working properly.

# referenced class assignments - 
# 05-Ins_DataFunctions
# 07-Ins_ColumnManipulation
# 10-Stu_ComicBooksCSV
# 01-Ins_LocAndIloc
# 02-Stu_GoodMovies-Loc
# 07-Par_Census-GroupBy
# 09-Stu_SearchForTheWorst
# 02-Stu_Census-Merging
# 04-Stu_MovieRatings-Binning
# 06-Stu_CleaningCrowdfunding

# Contacted AskBCS Learning Assistant 4 times with the following questions:
# 1 - I was attempting to do a grouby when calculating the total budget, thinking I'd need to distinguish each school and the budget separately first, then add up their individual budgets to avoid repettive values from adding since each school was listed multiple times. JCHOI showed me how I could just reference the CSV file that lists the budget for each individual school instead of the dataframe that was created.
# 2 - Siphe helped me understand what the portion "(["school_name"])["budget"]" in my syntax did and how it grouped each school name first, then told the code to look at the budget column for each school.
# 3 - Robert demonstrated over a Zoom call how I had referenced a value that was pulling in a string variable, and I instead needed to go higher in my previous code to reference the correct value.
# 4 - Robert demonstrated over a Zoom call that a previous value I had referenced was causing an issue down the line in my code, causing an "int" and "str" error.