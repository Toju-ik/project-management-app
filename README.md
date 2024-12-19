# Course Connect

## Project Overview
Course Connect is a Progressive Web Application (PWA) designed to help students manage tasks, navigate campus buildings, and collaborate with peers. With features like interactive maps, task tracking, and study buddy matching, Course Connect streamlines student productivity and engagement.

### Key Features:
- Task Management: Add, edit, and track assignments.
- Campus Navigation: Interactive map highlighting key locations.
- Study Buddy Finder: Match with peers based on courses and interests.
- PWA Functionality: Installable on devices and works offline.

---

## Directory Structure
- `/backend` - API and database logic.
- `/frontend` - React application and UI components.
- `/docs` - Documentation for the project.

---

## Getting Started

### Prerequisites
- Install [Node.js](https://nodejs.org/).
- Install [Git](https://git-scm.com/).

### Installation

1. **Clone the Repository**
    ```bash
    git clone https://github.com/your-username/project-management-app.git
    ```

2. **Navigate to the Project Directory**
    ```bash
    cd project-management-app
    ```

3. **Install Dependencies**
    - **Backend**
        ```bash
        cd backend
        npm install
        ```
    - **Frontend**
        ```bash
        cd ../frontend
        npm install
        ```

4. **Environment Variables**
    - Add a `.env` file in the `/backend` directory:
      ```
      PORT=5000
      MONGO_URI=your_mongo_db_connection_string
      JWT_SECRET=your_jwt_secret_key
      ```

---

## Running the Project

1. **Start Backend Server**
    ```bash
    cd backend
    npm start
    ```

2. **Start Frontend Server**
    ```bash
    cd ../frontend
    npm start
    ```

---

## Branch Naming Conventions
- **Main Branch**: `main` (stable version).
- **Feature Branches**: `feature/feature-name` (e.g., `feature/dashboard`).

---

## Contributing

### How to Contribute:
1. Fork the repository.
2. Create a feature branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Commit your changes:
    ```bash
    git commit -m "Add your message here"
    ```
4. Push the branch:
    ```bash
    git push origin feature/your-feature-name
    ```
5. Create a pull request.

### Coding Standards:
- Use ESLint for linting.
- Follow the existing file and folder structure.

### Reporting Issues:
- Submit bugs or feature requests through GitHub Issues.

---

## Testing
- Run tests for the backend:
    ```bash
    cd backend
    npm test
    ```

---

## Project Status
- **Current Phase**: Prototype complete; development for core functionalities in progress.
- **Upcoming Features**:
  - Study Buddy Matching.
  - Notifications and gamification elements.

---

## License
Specify the license here.
