# React OLX Clone (Vite)

This project is a lightweight clone of the OLX classifieds website, built as a learning project. It mimics the basic functionality of OLX, allowing users to view and post advertisements.

This application is built with React and bootstrapped using [Vite](https://vitejs.dev/) for a fast and modern development experience.

## Features

- **Browse Ads:** View all available products on the homepage.
- **View Details:** Click on any ad to see its detailed view (this feature is in progress).
- **User Authentication:** Full user flow including Sign Up and Log In using Firebase Authentication.
- **Post New Ads:** Logged-in users can post new advertisements with product details and an image.
- **Protected Routes:** Certain pages (like 'Create Post') are protected and only accessible to logged-in users.

## Tech Stack

- **Frontend:** [React](https://reactjs.org/)
- **Build Tool:** [Vite](https://vitejs.dev/)
- **Routing:** [React Router v6](https://reactrouter.com/)
- **Backend & DB:** [Firebase](https://firebase.google.com/) (used for Authentication, Firestore Database, and Storage)
- **State Management:** [React Context API](https://reactjs.org/docs/context.html) (for managing user authentication state)
- **Styling:** CSS3 (or Tailwind CSS - _you can edit this part_)

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) (v16 or higher) and `npm` installed on your machine.

### Installation

1.  **Clone the repository**

    ```sh
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```

2.  **Navigate to the project directory**

    ```sh
    cd your-repo-name
    ```

3.  **Install NPM packages**

    ```sh
    npm install
    ```

4.  **Set up Environment Variables**

    This project requires Firebase API keys to run.

    - Create a new file named `.env` in the root of your project.
    - Add your Firebase project configuration keys. **(Remember, Vite requires all environment variables to be prefixed with `VITE_`)**

    Your `.env` file should look like this:

    ```env
    VITE_API_KEY=your_api_key
    VITE_AUTH_DOMAIN=your_auth_domain
    VITE_PROJECT_ID=your_project_id
    VITE_STORAGE_BUCKET=your_storage_bucket
    VITE_MESSAGING_SENDER_ID=your_sender_id
    VITE_APP_ID=your_app_id
    ```

5.  **Run the Development Server**
    ```sh
    npm run dev
    ```

The app will be running on `http://localhost:5173` (or the next available port).
