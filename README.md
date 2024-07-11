Secrets App

Secrets App is a secure web application that allows users to manage and store sensitive information with confidence. It integrates several robust security features to safeguard user data and ensure a seamless experience.
Features

    Google OAuth Integration: Secure and convenient user authentication via Google accounts.

    Encrypted Password Storage: Utilizes bcrypt for encrypting and securely storing user passwords.

    PostgreSQL Database: Reliable data management using PostgreSQL, ensuring scalability and performance.

    Dynamic HTML Rendering: Enhanced user interface with dynamic content generation using EJS templates.

Functionality

    User Registration: Easy registration process allowing new users to sign up securely.

    Login: Secure login functionality for authenticated access to user-specific features and data.

    Confidentiality: Ensures data integrity and confidentiality through advanced security measures.

Set up environment variables:
Create a .env file in the root directory with the following variables:

PORT=3000
DB_HOST=localhost
DB_USER=username
DB_PASS=password
DB_NAME=secrets_db
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret

Start the application:

    npm start
    Open your web browser and navigate to http://localhost:3000 to access the application.

Contributing

Contributions are welcome! Please fork the repository and submit pull requests to contribute improvements or new features.
