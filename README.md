# Online-Quiz-Exam-Generator

This is an Quiz Exam Generator System designed to facilitate exam creation, administration, and result analysis. It provides separate interfaces for both users and administrators, along with real-time updates, JWT authentication, and more.

## Features

1. **Complex MongoDB Queries, Schemas, and Models**: Utilizes MongoDB for efficient data storage, with complex queries, schemas, and models optimized for exam management.

2. **Separate User Interfaces**: Offers distinct interfaces tailored for users and administrators, ensuring a seamless experience for both parties.

3. **JWT Authentication and Password Hashing**: Implements JWT authentication for secure user sessions, coupled with password hashing to safeguard user credentials.

4. **Admin Functionality**: Administrators can effortlessly add exams with questions, options, and answers, empowering them to manage exam content efficiently.

5. **Real-time Updates**: Enables real-time updates for all CRUD operations within the Questions and Exams modules, ensuring data accuracy and immediacy.

6. **Timer Functionality**: Incorporates timer functionality for exam sessions, allowing users to track their progress and adhere to time constraints.

7. **Live Result Generation**: Provides live result functionality immediately after exam completion, offering users instant feedback on their performance.

8. **MongoDB Integration**: Seamlessly integrates with MongoDB to store exam results securely and efficiently.

9. **Reports and Analytics**: Offers separate reporting and analytics functionalities for both administrators and users, facilitating insightful analysis of exam data.

## Tech Stack

- **Frontend**: React, HTML, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Languages**: JavaScript

## Getting Started

To get started with the Exam Management System, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine using:

    ```
    git clone https://github.com/spranjals/Online-Quiz-Exam-Generator.git
    ```

2. **Install Dependencies**: Navigate to the project directory and install the necessary dependencies for both the frontend and backend:

    ```
    cd / Online-Quiz-Generator
    cd frontend
    npm install
    cd ../backend
    npm install
    ```

3. **Set Up MongoDB**: Ensure you have MongoDB installed and running on your system. Modify the MongoDB connection string in the backend configuration file (`backend/config/db.js`) if necessary.

4. **Run the Application**: Start both the frontend and backend servers:

    - For the frontend:

        ```
        cd ../frontend
        npm start
        ```

    - For the backend:

        ```
        cd ../backend
        npm start
        ```

5. **Access the Application**: Open your web browser and navigate to `http://localhost:3000` to access the Online-Quiz-Generator System.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow these guidelines:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Commit your changes and push them to your fork.
- Submit a pull request with a detailed explanation of your changes.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to adjust any sections to better fit your project's specifics. Good luck with your Exam Management System!
