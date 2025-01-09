# Netflix Clone

**Netflix Clone** is a React app with a landing page, authentication, and sections for Movies, TV Shows, and Search History management.

## Features
- Landing page for user engagement.
- User authentication for secure access.
- Sections for:
  - **Movies**: Browse and view movies.
  - **TV Shows**: Explore popular TV shows.
  - **Search History**: Search for movies, TV shows, and actors, with the ability to browse and delete search history.
- Fully responsive design for all devices.

## Tech Stack
- **Frontend**: React
- **Backend**: Node.js, Express
- **Database**: MongoDB

## Dependencies
### Core Dependencies
- **axios**: For making API requests.
- **bcryptjs**: For hashing passwords securely.
- **cookie-parser**: For parsing cookies used in authentication.
- **dotenv**: For managing environment variables securely.
- **express**: A web application framework for handling routes and API requests.
- **jsonwebtoken**: For secure authentication via tokens.
- **mongoose**: An ODM (Object Data Modeling) library for MongoDB, used to interact with the database.

### DevDependencies
- **cross-env**: Allows setting environment variables across platforms.
- **nodemon**: Automatically restarts the server when file changes are detected during development.

## Scripts
- **`dev`**: Runs the application in development mode with `nodemon`, allowing auto-restart on file changes.
  ```bash
  cross-env NODE_ENV=development nodemon backend/server.js
  ```
- **`start`**: Runs the application in production mode.
  ```bash
  cross-env NODE_ENV=production node backend/server.js
  ```
- **`build`**: Installs dependencies for both backend and frontend and builds the frontend.
  ```bash
  npm install && npm install --prefix frontend && npm run build --prefix frontend
  ```

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/username/netflix-clone.git
   ```
2. Navigate to the project directory:
   ```bash
   cd netflix-clone
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the application in development mode:
   ```bash
   npm run dev
   ```

## Folder Structure
- **backend**: Contains server-side code (Express and MongoDB).
- **frontend**: Contains client-side code (React).

## License
This project is licensed under the ISC License.

