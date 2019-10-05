# Dining-Concierge-Agent
Project Assignment -- COMSE6998 Cloud Computing and Big Data <br>
https://sc4400-demo.s3.amazonaws.com/index.html


## Built With
- S3 - Used to host static frontend
- API Gateway - For deploying, monitoring, and securing REST APIs.
- Lambda - Acted as backend to run code without provisioning or managing servers.
- Lex - Used to build chat bots.
- Yelp API - Scratch restaurant information based on certain criterion.

## Architecture
![architecture](https://user-images.githubusercontent.com/43797430/66260983-f9e11f80-e793-11e9-8720-5621f2e8a456.jpg)

## Example Interatction
* User: Hi
* Bot: Hi there, how can I help?
* User: I need some restaurant suggestions.
* Bot: Great. I can help you with that. What city or city area are you looking to dine in?
* User: Manhattan
* Bot: What cuisine would you like to try?
* User: Japanese
* Bot: Ok, how many people are in your party?
* User: Two
* Bot: A few more to go. What date?
* User: Today
* Bot: What time?
* User: 12:00pm
* Bot: My Japanese place suggestions for 2 people on 2019-10-05 at 12:00 in Manhattan: 1. Ootoya Chelsea located at 8 W 18th St. 2. Izakaya MEW located at 53 W 35th St. 3. nonono located at 118 Madison Ave. Enjoy your meal!
* User: Thank you!
* Bot: You are welcome! Thanks for using the service. See you next time!
