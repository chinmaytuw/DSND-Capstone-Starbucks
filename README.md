# Data Science NanoDegree - Capstone - Starbucks

# Introduction:
- This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

- Not all users receive the same offer, and that is the challenge to solve with this data set.

- Thee task is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type.

- We will create a ML model that learns from historical data and helps the business predict whether or not a particular user will be influenced by an offer and end up completing it.

# Libraries:
1. pandas
2. numpy
3. sklearn
4. seaborn
5. matplotlib

# Files:

      - data
      |- portfolio.json  # json with offer data
      |- profile.json    # json with user data
      |- transcript.json.zip # zip with data for transactions
      
      - images # images used in the notebook

      - Starbucks_Capstone_notebook.ipynb # Notebook with all the code and analysis.

      - README.md

# Summary:
- The final recall score for the model was 82%. 
- [Here](https://chinmaytuw.medium.com/udacity-data-science-nanodegreee-capstone-starbucks-beb343e05ae9) is a Medium blogpost with detailed analysis.
