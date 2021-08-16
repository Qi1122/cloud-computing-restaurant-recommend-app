# cloud-computing-restaurant-recommend-app

•  Built a restaurant recommendation app using Amazon AWS with data analysis and machine learning. The backend was using Amazon cloud serverless platform to formulate an event-driven architecture, and all functions were maintained into Amazon cloud.
•  Employed React framework to focus on user interface, and deployed S3 to host and vend to users' browsers for interaction.
•  Used Amazon chatbot to provide a chat interface and analyze users’ text. Once all intents for restaurant recommendations have been fulfilled, serverless Lambda function using NodeJS would generate  an array of recommended restaurants.
•  Displayed the geo-location of the restaurants using Google map API when navigating to the frontend page, and used Yelp API to crawl 5,000+ random restaurants in Manhattan and stored into DynamoDB and ElasticSearch to query the recommended restaurants for user entered cuisine.
•  Used Cognito in the client application to provide a secure way for user to register and login, and supported to automatically send a text message or email using Amazon message queue when restaurant reservation is done by Amazon chatbot.


Vedio demo:

https://www.youtube.com/watch?v=Z-2ChCDmVXA&ab_channel=CarolineCC
