# Media Guide

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)
![GitHub Issues](https://img.shields.io/github/issues/yourusername/movie-catalog.svg)
![GitHub Stars](https://img.shields.io/github/stars/yourusername/movie-catalog.svg)

A simple and intuitive open-source movie catalog application that allows users to manage their movie collections efficiently. Users can add movies manually or upload them via CSV files, organize them into watched, unwatched, and custom lists, and enjoy a seamless experience across devices.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
  - [Prerequisites](#prerequisites)
  - [Backend Setup](#backend-setup)
  - [Frontend Setup](#frontend-setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **User Authentication (Optional):** Secure user accounts to manage personal movie catalogs.
- **Movie Management:**
  - **Add Movies:** Easily add movies manually or upload a CSV file.
  - **Edit/Delete Movies:** Manage and update your movie entries.
- **Metadata Handling:** Store comprehensive details such as title, genre, release year, director, ratings, and more.
- **Organize into Lists:**
  - **Default Lists:** Categorize movies as Watched or Unwatched.
  - **Custom Lists:** Create and manage personalized categories.
- **Search and Filtering:** Quickly find movies based on various criteria like title, genre, or director.
- **Responsive Design:** Access your catalog seamlessly on desktops, tablets, and mobile devices.
- **Import/Export:** Import movies from other sources or export your catalog for backup.

## Demo

![Movie Catalog Demo](./assets/demo-screenshot.png)

*Screenshot of the Movie Catalog application showcasing the main interface.*

## Technologies Used

### Frontend

- **React:** Building dynamic user interfaces.
- **Material-UI:** Pre-designed UI components for a polished look.
- **Axios:** Handling HTTP requests.
- **React Router:** Managing navigation within the app.

### Backend

- **Node.js & Express:** Building a scalable server.
- **MongoDB & Mongoose:** Managing the database with a flexible schema.
- **JWT (JSON Web Tokens):** Securing user authentication.
- **Multer & csv-parser:** Handling file uploads and CSV parsing.

### Deployment

- **Frontend:** Vercel or Netlify
- **Backend:** Heroku, Render, or DigitalOcean
- **Database:** MongoDB Atlas

## Installation

### Prerequisites

- **Node.js:** Ensure you have Node.js installed. [Download Node.js](https://nodejs.org/)
- **npm or Yarn:** Package manager for installing dependencies.
- **MongoDB Account:** For hosting your database. [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)

### Backend Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/media-guide-v1.git
   cd media-guide-v1/backend
   ```

2. **Install Dependencies:**

   ```bash
   npm install
   ```

3. **Configure Environment Variables:**

   Create a `.env` file in the `backend` directory and add the following:

   ```env
   PORT=5000
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. **Start the Backend Server:**

   ```bash
   npm start
   ```

   The backend server should now be running on `http://localhost:5000`.

### Frontend Setup

1. **Navigate to Frontend Directory:**

   ```bash
   cd ../frontend
   ```

2. **Install Dependencies:**

   ```bash
   npm install
   ```

3. **Configure Environment Variables:**

   Create a `.env` file in the `frontend` directory and add the following:

   ```env
   REACT_APP_API_URL=http://localhost:5000/api
   ```

4. **Start the Frontend Application:**

   ```bash
   npm start
   ```

   The frontend application should now be running on `http://localhost:3000`.

## Usage

1. **Register an Account (Optional):**

   - Navigate to the registration page to create a new account.
   - Log in using your credentials.

2. **Add Movies:**

   - **Manual Entry:** Use the "Add Movie" form to input movie details.
   - **CSV Upload:** Upload a CSV file containing your movie list.

3. **Organize Movies:**

   - **Default Lists:** Mark movies as Watched or Unwatched.
   - **Custom Lists:** Create custom categories to organize your movies.

4. **Search and Filter:**

   - Use the search bar to find movies by title, genre, or director.
   - Apply filters to narrow down your movie list based on various criteria.

5. **Manage Your Catalog:**

   - Edit or delete movie entries as needed.
   - Export your movie list for backup or sharing purposes.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

### Steps to Contribute

1. **Fork the Project:**

   Click the "Fork" button at the top right of the repository page.

2. **Clone Your Fork:**

   ```bash
   git clone https://github.com/yourusername/movie-catalog.git
   cd movie-catalog
   ```

3. **Create a New Branch:**

   ```bash
   git checkout -b feature/YourFeatureName
   ```

4. **Make Your Changes:**

   Implement your feature or bug fix.

5. **Commit Your Changes:**

   ```bash
   git commit -m "Add some feature"
   ```

6. **Push to Your Fork:**

   ```bash
   git push origin feature/YourFeatureName
   ```

7. **Open a Pull Request:**

   Go to the original repository and click "Compare & pull request."

### Guidelines

- **Code Quality:** Ensure your code is clean, well-documented, and follows the project's coding standards.
- **Commit Messages:** Write clear and descriptive commit messages.
- **Testing:** If applicable, add tests to cover your changes.
- **Respect the Project:** Be considerate and respectful in all interactions.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this project as per the terms of the license.

## Contact

If you have any questions, suggestions, or feedback, feel free to reach out!

- **GitHub:** [yourusername](https://github.com/yourusername)
- **Email:** your.email@example.com

---

*Happy Cataloging! 🎬🍿*