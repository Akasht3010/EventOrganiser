# MERN Stack Application

This is a basic MERN stack application with MongoDB, Express.js, React.js, and Node.js.

## Prerequisites

- [Node.js](https://nodejs.org/) installed
- [MongoDB](https://www.mongodb.com/) installed and running

## Getting Started

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/mern-stack-app.git
    cd mern-stack-app
    ```

2. **Install Dependencies:**

    Install server-side dependencies:

    ```bash
    cd server
    npm install
    ```

    Install client-side dependencies:

    ```bash
    cd client
    npm install
    ```

3. **Set Up Environment Variables:**

    Create a `.env` file in the `server` directory and add the following:

    ```env
    PORT=3000
    MONGODB_URI=mongodb://localhost:27017/your-database-name
    ```

    Adjust the `PORT` and `MONGODB_URI` values based on your preferences and MongoDB setup.

4. **Run the Application:**

    Start the server:

    ```bash
    cd server
    npm start
    ```

    Start the React client:

    ```bash
    cd client
    npm start
    ```

    The server will run at `http://localhost:3001`, and the React app will be accessible at `http://localhost:3000`.

5. **Build for Production:**

    To build the React app for production, run the following command in the `client` directory:

    ```bash
    npm run build
    ```

    This will create a `build` folder in the `client` directory.

6. **Deploy:**

    Deploy your application to your preferred hosting service, making sure to set the appropriate environment variables for production.

## Project Structure

- `client`: React.js front-end code
- `server`: Node.js and Express.js back-end code

Feel free to modify the project structure and add additional features as needed.

## Contributing

If you'd like to contribute, please fork the repository and create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
