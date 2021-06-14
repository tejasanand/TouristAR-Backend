# Tourist-AR

## Inspiration

Humans are inquisitive beings who love travelling and marvelling different tourist attractions and museums around the world. The global lockdowns have created a condition unlike other ever seen by us which curtails our liberty to discover different places around the world. Moreover, 2d images don't do much justice in giving the scale and details of a specific location or famous item. Stemming from this problem, we decided to create an Augmented Reality App where the user can experience different monuments/museum-installations etc. in 3d from the comfort of their homes.

## What it does

Powered by the nearly unlimited models of EchoAR, our mobile web application brings a travel destination/museum experience to your phone. The user can log into their customised accounts and search for different locations/museums/monuments around the world and view them in real world through the camera of their phones. Moreover, we are using an Artificial Intelligence algorithm to guide the user with their searches and recommend them related location/monuments etc. so they can view similar places around the world just by a click on their phones. The Artificial Intelligence algorithm provides similar search items to the user and enhances the user experience.

## How we built it

We created the mobile application using React Native which enables us to publish the app on iOS and Android simultaneously. The database was supported by Linode database service to store user accounts, different locations, models at a location and link on EchoAR server to display the model. As mentioned, we are using EchoAR's server power and 3d model rendering to integrate and display the models in our application to create the main Augmented Reality experience.
For the backend, we are using Flask(python) to process the data fetched and store the data processed by the database.
Moreover, we have Artificial Intelligence/Machine Learning algorithm (using 'k-nearest neighbour' strategy) to optimise the search of different locations. It provides the user with similar locations based on the keywords he has entered, thereby, enhancing the user experience.

## Challenges we ran into

- None of the members had used AR before but we were keen on learning it. Although we were quite skeptical about it as if we weren't able to learn to use it, then the whole project would come crashing down. But, luckily, we divided up learning AR equally among the team member & the EchoAR workshop at the hackathon also helped us kickstart our very first Augmented Reality Application.
- Another challenge that we face was to enhance the search using Artificial Intelligence algorithm. We wanted this to be a part of our app's search result to make the user's experience better and build an app closer to the production level. 2 of the members were versed in the field of AI and looked intensively at research papers and dived deep into the field just to enhance the user experience to produce more relevant search results. The other 2 members also looked into the problem to expose themselves to the field and contribute their valuable input. Finally, we found a suitable strategy(k nearest neighbour strategy) and implemented it successfully.

## Accomplishments that we're proud of

- The application as a whole is something that the whole team is quite proud of but the following are the specific items where our pride is at it's peak:

1. Implementing a completely new and high-demand technology - Augmented Reality. We all have built a new skill of uplifting the user from the world to 2d to a more rich 3d experience.
2. Keeping the user experience in paramount, we implemented a complex Artificial Intelligence/Machine Learning algorithm to provide relevant search results.
3. Successfully integrating the backend, frontend & database of the application to create the project as a full stack application.

## What we learned

Tech Skills-

1. Highly in-demand technology - Augmented Reality and it's different use cases.
2. k-nearest strategy AI/ML algorithm.

Soft Skills-

1. Collaborating in a team in a time sensitive environment.
2. Maintaining the team productive even if everyone is in different timezones of the world.
3. Valuing technical capabilities more than hardship of picking up a new skill.

## What's next for Tourist AR

- Add more data/models for different locations throughout the world. Moreover, create a creator's account where creators can add models and description of a location themselves.
- Create a more life like experience by adding the functionality of a map where user chooses a specific point inside a location and is lead to that model. For example, user is given a map of a museum and they select the location inside the museum(like, second floor's entrance) and they are presented with the models kept at that location.

## Judging Criteria

- Problem Solving: People not able to immerse themselves with different locations and experience them in 3d is a real problem that deprives humans from recreational and educational activities.
- Development Complexity: The app is quite complex as it is a full stack iOS/Android application with a functional Frontend, Backend & Database. Along with that it uses complex technologies like Artificial Intelligence and Augmented Reality.
- Aesthetics: User experience, UI and aesthetics have been the paramount aspect of our project. We believe that a happy user accounts for a successful project which we strived for.
- Presentation: As a team, we have put a whole lot of effort in the presentation aspect of the project as well. (Describing the devpost robustly, creating a descriptive video and explaining everything in the Readme of the project)

1. [Front-end GitHub repository (using React Native)](https://github.com/AdityaGoyal1999/Tourist-AR)
2. [Back-end GitHub repository (using Flask)](https://github.com/TejasAnand/TouristAR-Backend)
