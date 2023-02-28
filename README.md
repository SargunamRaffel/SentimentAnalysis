# Description              

In this Module, I will show you how to integrate sentiment analysis in your Mendix using a REST API. This helps us to easily analyze user feedback and confidence level.

# Dependencies:·       

Mendix Modeler 9.12.0·        

API Layer (https://apilayer.com/)- API Key

# Configuration:


· Create an account on the API Layer (https://apilayer.com/ ) and subscribe to the Sentiment Analysis API from the API Layer marketplace (https://apilayer.com/marketplace/sentiment-api) 

· Collect the API Key for your API Layer account

· Add the API Key value to the constant APIKey from the module

· Run the application and navigate to the SentimentAnalysis_Overviewpage

· Click the SendMessage button, the User can enter feedback when clicking the send button

. This will trigger the REST API to analyze the user emotion and it will respond with the status (positive, negative, neutral) and confidence level with percentage.

· You can also keep this status in your application for admin-level review.

· Finally, You can view the User emotion in the SentimentAnalysis_Overviewpage
