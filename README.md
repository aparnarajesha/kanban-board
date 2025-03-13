# Kanban Board Project

## Overview
This is a **Kanban Board** built using **ReactJS**. It includes features like:
- Four columns: **To Do, In Progress, Peer Review, Done**
- Drag-and-drop functionality for task management
- Task cards with a title and truncated description
- Search bar for filtering tasks dynamically by title
- Floating button to add new tasks (only in the 'To Do' column)
- Task creation form with title and description

## Project Setup Instructions
### 1. Extracting Files
Since this project is large, all files are uploaded as separate **zip** folders. Follow these steps to extract and set up:
1. **Extract Each Folder:** Unzip each folder separately (e.g., `src.zip`, `public.zip`, `node_modules_part1.zip`, `node_modules_part2.zip`, etc.).
2. **Combine Node Modules:** Merge all extracted `node_modules` parts into a single `node_modules` folder.

### 2. Install Dependencies
Once all files are extracted, navigate to the project directory and install dependencies:
```sh
npm install
```

### 3. Start the Development Server
Run the following command to start the development server:
```sh
npm start
```
The application will be available at `http://localhost:3000/`.

#Demo:
https://youtu.be/JhbuG4P5RDw?si=k5a7V5CJwmfQO9oU


## Folder Structure
```
kanban-board/
│── public/            # Static assets
│── src/               # Source code
│   ├── components/    # React components
│   ├── styles/        # CSS and styled-components
│   ├── utils/         # Helper functions
│── node_modules/      # Dependencies (Merged from multiple zip files)
│── .gitignore         # Files to ignore in Git
│── package.json       # Project metadata and dependencies
│── README.md          # Project documentation
```

## Features & Functionality
- **Drag-and-Drop Tasks**: Easily move tasks between columns.
- **Search Bar**: Filter tasks by title dynamically.
- **Task Assignment**: Each task displays an avatar.
- **Real-time Updates**: Updates task status on the fly.

## Technologies Used
- **Frontend**: ReactJS, Styled-Components
- **State Management**: React Hooks
- **Drag & Drop**: react-beautiful-dnd
- **UI Components**: Ant Design

## Contribution & Issues
If you'd like to contribute, feel free to fork this repo and submit a pull request. For issues, report them in the GitHub Issues section.

## License
This project is licensed under the MIT License.

---
**Happy Coding! 🚀**



