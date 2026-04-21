# Bareq - Academic Services Marketplace Backend

An academic educational platform for the university community. It serves as a marketplace where students, graduates, and academics can offer and request educational services. The platform includes a robust backend to handle all core functionalities, user management, and dispute resolution.

## Features

- **User Management**: Academic user registration, authentication, and profile management
- **Custom Requests**: Students can post custom academic service requests
- **Offers & Bidding**: Service providers can submit offers for requests
- **File Management**: Support for file uploads and attachments
- **Payment System**: Integrated wallet system with transaction tracking
- **Dispute Resolution**: Built-in dispute handling and resolution
- **Rating System**: User rating and review system
- **Real-time Communication**: WebSocket support for chat functionality
- **Admin Panel**: Comprehensive admin dashboard for platform management

## Tech Stack

- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: PostgreSQL with Prisma ORM
- **Authentication**: JWT (JSON Web Tokens)
- **File Upload**: Multer middleware
- **Validation**: Joi schema validation
- **Real-time**: Socket.io
- **Containerization**: Docker & Docker Compose


## Project Structure

```
bareq/
├── prisma/                 # Database schema and migrations
├── src/
│   ├── config/            # Configuration files
│   ├── controllers/       # Route controllers
│   ├── middlewares/       # Express middlewares
│   ├── routes/            # API route definitions
│   ├── services/          # Business logic services
│   ├── socket/            # WebSocket handlers
│   ├── utils/             # Utility functions
│   └── app.js            # Express app configuration
├── uploads/               # File upload directory
├── docker-compose.yml     # Docker configuration
├── Dockerfile            # Docker image definition
└── package.json          # Dependencies and scripts



## 🔒 Security Features

- JWT-based authentication
- Password hashing with bcrypt
- Rate limiting middleware
- CORS protection
- Input validation with Joi
- SQL injection prevention with Prisma
