# Income & Expense Tracker

A comprehensive web application for personal finance management that allows users to track their income and expenses efficiently.

## Features

- **User Authentication**: Secure login and registration system with JWT
- **Dashboard**: Visual representation of financial data with charts and summaries
- **Transaction Management**: Add, edit, and categorize income and expense transactions
- **Category Management**: Create and manage custom categories for better organization
- **Financial Reports**: Generate and visualize spending patterns and financial trends
- **Responsive Design**: Works seamlessly across desktop and mobile devices

## Technology Stack

### Frontend
- React.js with TypeScript
- TailwindCSS for styling
- Chart.js for data visualization
- Formik & Yup for form validation
- React Router for navigation

### Backend
- Spring Boot
- Spring Security with JWT authentication
- Spring Data JPA
- PostgreSQL database
- RESTful API architecture

## Getting Started

### Prerequisites
- Node.js (v16 or later)
- Java 17
- PostgreSQL

### Installation

#### Backend
1. Navigate to the backend directory
2. Configure your PostgreSQL connection in `application.properties`
3. Run `mvn spring-boot:run`

#### Frontend
1. Navigate to the frontend directory
2. Install dependencies: `npm install`
3. Start the development server: `npm run dev`

## Project Structure

- `frontend/`: React.js application
  - `src/components/`: UI components
  - `src/services/`: API service calls

- `backend/`: Spring Boot application
  - `controller/`: REST controllers
  - `model/`: Data models
  - `service/`: Business logic
  - `repository/`: Data access layer
  - `security/`: Authentication and authorization
