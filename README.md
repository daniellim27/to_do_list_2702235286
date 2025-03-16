# To-Do List Application

A modern and responsive to-do list application built with React, Vite, and Firebase. This application allows users to create, manage, and track their tasks efficiently.

## Features

- Create, edit, and delete tasks
- Mark tasks as completed
- Filter tasks by status
- User authentication with Firebase
- Real-time data synchronization
- Responsive design with Tailwind CSS

## Technologies Used

- **Frontend**: React 19, React Router
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **Database & Authentication**: Firebase
- **Icons**: Font Awesome
- **UUID**: For generating unique IDs

## Getting Started

### Prerequisites

- Node.js (version 16.x or later recommended)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd to-do-list
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Create a Firebase project and set up Firebase configuration:
   - Create a project at [Firebase Console](https://console.firebase.google.com/)
   - Enable Authentication and Firestore
   - Add a web app to your Firebase project
   - Copy the Firebase configuration

4. Create a `.env` file in the root directory and add your Firebase configuration:
   ```
   VITE_FIREBASE_API_KEY=your-api-key
   VITE_FIREBASE_AUTH_DOMAIN=your-auth-domain
   VITE_FIREBASE_PROJECT_ID=your-project-id
   VITE_FIREBASE_STORAGE_BUCKET=your-storage-bucket
   VITE_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
   VITE_FIREBASE_APP_ID=your-app-id
   ```

### Running the Application

To start the development server:

```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:5173/` by default.

### Building for Production

To build the application for production:

```bash
npm run build
# or
yarn build
```

To preview the production build:

```bash
npm run preview
# or
yarn preview
```

## Project Structure

- `/src`: Source code
  - `/components`: React components
  - `/contexts`: React context providers
  - `/assets`: Static assets
  - `firebase.js`: Firebase configuration
  - `App.jsx`: Main application component
  - `main.jsx`: Application entry point

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [Firebase](https://firebase.google.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Font Awesome](https://fontawesome.com/)
