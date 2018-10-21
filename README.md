# boilermakebrownies

Our team for boilermake6 is comprised of 1 second year pre-med student, 2 seniors completing their bachelors in Computer Science, and 1 software engineer completing his masters in Computer Science.

The project is a simple voting app. It is hosted live [here](https://ilmstudios.github.io/boilermakebrownies/).

A user can sign-up for a voting session, entering in some simple demographic data. A user can initiate a new vehicle pair to vote against from the menu or on the home screen. The vehicles are pulled on the fly from the Liberty Mutual Shine API. Some sample stats are shown on the compare page. The data pulled from Liberty Mutual is then run against Bing Image Search to pull the first result to display. The user can then vote for either vehicle, which gets saved to MongoDB. The vote feed page shows current votes in the system for vehicle compares. Other users can then add their vote. The plan with aggregating the demographics would be to show a demographics report based on the vehicles chosen.

We've divvied up the tasks as external API wrangler, 2 frontend devs, 1 devops/backend.

We are using Angular 7, MongoDB Stitch, Librerty Mutual Shine API, and Bing Image Search API.

We've structured our Angular application into components, services, modules, and models.

We followed MongoDB's Stitch's templates for database rules.

We're using Firebase/GCP for hosting.

## Mockups

Registration:
![image](https://user-images.githubusercontent.com/29419183/47252363-6c38e280-d411-11e8-839d-295e26b0fe1c.png)

Login:
![image](https://user-images.githubusercontent.com/29419183/47252368-7f4bb280-d411-11e8-843e-53b56531f9d8.png)


## Requirements
* A user should be able to sign up for the application, providing demographic data.
* A non authenticated user should see a list of previously voted items.
* An authenticated user should be able to vote on a new vehicle comparison.
* An authenticated user should be able to vote on an already existing comparison.

## Coding Guide
* Always run code before pushing to remote, do not push broken code.
* Follow the folder structure given for front end development.

## Final Screens

![image](https://user-images.githubusercontent.com/29419183/47263427-89cc8180-d4cf-11e8-98b1-da149a191683.png)

![image](https://user-images.githubusercontent.com/29419183/47263431-981a9d80-d4cf-11e8-945a-371ad614f946.png)

![image](https://user-images.githubusercontent.com/29419183/47263438-a23c9c00-d4cf-11e8-8ef3-c62b3faacd05.png)

![image](https://user-images.githubusercontent.com/29419183/47263440-b385a880-d4cf-11e8-9e1d-f274c36bcd58.png)

![image](https://user-images.githubusercontent.com/29419183/47263445-d44dfe00-d4cf-11e8-9ca4-e7ed6b16a245.png)

