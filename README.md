# airnp-analysis
## Frist step (Pre-Processing):<br>
distribute -unknown- values in gender with the same ratio on Female, male and others.<br>
Convert Columns types to correct types:<br>
Convert date & time columns<br>
Convert Categorical columns<br>
solution of inaccurate values in age:<br>
      Drop null values in first-affliate-tracked<br>
      fill null values in age with median and Convert age type into integer<br>
Generate new columns<br>
Replace missing values with mode<br>
## Correlation:<br>
    overlay histogarm: ( timestamp_first_active , date_account_created and date_first_booking )
    Correlation matrix(how features are alike or similar to each other)  <br>
## Visualizations:<br>
    Pie Charts:<br>
      signup_app pie chart<br>
      gender pie chart<br>
      signup_method pie chart<br>
      first_affiliate_tracked pie chart<br>
## Bar Plot:<br>
      first_browser bar plot<br>
      Most signup_flow: the page a user came to signup up from<br>
      Top Booked Countries over years<br>
      language bar plot<br>
      almost all users language is English<br>
      first_device_type bar plot<br>
      country_destination bar plot<br>
## Scatter Plot:<br>
       signup_flow with age<br>
## Heat Map:<br>
       first_device_type with country_destination<br>
       age with country_destination<br>
       first_device_type with first_browser<br>
       affiliate_channel with affiliate_provider<br>
       signup_method with gender<br>
       gender with country_destination<br>
## Tree Map:<br>
       gender => country_destination => language<br>
       country_destination => gender => signup_method<br>
## Time Series analysis:<br>
       using Prophet library for predicting the next year (365 days )<br>
## Machine learning model :<br>
        (XGBOOST)
        accuracy =87% 


       
