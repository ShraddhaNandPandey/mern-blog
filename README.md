# MERN Blog

**MERN Blog** is a full-stack blog application built with the MERN stack (MongoDB, Express, React, Node.js). This application allows users to create, read, update, and delete blog posts. It features a modern and responsive user interface and a robust backend API for handling blog data.

## Features

- **User Authentication:** Secure user login and registration.
- **CRUD Operations:** Create, read, update, and delete blog posts.
- **Responsive Design:** Mobile-friendly user interface.
- **API Integration:** RESTful API for blog operations.
- **Data Persistence:** MongoDB database for storing blog posts and user data.

## Installation

### Prerequisites

- Node.js and npm installed.
- MongoDB installed and running.

### Backend Setup

1. **Clone the repository:**

    ```bash
    git clone https://github.com/ShraddhaNandPandey/mern-blog.git
    ```

2. **Navigate to the backend directory:**

    ```bash
    cd mern-blog/backend
    ```

3. **Install backend dependencies:**

    ```bash
    npm install
    ```

4. **Create a `.env` file in the backend directory** and add the following environment variables:

    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

5. **Start the backend server:**

    ```bash
    npm start
    ```

### Frontend Setup

1. **Navigate to the frontend directory:**

    ```bash
    cd ../frontend
    ```

2. **Install frontend dependencies:**

    ```bash
    npm install
    ```

3. **Start the frontend server:**

    ```bash
    npm start
    ```

4. **Open your browser** and go to `http://localhost:3000` to view the application.

## Usage

- **Register or log in** to access the blog features.
- **Create new blog posts** using the provided form.
- **Edit or delete** existing posts from the dashboard.
- **View posts** on the main page and read individual articles.

## Contributing

We welcome contributions to improve the application. To contribute:

1. **Fork the repository.**
2. **Create a new branch** for your changes:

    ```bash
    git checkout -b feature/your-feature
    ```

3. **Make your changes and commit them:**

    ```bash
    git commit -am 'Add new feature'
    ```

4. **Push your changes to your fork:**

    ```bash
    git push origin feature/your-feature
    ```

5. **Open a pull request** on the original repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or feedback, please reach out to [Shraddha Nand Pandey](mailto:your-email@example.com).
