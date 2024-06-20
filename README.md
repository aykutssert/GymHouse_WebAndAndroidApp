# Gym House

This repository is a fork of the original [Gymhouse_webAndAndroidApp](https://github.com/original_owner/Gymhouse_webAndAndroidApp) repository.

## Description

This project includes full stack web application development for the Gymhouse application. The development involved both frontend and backend implementation to create a complete and functional web application for gym management.

### Features

#### Frontend
- **Technologies:** HTML, CSS, JavaScript, Bootstrap
- **Features:**
  - Responsive Design for different screen sizes
  - User Authentication and Authorization
  - Interactive UI components
  - API Integration with Backend

#### Backend
- **Technologies:** ASP.NET Core
- **Features:**
  - RESTful API development
  - User Authentication
  - CRUD operations for managing gym data
  - Database Schema Design and Integration
  - Middleware for error handling and logging

#### Database
- **Technology:** MySQL
- **Features:**
  - Relational database management
  - Secure data storage
  - Efficient querying and indexing

## Setup Instructions

### Prerequisites

- [.NET Core SDK](https://dotnet.microsoft.com/download)
- [Node.js](https://nodejs.org/)
- [MySQL Server](https://www.mysql.com/)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your_username/Gymhouse_FullStackWebApp.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Gymhouse_FullStackWebApp
    ```

### Frontend Setup

3. Navigate to the frontend directory and install dependencies:
    ```bash
    cd frontend
    npm install
    ```

### Backend Setup

4. Navigate to the backend directory:
    ```bash
    cd ../backend
    ```

5. Restore .NET Core dependencies:
    ```bash
    dotnet restore
    ```

6. Set up environment variables:
    - Create an `appsettings.json` file in the `backend` directory.
    - Add the following configuration:
      ```json
      {
        "ConnectionStrings": {
          "DefaultConnection": "Server=your_server;Database=your_database;User=your_username;Password=your_password;"
        },
        "Jwt": {
          "Key": "your_jwt_secret",
          "Issuer": "your_issuer",
          "Audience": "your_audience"
        }
      }
      ```

### Database Setup

7. Set up your MySQL database and update the connection string in the `appsettings.json` file.

### Running the Application

8. Start the backend server:
    ```bash
    dotnet run
    ```

9. Start the frontend server:
    ```bash
    cd ../frontend
    npm start
    ```

10. Open your browser and navigate to `http://localhost:3000` to see the application in action.

## Contribution

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository
2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Commit your changes:
    ```bash
    git commit -m 'Add your feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature/your-feature-name
    ```
5. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

Special thanks to:
- Prof. Dr. Example Name for course guidance
- Teaching Assistants for their support
- GitHub community for code samples and inspiration
