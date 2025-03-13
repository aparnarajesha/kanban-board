Kanban Board App

A simple and responsive Kanban board web application built with React, Redux, and drag-and-drop functionality.

Features

✅ Four Fixed Columns: To Do, In Progress, Peer Review, Done✅ Drag & Drop Task Management✅ Add, Edit, and Delete Tasks✅ Persistent State with Redux & Local Storage✅ Search Tasks by Title✅ Attach Images to Columns✅ Responsive & User-Friendly UI

Demo



Getting Started

Prerequisites

Ensure you have the following installed:

Node.js

npm or yarn

Installation

Clone the repository:


cd kanban-board

Install dependencies:

npm install  # or yarn install

Running the App

To start the development server:

npm start  # or yarn start

Open http://localhost:3000 in your browser.

API Integration

The app fetches tasks from https://dummyjson.com/todos. You can replace it with your preferred API.

Folder Structure

kanban-board/
│-- src/
│   │-- components/      # Reusable components (TaskCard, Column, etc.)
│   │-- redux/           # State management with Redux
│   │-- assets/          # Images & static assets
│   │-- utils/           # Helper functions
│   │-- App.js           # Main app component
│   │-- index.js         # Entry point
│-- public/
│-- README.md            # Documentation
│-- package.json         # Dependencies

Deployment

Build and deploy the project:

npm run build  # or yarn build

Deploy on:

Vercel: vercel --prod

Netlify: netlify deploy

Contributing

Feel free to fork this repo and submit pull requests. Contributions are welcome!

License

This project is licensed under the MIT License.

