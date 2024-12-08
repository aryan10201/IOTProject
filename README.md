# IoT-Enabled Full-Stack Authentication System  

This project is a robust authentication system that integrates IoT components for real-time user interaction. It features a full-stack implementation using Express.js for the backend, Next.js for the frontend, and an ESP8266 microcontroller with an OLED display for displaying authentication statuses.  

## Features  

- **Full-Stack Authentication System**:  
  A comprehensive system enabling user registration, login, logout, and profile management.  

- **Email Verification and Password Management**:  
  Secure OTP-based email verification, password reset functionality, and two-step authentication using Nodemailer.  

- **JWT-Based Session Management**:  
  Implemented access and refresh tokens for session management, including token expiration handling and auto-refresh mechanisms.  

- **Responsive UI with State Management**:  
  Built with Redux Toolkit and RTK Query for seamless state management across the application, including registration, login, and password management forms.  

- **IoT Integration**:  
  Connected to an ESP8266 microcontroller and OLED display for real-time text display, enhancing user interaction with IoT technology.  

## Technology Stack  

### Backend:  
- **Express.js**: Framework for building RESTful APIs.  
- **MongoDB**: Database for storing user information.  
- **Nodemailer**: Library for sending email OTPs.  
- **Passport.js**: Middleware for authentication using JWT.  

### Frontend:  
- **Next.js**: Framework for server-rendered React applications.  
- **Redux Toolkit**: For efficient state management.  
- **Formik & Yup**: For handling and validating forms.  

### IoT:  
- **ESP8266**: Microcontroller for displaying text on an OLED display.
