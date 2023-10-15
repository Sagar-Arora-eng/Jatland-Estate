# Jatland Estate

Welcome to Jatland Estate, a MERN stack web application for managing and listing properties. This interactive readme will guide you through the project, its deployment, technologies used, and key features.

## Deployment
You can access the deployed web application at [Jatland Estate Web App](https://jetland-estate-webapp.onrender.com/).

## Technologies Used
- **Frontend**:
  - React: A JavaScript library for building user interfaces.
  - Redux Toolkit: A state management library for predictable state containers.
  - Tailwind CSS: A utility-first CSS framework for building responsive web designs.

- **Backend**:
  - Express: A fast and minimalist web framework for Node.js.
  - MongoDB: A NoSQL database for storing property and user data.
  - Firebase: Used for advanced authentication and cloud functions.

## Features
Jatland Estate offers a range of features to enhance the user experience:

1. **Advanced Authentication**
   - Implement JWT for secure user authentication.
   - Utilize Firebase for additional authentication methods and storage.
   - Integrate Google OAuth for seamless user access.

2. **User-friendly Features**
   - Image Uploads: Allow users to upload images of their properties.
   - Property Listing Management: Provide users with the ability to manage their property listings.
   - And more: Discover additional user-friendly features while exploring the application!

## Getting Started
To get started with Jatland Estate, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/jatland-estate.git
   ```

2. Install dependencies for both the frontend and backend:
   ```bash
   cd jatland-estate
   npm install
   cd client
   npm install
   ```

3. Set up your environment variables:
   - Create a `.env` file in the main directory and in the 'api' folder configure your MongoDB.
   - Create a `.env` file in the client directory and configure Firebase credentials.

4. Start the development servers:
   - For the frontend:
     ```bash
     cd ../api
     npm run dev
     ```

   - For the backend:
     ```bash
     npm start
     ```

5. Open your web browser and navigate to `http://localhost:5173` to access the Jatland Estate web application.
