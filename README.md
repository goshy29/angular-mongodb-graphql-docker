# Angular Project + MongoDB + GraphQL with Docker
## Project Description:
This Full-Stack Project which I called Cake World with Angular frontend with an Express.js backend, MongoDB database, and GraphQL API for efficient data handling. Тhe purpose of this application is to share a recipe of your favorite cake, which recipe will be posted at the Blog from the Menu and saved in MongoDB. Information at the Blog includes a title, user name, email and recipe. The application allows you to delete someones blog. Also you will find Cakes from the menu where you can read some interesting articles about desserts which are in-memory loaded. With Docker Compose, this project provides a convenient setup and deployment process, letting you start the application in seconds.

## Features:
1. Responsive Design: The application is fully responsive, ensuring an optimal viewing experience across a wide range of devices, from desktops to mobile phones.
2. Full-Stack Architecture: Combines a Angular frontend, Express.js backend, MongoDB database, and GraphQL for API queries.
3. GraphQL API: Enables flexible and efficient data querying for the frontend.
4. Containerized Deployment: Runs Docker containers for frontend, backend and MongoDB, streamlining development and deployment.
5. Blog: Allows users to post recipes with title, user details, and the recipe itself. Provides functionality to delete blog posts.
6. In-Memory Articles: Displays articles about desserts that are in-memory loaded for quick access.

## Technologies Used:
1. Frontend: Angular, HTML, CSS.
2. Backend: Node.js, Express.js, GraphQL.
3. Database: MongoDB, Mongoose.
4. State Management: Angular Services.
5. Routing: Angular Router.
6. Containerization: Docker, Docker Compose.
7. Version Control: Git, GitHub.

## Project Structure:
Frontend: Contains all Angular components and frontend logic.
  1. Components: Components(some of them reusable) for different sections of the project, including Menu.
  2. Pages: Separate pages for Home, Cakes, Blog and Share Recipe.

Backend: Contains Express.js server-side code, GraphQL API logic, and database management.
  1. GraphQL Schema: Defines types and operations for querying and mutating data.
  2. Resolvers: Implements logic for each GraphQL query and mutation.
  3. Models: Define the MongoDB schemas using Mongoose.
  4. Config: Configuration files, including database connection settings.

## To run this project locally with Docker Compose, follow these steps:
1. GitHub: https://github.com/goshy29/angular-mongodb-graphql-docker
2. Clone the repository: https://github.com/goshy29/angular-mongodb-graphql-docker.git
3. Open the project with your code editor(VS Code) and open New Terminal
4. Ensure Docker is installed on your computer and running
5. Start the services in detached mode: docker-compose up -d
6. Open the application in your browser: http://localhost:4200
7. To stop services without removing volumes: docker-compose down
8. To stop and remove volumes (for a fresh start): docker-compose down -v

## Example Data to Enter in the User Form: 
1. title: Fig, nut & seed bread with ricotta & fruit
2. name: John Doe
3. email: johndoe@gmail.com
4. recipe: This healthy loaf is closer to banana bread than traditional cake. It's made with dried figs, sultanas, oats, nuts, seeds and black tea, all of which provide a natural boost of energy. Heat oven to 170C/150C fan/gas 3½. Pour the tea into a large bowl and stir in the figs, sultanas and oats. Set aside to soak. Meanwhile, line the base and sides of a 1kg loaf tin with baking parchment. Mix together the flour, baking powder, nuts and seeds. Beat the egg into the cooled fruit mixture, then stir the dry ingredients into the wet. Pour into the tin, then level the top and scatter with the extra nuts and sesame seeds.
