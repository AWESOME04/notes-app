# Markdown Notes App

![image](https://github.com/AWESOME04/notes-app/assets/102630199/eae1c56e-1c9e-43ad-94e2-db0cd4ff117d)

This is a React-based web application that allows users to create, edit, and delete markdown notes. The app features a split-screen layout with a sidebar for managing notes and a main editor area for writing and previewing markdown content.

## Features

- Create new notes
- Edit existing notes
- Delete notes
- Markdown preview with live rendering
- Persistent note storage using localStorage
- Responsive design with a split-screen layout

## Technologies Used

- React
- react-mde (Markdown Editor)
- showdown (Markdown to HTML converter)
- react-split (Split-screen layout)
- nanoid (Unique ID generation)

## Getting Started

To get a local copy of the project up and running, follow these steps:

1. Clone the repository
   ```
   git clone https://github.com/your-username/markdown-notes-app.git
   ```

2. Install dependencies
   ```
   cd markdown-notes-app
   npm install
   ```

3. Start the development server
   ```
   npm start
   ```

4. Open the app in your browser at `http://localhost:3000`

## Screenshot

![image](https://github.com/AWESOME04/notes-app/assets/102630199/0ae7c592-12d6-46fe-bd0d-057886709cb6)

  
## File Structure

- `src/components/Editor.js`: The main markdown editor component.
- `src/components/Sidebar.js`: The sidebar component for managing notes.
- `src/App.js`: The main app component that integrates the sidebar and editor components.
- `src/data.js`: Sample data for initializing the app with some pre-existing notes (not used in this project).

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgments

- [React](https://reactjs.org/)
- [react-mde](https://github.com/andrerpena/react-mde)
- [showdown](https://github.com/showdownjs/showdown)
- [react-split](https://github.com/nathancahill/split/tree/master/packages/react-split)
- [nanoid](https://github.com/ai/nanoid)
