# BookNook Server 📚

BookNook Server is the backend of the BookNook online library platform. It provides RESTful APIs to manage books, handle borrowing activities, process book cover image uploads, and support secure communication between the client and database.

## 🌐 Live API

[Visit BookNook Server](https://booknook-server-peach.vercel.app/)

## 🔗 Project Repositories

- **Client Repository:** [BookNook Client](https://github.com/mahzamincodes/PH-B14-A08-BookNook-Client)
- **Server Repository:** [BookNook Server](https://github.com/mahzamincodes/PH-B14-A08-BookNook-Server)
- **Live Client:** [BookNook Website](https://booknook-client-blond.vercel.app/)

## ✨ Key Features

- **Book Management:** Provides API functionality for managing book information.
- **Borrowing Management:** Handles book borrowing and return operations.
- **Database Integration:** Stores and manages application data using MongoDB.
- **Authentication & Security:** Supports secure API access and JWT verification.
- **Image Upload:** Handles book cover image uploads using Multer and ImgBB.
- **RESTful API:** Provides backend endpoints for communication with the frontend.
- **Environment Configuration:** Uses environment variables to manage sensitive configuration.

## 🛠️ Technologies Used

- Node.js
- Express.js
- MongoDB
- JWT (Jose)
- Multer
- ImgBB API
- dotenv
- CORS

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/mahzamincodes/PH-B14-A08-BookNook-Server.git
cd PH-B14-A08-BookNook-Server
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the project root and configure the required environment variables, including:

- MongoDB connection URL
- ImgBB API key
- Better Auth URL
- Client URL
- Other required server configuration

Never commit your actual secret keys or credentials to GitHub.

### 4. Start the Server

```bash
npm start
```

The backend runs on port `5000` by default.

## 🎯 Project Goal

The goal of BookNook Server is to provide a reliable backend system for managing books, borrowing activities, authentication, and database operations for the BookNook online library platform.

## 👨‍💻 Developer

Developed by **Mahzamin Khan** as part of Programming Hero Assignment 08.
