# Eventos - Calendar Application

Welcome to Eventos, your comprehensive calendar web application powered by React.js and Express.js. Eventos offers a wide array of features designed to streamline your calendar management experience.

## Features

### User Authentication

- **Signup**: Easily create an account to get started.
- **Login**: Securely access your account with your credentials.

### Calendar Views

- **Week and Day Views**: Gain insights into your schedule through detailed week and day calendar views.

### Intuitive Navigation

- **Next and Previous Buttons**: Effortlessly navigate through calendar dates with intuitive next and previous buttons.
- **Today Button**: Instantly jump to the current date by clicking the "Today" button.

### Event Management

- **Create Events**: Personalize your schedule by adding events with the following attributes:

  - **Title**: The title of the event (string).
  - **Description**: A detailed description of the event (string).
  - **Note**: A short note or reminder (string).
  - **End Time**: The end time of the event (ISO string, ignored if it's an all-day event).
  - **All-Day Event**: Indicates whether the event is a full-day event (boolean).
  - **Start Time**: The start time of the event (ISO string or other date string).
  - **Repeat Frequency**: Define event recurrence frequency (daily, weekly, monthly, yearly).
  - **Repeat Interval**: Specify the repeat cycle for recurring events (number).
- **Event List**: View a comprehensive list of all your created events.
- **Update and Delete**: Easily modify or remove events to keep your schedule up-to-date.

## Technologies Used

### Backend

- **Express.js**: Building a robust and performant backend server.
- **MongoDB**: Efficiently storing and retrieving your data.
- **JSON Web Tokens (JWT)**: Ensuring secure user authentication and authorization.
- **Mongoose**: An elegant object modeling tool for MongoDB.

## Installation

### Requirements:

1. Node version: `v18.12`
2. Npm version: `v8.19.2`

### Backend

1. Clone the repository:

   ```
   git clone https://github.com/odht82/calendar-app-api && cd calendar-app-api
   ```
2. Install dependencies:

   ```
   npm i
   ```
3. Create your MongoDB database and store the connection URI in a `.env` file.
4. Add environment variables according to `.env.example`.
5. Start the development server:

   ```
   npm run dev
   ```

---

### **Other Repository:**

[FrontEnd Repository](https://github.com/odht82/calendar-app "Frontend Eventos")

---
