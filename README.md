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
* Bot: Got it, Manhattan. What cuisine would you like to try?
* User: Japanese
* Bot: Ok, how many people are in your party?
* User: Two
* Bot: A few more to go. What date?
* User: Today
* Bot: What time?
* User: 12:00pm
* Bot: Here are my Japanese restaurant suggestions for 2 people, for today at 7 pm: 1.
Sushi Nakazawa, located at 23 Commerce St, 2. Jin Ramen, located at 3183 Broadway,
3. Nikko, located at 1280 Amsterdam Ave. Enjoy your meal
* User: Thank you!
* Bot:
