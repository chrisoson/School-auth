To start the project: Check the README for the API to see how to set up the database and start it.

To start the Angular project, navigate to the project in the terminal and run:

ng serve

To start the vanilla project, simply open the index.html file in a live server.

Reflection on Choosing Angular
I chose to challenge myself by not only doing the project in regular JavaScript but also building it in Angular, which I have been experimenting with outside of school. There was a lot to learn, but I’ve gained a lot of knowledge this week because of it. I could write extensively about my experience, but it would be too long, so instead, I’ve added comments in my code to explain how certain things work in Angular.

Why Angular?
I chose to work with Angular instead of something like React because I find Angular more structured. It's not as flexible as React, where you can organize the project in almost any way you want. I like that Angular is more "opinionated," as I believe it prevents things from becoming chaotic when there are no set guidelines. Personally, I also find Angular more readable and easier to understand, partly due to its syntax and partly because each component is divided into separate HTML, CSS, and TypeScript files, which makes it well-organized. Another thing I like is that Angular requires TypeScript, which is more similar to C#. Since Angular uses "dependency injection" and is more class-based in its JavaScript approach, which is a common pattern in C#, it was easier for me to grasp than React’s more functional style.

Advantages of a Framework
The biggest advantage of using a framework, in my opinion, is the component architecture that all major JavaScript frameworks use. This makes things much less chaotic as the project grows, as you can have components with their HTML, CSS, and JavaScript completely isolated and reusable. This is one of the biggest reasons frameworks exist for JavaScript, I believe.

Angular Material
I chose to use Angular Material, which is a component library similar to Bootstrap but specifically for Angular. These components follow the same style guide, allowing you to create sleek and consistent pages without designing everything yourself, which can take a lot of time to get right. Angular Material is developed by the Angular team and is not only efficient but also offers great accessibility out of the box.

Analysis and Reflection
Performance
I find performance very difficult to evaluate in this task, but I think it's important to only make API calls that are actually needed and not waste resources with unnecessary calls. Another important factor is to only fetch the data that’s required. For example, if you fetch all reviews in a large application, there will likely be a huge number of them. So, it's crucial to find a good way to fetch data in smaller chunks to maintain good performance on the page.

Scalability
I believe both my vanilla and Angular projects are fairly scalable. In the vanilla project, my API calls are divided into separate files (services), making them easy to locate. Similarly, in the Angular project, I have services for my entities, which are located in one place, making the project more scalable and organized.

Security
One thing that could have been improved here is configuring CORS to only allow access from the specific address where my frontend is hosted. While this was not part of the task, it would ensure that only this URL can make API calls to the backend, which would enhance security.

Maintainability
The maintainability of my Angular project, in particular, is strong. Components are divided into separate files, making it easier to find things, which also contributes to easier maintenance. For instance, all interfaces (models, DTOs) are located in a dedicated folder, making them easy to access and manage.
