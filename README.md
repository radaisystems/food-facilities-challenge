# Food facilities backend challenge

Given the data about Mobile Food Facilities in San Francisco (https://data.sfgov.org/Economy-and-Community/Mobile-Food-Facility-Permit/rqzj-sfat/data), build an API to perform the following operations on the data set:

- Search by name of applicant. Include optional filter on "Status" field.
- Search by street name. The user should be able to type just part of the address. Example: Searching for "SAN" should return food trucks on "SANSOME ST"
- Given a latitude and longitude, the API should return the 5 nearest food trucks. By default, this should only return food trucks with status "APPROVED", but the user should be able to override this and search for all statuses.
  - You can use any external services to help with this (e.g. Google Maps API).
- For the programming languages allowed we would prefer that you use the one that was discussed with the recruiter or the hiring manager. So make sure that this is clear before you start this challenge, please :) 
- We write automated tests and we would like you to do so as well.

**Bonus points:**

- Use an API documentation tool
- Provide a dockerfile with everything necessary to run your application

## README

Your code should include a README file including the following items:

- Description of the problem and solution;
- Reasoning behind your technical/architectural decisions
- Critique section:
  - What would you have done differently if you had spent more time on this?
  - What are the trade-offs you might have made?
  - What are the things you left out?
  - What are the problems with your implementation and how would you solve them if we had to scale the application to a large number of users?
- Please document any steps necessary to run your solution and your tests.
- Please indicate the amount of time you spent on the project

## How we review

We value quality over feature-completeness. It is fine to leave things aside provided you call them out in your project's README.
The aspects of your code we will assess include:

- Clarity: does the README clearly and concisely explains the problem and solution? Are technical tradeoffs explained?
- Correctness: does the application do what was asked? If there is anything missing, does the README explain why it is missing?
- Code quality: is the code simple, easy to understand, and maintainable? Are there any code smells or other red flags? Does object-oriented code follows principles such as the single responsibility principle? Is the coding style consistent with the language's guidelines? Is it consistent throughout the codebase?
- Security: are there any obvious vulnerabilities?
- Technical choices: do choices of libraries, databases, architecture etc. seem appropriate for the chosen application?
