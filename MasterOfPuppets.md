# Master of Puppets

The purpose of the Master of Puppets is to allow engineers to activate or deactivate features in an application through using a nice and comfy web application.

## Terminology

- **Feature toggle**: (often also refered to as Feature Flags) are a powerful technique, allowing teams to modify system behavior without changing code. [Read More](https://martinfowler.com/articles/feature-toggles.html)

## User Stories

- As a user I am able to create a project through the Master of Puppets application. Once this is done a secret key is generated and communicated to me through the web application and/or APIs. Only the users that knows this secret can use it so that they can create, read, update and delete feature toggles on this specific project.
- As a user I want to access the list of feature toggles and their current status by providing the secret through a set of well defined APIs so that I can integrate my application at run time or my CI/CD pipelines at buildtime.
- As a user I do not have to care about the project on Master of Puppets. If the project is not accessed in more that 1 month (through both APIs or WebApp), then the project gets deleted.
- **[Senior Level]**: As a user I am able to signup and signin to the Master of Puppets web application and/or APIs so that I can safely access my profile information, and I can get a status on the resources I am managing through this system. It is no longer enough to know the secret to access and perform CRUD operation on the toggles, but access instead will have to be related to the user profiles instead.
- **[Senior Level]**: As a user I am able to get some samples on how to integrate my application to Master of Puppets so that the integration excercise I need to do at run time is simplified. As a user I can find sample for at least two technologies (as ReactJS, VueJS, Java, C#, or any others).
- **[Senior Level]**: As a user I am able to get some samples on how to integrate my CI/CD pipeline to Master of Puppets so that the integration excercise I need to do at build time is simplified. As a user I can find sample for at least two providers (as vanilla Jenkins, Travis, CircleCI, or others).
