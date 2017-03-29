# nicochain
Insurance Blockchain platform for small wearables and smart companions such as smartphones and smart watches

## Scope
* Write a 1 page spec about the business and technical challenge
* MVP of a smart contract on ethereum
* Simple risk model 
* UI/UX for a mobile/web app (mockups are fine)

### Simple risk model
A very simple (probably hardcoded) model. Example:
* Wearable value: W
* Premium: W * X%
* Insurance amount: W * Y%
* Claim probability:  Z %

Simple meaning it estimates different price of insurance for different risk profiles based on 3-5 data inputs like age, gender, phone model, location, # of friends or calls movements,  installed apps - anything that can make the risk (and as a result - cost of insurance premium) higher or lower for different people.
It should predict the risk of loss better than random dice rolling

Start with the simplest possible model and then grow to different models.
