# TaskVault

A secure Kanban board application for agile teams to efficiently manage and track work items.

![TaskVault Banner](https://via.placeholder.com/800x200?text=TaskVault+Kanban+Board)

## Overview

TaskVault is a web-based Kanban board application with secure authentication that enables agile teams to organize, visualize, and manage their workflows. The application features JWT-based authentication, drag-and-drop task management, and customizable work states to adapt to your team's specific workflow.

## Features

- **Secure Authentication**
  - JWT-based authentication system
  - Secure password handling
  - Session timeout for inactive users
  - Protection against unauthorized access

- **Intuitive Kanban Board**
  - Drag-and-drop interface for task management
  - Customizable columns for different workflow states
  - Visual indicators for task priority and status
  - Filter and search capabilities

- **User Experience**
  - Responsive design for desktop and mobile
  - Real-time updates across team members
  - Dark/light mode toggle
  - Notification system for task updates

## Technology Stack

- **Frontend**: React.js with React DnD for drag-and-drop functionality
- **Backend**: Node.js with Express
- **Authentication**: JWT (JSON Web Tokens)
- **Database**: MongoDB
- **Styling**: CSS with Tailwind CSS framework

## Getting Started

### Prerequisites

- Node.js (v14.0 or higher)
- npm or yarn
- MongoDB

### Installation

1. Clone the repository
   ```
   git clone https://github.com/camxchodxvid/taskvault.git
   cd taskvault
   ```

2. Install dependencies
   ```
   npm install
   ```

3. Configure environment variables
   Create a `.env` file in the root directory with the following variables:
   ```
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/taskvault
   JWT_SECRET=your_jwt_secret_key
   JWT_EXPIRATION=3600
   ```

4. Start the development server
   ```
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:3000`

## Usage

1. **Login/Register**
   - Create an account or login with existing credentials
   - Secure authentication protects your team's data

2. **Manage Tasks**
   - Create new tasks with title, description, priority, and assignee
   - Drag tasks between columns to update status
   - Edit task details or delete tasks as needed

3. **Team Collaboration**
   - Assign tasks to team members
   - Comment on tasks for discussion
   - Receive notifications for task updates

## API Documentation

The API documentation is available at `/api-docs` when running the development server, powered by Swagger UI.

## Security

AgileFlow implements several security measures:
- JWT tokens stored securely in HttpOnly cookies
- Password hashing using bcrypt
- CSRF protection
- Rate limiting to prevent brute force attacks
- Automatic session timeout after period of inactivity

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

David - [@camxchodxvid](https://github.com/camxchodxvid) - dxvid2001@gmail.com

Project Link: [https://github.com/camxchodxvid/taskvault](https://github.com/camxchodxvid/taskvault)

## Acknowledgements

- [React DnD](https://react-dnd.github.io/react-dnd/)
- [JSON Web Tokens](https://jwt.io/)
- [MongoDB](https://www.mongodb.com/)
- [Express](https://expressjs.com/)
- [Tailwind CSS](https://tailwindcss.com/)
