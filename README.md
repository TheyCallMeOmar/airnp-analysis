# airnp-analysis
Frist step (Pre-Processing):<br>
distribute -unknown- values in gender with the same ratio on Female, male and others.
Convert Columns types to correct types:
Convert date & time columns
Convert Categorical columns
solution of inaccurate values in age:
      Drop null values in first-affliate-tracked
      fill null values in age with median and Convert age type into integer
Generate new columns
Replace missing values with mode
Correlation:
    overlay histogarm: ( timestamp_first_active , date_account_created and date_first_booking )
    Correlation matrix(how features are alike or similar to each other)  
Visualizations:
    Pie Charts:
      signup_app pie chart
      gender pie chart
      signup_method pie chart
      first_affiliate_tracked pie chart
Bar Plot:
      first_browser bar plot
      Most signup_flow: the page a user came to signup up from
      Top Booked Countries over years
      language bar plot
      almost all users language is English
      first_device_type bar plot
      country_destination bar plot
Scatter Plot:
       signup_flow with age
Heat Map:
       first_device_type with country_destination
       age with country_destination
       first_device_type with first_browser
       affiliate_channel with affiliate_provider
       signup_method with gender
       gender with country_destination
Tree Map:
       gender => country_destination => language
       country_destination => gender => signup_method
Time Series analysis:
       using Prophet library for predicting the next year (365 days ) 
Machine learning model :
        (XGBOOST)
        accuracy =87% 


       
