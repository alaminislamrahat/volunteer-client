# Volunteer Management System - Frontend

#Live Link: https://volunteer-management-3413a.web.app

🧑‍🤝‍🧑 Volunteer Management System (Client-Side)
Welcome to the client-side of the Volunteer Management System. This frontend is built with React, Tailwind CSS, and DaisyUI to provide a dynamic and responsive user experience. It communicates with the backend server to display and manage volunteer data in a clean and interactive interface.

Volunteer Client Repository

🚀 Features
Responsive Design: Built with Tailwind CSS to ensure the website is optimized for all devices, from mobile to desktop.
Dynamic Data: Fetches volunteer data from the server and dynamically displays it on the frontend.
Interactive Components: Uses DaisyUI components for modern UI elements like buttons, cards, and forms.
Volunteer Management: Allows users to view, add, and manage volunteer information through the user interface.
🛠️ Technologies Used
React - JavaScript library for building interactive user interfaces.
Tailwind CSS - Utility-first CSS framework for fast and responsive design.
DaisyUI - Component library based on Tailwind CSS for beautiful UI components.
Axios - For making API requests to the backend server.
📋 Features & Components
Volunteer List: Displays a list of volunteers fetched from the backend.
Add Volunteer Form: Allows users to add new volunteers by submitting the form.
Volunteer Cards: Each volunteer is shown with their details in an organized and interactive card layout.
Responsive Layout: Automatically adjusts the layout for mobile, tablet, and desktop screens.
📈 Setup Instructions
Prerequisites
Node.js and npm installed on your local machine.
The Volunteer Management System (Server-Side) should be running to fetch data.
Installation
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/alaminislamrahat/volunteer-client.git
Navigate to the project folder:
bash
Copy code
cd volunteer-client
Install the required dependencies:
bash
Copy code
npm install
Configuration
Set the API URL for the server in your React project (usually done in a .env file or directly in the app config). Example:
bash
Copy code
REACT_APP_API_URL=http://localhost:5000
Start the development server:
bash
Copy code
npm start
The website will be running at http://localhost:3000.
🛠️ How to Use
View Volunteers: The homepage will automatically fetch and display the list of volunteers from the backend.
Add a Volunteer: Use the Add Volunteer form to submit new volunteer data to the backend.
Responsive Design: The website automatically adjusts to different screen sizes, ensuring a smooth experience on mobile, tablet, and desktop devices.
💡 Future Improvements
Add authentication to allow for role-based access to manage volunteers.
Implement pagination for better management of large datasets.
Add more features for volunteer details such as skills, availability, and assignments.
## Getting Started

Follow the steps below to run the frontend locally:

### Prerequisites

- Node.js and npm installed on your machine.
- A backend server for API requests (refer to the backend repository).

### Installation

1. Clone the repository:
   
git clone git@github.com:programming-hero-web-course2/b10a11-client-side-alaminislamrahat.git

2. Navigate to the project directory:
   
cd volunteer-management-frontend

3. Install dependencies:
   
npm install

4. Create an .env file in the root of your project and configure the API URL:
   
env
REACT_APP_API_URL=http://localhost:5000

### Running the Application

Start the development server:
npm start

The application will be available at http://localhost:3000.

## Folder Structure

/src
/components
/pages
/hooks
/utils
App.js
index.js
tailwind.config.js

## Deployment

To build and deploy the project:
npm run build

Host the build folder on platforms like Netlify or Vercel.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.
