# TripsTravels

TripsTravels is a responsive web application that allows users to explore, book trips, and share reviews. Built with modern web technologies, it provides a seamless user experience across all devices.

## Live link
https://trips-travel.vercel.app/home

## Features

- **User Authentication**: Sign up, log in, and log out functionality.
- **Trip Booking**: Users can browse and book trips effortlessly.
- **Reviews and Ratings**: Users can add reviews and rate their travel experiences.
- **Responsive Design**: Fully optimized for all screen sizes, from mobile to desktop.

## Tech Stack

### Frontend
- **React**: For building a dynamic and responsive user interface.
- **Tailwind CSS**: For styling and responsive design.
- **React Router**: For handling navigation.
- **Axios**: For making API requests.
- **React Toastify**: For notifications.
- **React Slick** and **Swiper**: For carousels and interactive UI components.

### Backend
- **Node.js**: Server-side JavaScript runtime.
- **Express**: Web framework for building the backend API.
- **MongoDB**: NoSQL database for storing user and trip data.
- **Mongoose**: Object Data Modeling (ODM) library for MongoDB.
- **JWT (JSON Web Tokens)**: For secure user authentication.
- **bcrypt.js**: For password hashing.

### Development Tools
- **Vite**: For fast frontend development and building.
- **Nodemon**: For automatic server restarts during development.
- **ESLint**: For code quality and linting.
- **PostCSS**: For processing CSS.

## Installation

Follow these steps to set up the project locally:

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- MongoDB instance

### Backend Setup
1. Navigate to the `backend` folder:
   ```bash
   cd backend
    ```
2. Install dependencies:
```bash
npm install
```
3. Create a .env file in the backend folder and add the following:
```bash
PORT=5000
MONGO_URL=<Your MongoDB Connection String>
SECRET_KEY=<Your JWT Secret Key>
```
4. Start the backend server:
```bash
npm run dev
```
### Frontend Setup
1. Navigate to the frontend folder:
```bash
cd frontend
```
2. Install dependencies:
```bash
npm install
```
3. Start the development server:
```bash
npm run dev
```
## Additional Information
TripsTravels was designed to simplify the process of booking trips and sharing travel experiences. The application prioritizes ease of use, security, and scalability, ensuring a reliable experience for users.

## License
This project is licensed under the ISC License.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

## Acknowledgements
- React and Node.js communities for their excellent documentation.
- Tailwind CSS for simplifying responsive design.
- MongoDB for its flexible NoSQL database solutions.
