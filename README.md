# Online Banking Portal

## Overview
A secure and user-friendly online banking portal built with Java and Spring Boot, offering features like account management, fund transfers, bill payments, card tracking, loan status updates, and locker availability, secured with AES encryption and robust validations.

## Features
- **Secure Login**: AES encryption and server/client-side validations for data protection.
- **Account Management**: Access transaction history and account details.
- **Fund Transfers & Bill Payments**: Seamless and secure transactions.
- **Card Management**: Apply for and track various cards.
- **Loan & Locker Services**: Check loan status and real-time locker availability.

## Tech Stack
- **Backend**: Java, Spring Boot, Maven, MySQL, AES encryption.
- **Frontend**: HTML, CSS, (optional) ReactJS.
- **APIs**: RESTful APIs with JSON data exchange.

## Setup
1. **Clone Repository**:
   ```
   git clone https://github.com/yourusername/online-banking-portal.git
   cd online-banking-portal
   ```
2. **Database Setup**:
   - Create a MySQL database and update credentials in `application.properties`.
   - Run provided SQL scripts to initialize the schema.
3. **Run Backend**:
   ```
   mvn clean install
   mvn spring-boot:run
   ```
4. **(Optional) Setup Frontend**:
   - Navigate to the frontend folder.
   - Install dependencies: `npm install`.
   - Start development server: `npm start`.

5. Access the Portal:
   - Visit  `http://localhost:3000 ` for the frontend (if ReactJS).
   - Visit  `http://localhost:8080 ` for backend API access.

## Contribution
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request for review.

