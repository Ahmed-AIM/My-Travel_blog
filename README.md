# Travel Blog Website

## Overview
This is a travel blog website focused on sharing travel experiences in Egypt. Users can post and share their travel stories, upload images, and interact with other travelers.

## Features
- User Dashboard: View and manage your posts, favorite posts, and profile.
- Blog Post Form: Create new blog posts with images and tags.
- About Us: Learn more about the travel blog and its mission.
- Footer: Consistent footer across the website.
- Destinations: Explore popular destinations in Egypt.
- Search: Find blog posts by title, tags, or destination.
- User Authentication: Login functionality for users.
- Responsive Design: Mobile-friendly layout.
- Edit Profile: Users can update their profile information.
- Saved Destinations: Users can save their favorite destinations.
- Favorite Posts: Users can save and manage their favorite blog posts.

## Technologies Used
- React
- Bootstrap
- FontAwesome
- Express.js (for server)
- React Router
- React Quill (for rich text editing)
- Axios (for API requests)

## File Structure
The project structure is as follows:
travel-official/
├── public/
│   ├── index.html
│   ├── favicon.ico
│   ├── manifest.json
│   └── robots.txt
├── server/
│   ├── data/
│   │   ├── data.json
│   │   └── users.json
│   ├── package.json
│   └── server.js
├── src/
│   ├── components/
│   │   ├── About.jsx
│   │   ├── BlogPost.jsx
│   │   ├── BlogPostForm.jsx
│   │   ├── BlogPostPage.jsx
│   │   ├── Contact.jsx
│   │   ├── Destinations.jsx
│   │   ├── EditProfileForm.jsx
│   │   ├── FilterInput.jsx
│   │   ├── Footer.jsx
│   │   ├── Header.jsx
│   │   ├── Homepage.jsx
│   │   ├── Login.jsx
│   │   ├── NavBar.jsx
│   │   ├── NewItineraryForm.jsx
│   │   ├── SearchBar.jsx
│   │   ├── SearchResults.jsx
│   │   ├── Sidebar.jsx
│   │   └── UserDashboard.jsx
│   ├── styles/
│   │   ├── About.css
│   │   ├── App.css
│   │   ├── BlogPost.css
│   │   ├── BlogPostForm.css
│   │   ├── BlogPostPage.css
│   │   ├── Contact.css
│   │   ├── Destinations.css
│   │   ├── Footer.css
│   │   ├── Header.css
│   │   ├── Homepage.css
│   │   ├── Login.css
│   │   ├── NavBar.css
│   │   ├── SearchBar.css
│   │   ├── Sidebar.css
│   │   └── UserDashboard.css
│   ├── App.js
│   ├── App.test.js
│   ├── apiConfig.js
│   ├── fontawesome.js
│   ├── index.css
│   ├── index.js
│   ├── reportWebVitals.js
│   └── setupTests.js
├── .gitignore
├── package.json
├── README.md
└── FileStructureTree.txt

## Setup
1. Clone the repository.
2. Navigate to the project directory.
3. Install dependencies for the client:
   ```bash
   npm install
   ```
4. Navigate to the server directory and install server dependencies:
   ```bash
   cd server
   npm install
   ```
5. Start the development server for the client:
   ```bash
   npm start
   ```
6. In a separate terminal, start the server:
   ```bash
   cd server
   node server.js
   ```

## Available Scripts
In the project directory, you can run:

- `npm start`: Runs the app in development mode.
- `npm test`: Launches the test runner.
- `npm run build`: Builds the app for production.

## API Configuration
The project uses a separate `apiConfig.js` file to manage API endpoints. Update this file if you need to change the server URL or API routes.

## Contributing
Contributions are welcome. Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License.

## Recent Changes
- Added EditProfileForm component for user profile editing
- Updated UserDashboard to include drafts and saved destinations
- Enhanced Destinations component with filtering and post display
- Improved error handling and loading states in various components
- Added FavoritePosts component for managing favorite blog posts
- Implemented Drafts functionality in UserDashboard

## Git Setup

This project is connected to a GitHub repository. To clone and set up the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/Ahmed-AIM/Travel-blog.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Travel-blog
   ```

3. Set up the remote (if not already done):
   ```bash
   git remote add new-remote-name https://github.com/Ahmed-AIM/Travel-blog.git
   ```

4. Push to the remote:
   ```bash
   git push new-remote-name main
   ```
