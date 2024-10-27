![The She Codes Logo](../../global_images/logo.png)

# Django Rest Framework Project: Crowdfunding App (Part 1)<br><sub><sup><sub>Due: Last Sunday of the module at 11:59pm.</sub></sup></sub>

## Project Description
Kickstarter, Go Fund Me, Kiva, Change.org, Patreon… All of these different websites have something in common: they provide a platform for people to fund projects that they believe in, but they all have a slightly different approach. You are going to create your own crowdfunding website, and put your own spin on it!

## Project Requirements
Your crowdfunding project must:

- [ yes] Be separated into two distinct projects: an API built using the Django Rest Framework and a website built using React. 
- [ yes] Have a cool name, bonus points if it includes a pun and/or missing vowels. See https://namelix.com/ for inspiration. <sup><sup>(Bonus Points are meaningless)</sup></sup>
- [ yes] Have a clear target audience.
- [ yes] Have user accounts. A user should have at least the following attributes:
  - [ yes] Username
  - [ yes] Email address
  - [ yes] Password
- [ yes] Ability to create a “project” to be crowdfunded which will include at least the following attributes:
  - [ yes] Title
  - [ yes] Owner (a user)
  - [ yes] Description
  - [ yes] Image
  - [ yes] Target amount to fundraise
  - [ yes] Whether it is currently open to accepting new supporters or not
  - [ yes] When the project was created
- [yes ] Ability to “pledge” to a project. A pledge should include at least the following attributes:
  - [ yes] An amount
  - [ yes] The project the pledge is for
  - [ yes] The supporter/user (i.e. who created the pledge)
  - [ yes] Whether the pledge is anonymous or not
  - [ ] A comment to go along with the pledge
- [yes ] Implement suitable update/delete functionality, e.g. should a project owner be allowed to update a project description?
- [ yes] Implement suitable permissions, e.g. who is allowed to delete a pledge?
- [ yes] Return the relevant status codes for both successful and unsuccessful requests to the API.
- [ yes] Handle failed requests gracefully (e.g. you should have a custom 404 page rather than the default error page).
- [ yes] Use Token Authentication, including an endpoint to obtain a token along with the current user's details.
- [ yes] Implement responsive design.

## Additional Notes
No additional libraries or frameworks, other than what we use in class, are allowed unless approved by the Lead Mentor.

Note that while this is a crowdfunding website, actual money transactions are out of scope for this project.

## Submission
To submit, fill out [this Google form](https://forms.gle/34ymxgPhdT8YXDgF6), including a link to your Github repo. Your lead mentor will respond with any feedback they can offer, and you can approach the mentoring team if you would like help to make improvements based on this feedback!

Please include the following in your readme doc:
- [yes ] A link to the deployed project.
- [ yes] A screenshot of Insomnia, demonstrating a successful GET method for any endpoint.
- [ yes] A screenshot of Insomnia, demonstrating a successful POST method for any endpoint.
- [yes ] A screenshot of Insomnia, demonstrating a token being returned.
- [ yes] Step by step instructions for how to register a new user and create a new project (i.e. endpoints and body data).
- [ yes] Your refined API specification and Database Schema.