# FullStack-Dall-E
The front end is created using React and JS, and backend consists of the MERN Stack(MongoDB, Express, React Node) All images are generated using the dall-e API by OpenAI
The user can input a prompt they want the AI to generate an image for.

**Overview:**
DALL-E Image Generator is a full-stack web application that leverages the power of OpenAI's DALL-E API to create images based on user input prompts. This project combines cutting-edge AI technology with a modern MERN stack to provide a seamless and interactive image-generation experience.

# Features

AI-Powered Image Generation: Users can input prompts or descriptions, and the application utilizes the DALL-E API to generate unique and creative images based on those prompts.

MERN Stack: The project is built on the MERN stack, consisting of MongoDB for database storage, Express.js for the backend API, React for the front end, and Node.js as the server runtime.

User Authentication: Users can create accounts, log in, and save their generated images to their profiles. Authentication is handled securely with JWT tokens.

Image History: Users can access their image generation history and view previously generated images.

Responsive Design: The user interface is designed to be responsive and user-friendly, ensuring a seamless experience across various devices and screen sizes.

Image Storage: Generated images are stored securely and efficiently in the MongoDB database.

# Technologies Used

**Frontend:**

React.js
Axios for API requests
Material-UI for UI components
Redux for state management

**Backend:**

Express.js
Node.js
JWT for authentication
Mongoose for MongoDB interactions

**Database:**

MongoDB

**AI Integration:**

OpenAI DALL-E API

![image](https://github.com/ThomasOli/FullStack-Dall-E/assets/51518411/840ac90d-dab5-4770-b9db-0c902748173a)\

![image](https://github.com/ThomasOli/FullStack-Dall-E/assets/51518411/89b03ede-3bd6-4162-99c4-9b332f884529)

After the image is generated, the user can choose to post their image to the community showcase.
![image](https://github.com/ThomasOli/FullStack-Dall-E/assets/51518411/b35b6a68-6ea4-46d8-bb40-f78fd578ae19)
The search bar can be used to search within the community photo repository.
![image](https://github.com/ThomasOli/FullStack-Dall-E/assets/51518411/6e4dfd07-ada5-4386-a560-f8e65dac75f5)






## Setup
### Clone the repository:
```
git clone https://github.com/ThomasOli/dall-e-image-generator.git

```
### Install dependencies for the frontend and backend:

```
cd dall-e-image-generator/frontend
npm install
cd ../backend
npm install
```
### Configure environment variables for both the frontend and backend. Include API keys and other sensitive information.

### Start the development server for both the frontend and backend:


Frontend (from the frontend directory)
```
npm start
```
Backend (from the backend directory)
```
npm start
```
### Access the application in your web browser at http://localhost:3000.

## Usage
Sign up for an account or log in if you already have one.
Input a prompt or description for the image you want to generate.
Click the "Generate Image" button, and watch DALL-E work its magic!
View and save the generated image to your profile.

## Contributing
Contributions are welcome! Feel free to open issues or pull requests for bug fixes, enhancements, or new features.

##License
This project is licensed under the MIT License - see the LICENSE file for details.

This DALL-E Image Generator project demonstrates the seamless integration of AI technology with a robust MERN stack, providing users with a creative and interactive experience. Give it a try and bring your imagination to life through AI-generated images!
