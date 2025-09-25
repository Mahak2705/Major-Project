# Wonderlust - Travel Stay Booking Platform

A full-stack web application for booking travel accommodations and stays, built with Node.js, Express, and MongoDB.

## Features

- User authentication and authorization
- Property listings with categories (Trending, Rooms, Cities, Mountains etc.)
- Image upload and storage using Cloudinary
- Reviews and ratings system
- Search and filter properties
- Responsive design using Bootstrap

## Tech Stack

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- Authentication using express-session
- Input validation using Joi
- Image upload using Multer & Cloudinary

### Frontend 
- EJS templating
- Bootstrap 5
- Custom CSS
- Font Awesome icons

## Project Structure
├── controllers/ # Route controllers ├── models/ # MongoDB models ├── routes/ # Express routes ├── views/
│ ├── includes/ # Reusable view components │ ├── layouts/ # Base layout templates │ ├── listings/ # Property listing views │ └── users/ # User account views ├── public/ │ ├── css/ # Stylesheets │ └── js/ # Client-side JavaScript ├── utils/ # Helper utilities ├── init/ # Initialization data └── app.js # Express app entry point



## Setup & Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/wonderlust.git

npm install

CLOUD_NAME=your_cloudinary_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret
MONGO_URL=your_mongodb_connection_url
SESSION_SECRET=your_session_secret

node app.js

**Environment Requirements**
Node.js 22.18.0
MongoDB

**Features in Detail**
Property Listings
Create, read, update and delete property listings
Upload multiple images
Categorize properties
Add pricing and location details

**User System**
User registration and authentication
User profiles
Property ownership management

**Reviews & Ratings**
Add reviews with ratings
View property ratings
Edit/delete reviews

**Contributing**
Contributions are welcome! Please feel free to submit a Pull Request.

**License**
This project is licensed under the ISC License.

