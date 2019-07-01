# Coding Challenge “Passionate Navigation”
## Background Information
Passion.io works with various successful people from around the globe. 
They all are turned their passion into their profession in different verticals and niches.

## Task at Hand - ONLY FRONTEND / FULL-STACK POSITIONS
To structure the different verticals and niches, you will build a navigation for that with ReactJS.

Please find in the json folder 3 lists:
- 1x Verticals
- 1x Categories 
- 1x Courses

As you can see, categories have a parent called vertical and courses have a parent called categories.

**Your task is to build an UI where you can fold / unfold based on the lists with ReactJS.**

**Bonus ONLY FULL-STACK**
- Use the API oauth provider to identify your self

### Challenges you will face
- Building a tree from the lists, state management, building reusable components, building modules that consists of modules, making it visually appealing

## Task at Hand - ONLY BACKEND / FULL-STACK POSITIONS
To serve the frontend, you will build the backend for that with an API.

- Set up the models, controllers, and API
- Database: SQLite or Postgres - please provide a seed file
- Send SQS/email message on create — it could be just kinda mock
- Validate uniqueness of `Name` of `category` and `vertical` across both models (if there is a category with name "TEST" then a vertical with name "TEST" can't be valid)

**Bonus**
- Set up a oauth provider to protect the API

As you can see in the JSON folder, categories have a parent called vertical and courses have a parent called categories.

**Your task is to build a simple RESTful API with Ruby / Ruby on Rails that will be consumed by external frontend applications.**

### Challenges you will face
- Ensuring that API can be scaled and is well-tested, abstracting business logic in reusable concerns or services

## Questions 
- How does your solution perform? 
- How does your solution scale?
- What would you improve next?

## Submission Requirements
Please provide the URL(s) to your application(s) repo(s) and provide a description about your approach within a README.md.
If you do not want to host the repo, you can also email us the files.
In any case, please provide the README.md.

## Additional optional questions
- What was one of the biggest coding challenges that you ever had?
- Please show and explain why it was so difficult
