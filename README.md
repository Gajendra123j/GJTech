# GJ Tech - Technology Blog and Learning Platform

A full-stack web application for technology blogging and online learning, built with Node.js, Express, MongoDB, and modern frontend technologies.

## Features

- **Blog System**
  - Create, read, update, and delete blog posts
  - Categorize posts by technology
  - Like and comment on posts
  - Search functionality
  - Author profiles

- **Course Platform**
  - Course creation and management
  - Student enrollment
  - Course curriculum with different content types
  - Student progress tracking
  - Course reviews and ratings

- **User Management**
  - User registration and authentication
  - Role-based access control
  - Profile management
  - Password reset functionality

- **Contact System**
  - Contact form for inquiries
  - Admin message management
  - Email notifications

## Tech Stack

- **Backend**
  - Node.js
  - Express.js
  - MongoDB
  - Mongoose
  - JWT Authentication
  - Nodemailer

- **Frontend**
  - HTML5
  - CSS3 (Tailwind CSS)
  - JavaScript
  - Modern UI/UX design

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/gj-tech.git
cd gj-tech
```

2. Install dependencies:
```bash
npm install
```

3. Create a .env file in the root directory and add the following variables:
```
NODE_ENV=development
PORT=3000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
SMTP_EMAIL=your_email
SMTP_PASSWORD=your_password
```

4. Start the development server:
```bash
npm run dev
```

## Project Structure

```
gj-tech/
├── config/         # Configuration files
├── controllers/    # Route controllers
├── middleware/     # Custom middleware
├── models/         # Mongoose models
├── public/         # Static files
├── routes/         # API routes
├── .env            # Environment variables
├── .gitignore      # Git ignore file
├── package.json    # Project dependencies
├── README.md       # Project documentation
└── server.js       # Application entry point
```

## API Documentation

The API documentation is available at `/api-docs` when running the server in development mode.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Gajendra Singh - [@Gajendra123j](https://twitter.com/Gajendra123j)

Project Link: [https://github.com/Gajendra123j/gj-tech](https://github.com/Gajendra123j/gj-tech) 