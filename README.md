Pandas-challenge

Please see my Pandas-challenge homework. I utilized a tutor for some errors I was having. I learned that it was just type errors, when I created my dataframe I like to have it look pretty so I formatted everything and when I did that it converted my results into strings. To remedy this I created copys for the formatted results to keep a copy of the raw data for further manipulation. 


You will see the below warning in my code, after speaking with my instructor he advised that this is just a warning that the version will be deprecated but will not affect my code. 

> C:\Users\zenob\AppData\Local\Temp\ipykernel_16532\3364004365.py:3: FutureWarning: The default of observed=False is deprecated and will be changed to True in a future version of pandas. Pass observed=False to retain current behavior or observed=True to adopt the future default and silence this warning.
  spending_math_scores = school_spending_df.groupby(["Spending Ranges (Per Student)"])["Average Math Score"].mean()
C:\Users\zenob\AppData\Local\Temp\ipykernel_16532\3364004365.py:4: FutureWarning: The default of observed=False is deprecated and will be changed to True in a future version of pandas. Pass observed=False to retain current behavior or observed=True to adopt the future default and silence this warning.
  spending_reading_scores = school_spending_df.groupby(["Spending Ranges (Per Student)"])["Average Reading Score"].mean()
C:\Users\zenob\AppData\Local\Temp\ipykernel_16532\3364004365.py:5: FutureWarning: The default of observed=False is deprecated and will be changed to True in a future version of pandas. Pass observed=False to retain current behavior or observed=True to adopt the future default and silence this warning.
  spending_passing_math = school_spending_df.groupby(["Spending Ranges (Per Student)"])["% Passing Math"].mean()
C:\Users\zenob\AppData\Local\Temp\ipykernel_16532\3364004365.py:6: FutureWarning: The default of observed=False is deprecated and will be changed to True in a future version of pandas. Pass observed=False to retain current behavior or observed=True to adopt the future default and silence this warning.
  spending_passing_reading = school_spending_df.groupby(["Spending Ranges (Per Student)"])["% Passing Reading"].mean()
C:\Users\zenob\AppData\Local\Temp\ipykernel_16532\3364004365.py:7: FutureWarning: The default of observed=False is deprecated and will be changed to True in a future version of pandas. Pass observed=False to retain current behavior or observed=True to adopt the future default and silence this warning.
  overall_passing_spending = school_spending_df.groupby(["Spending Ranges (Per Student)"])["% Overall Passing"].mean()
