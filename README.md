# YouTube Clone

A React-based YouTube Clone that replicates core features of YouTube, including video browsing, searching, and playback.

## Features

- **Home Page:** Displays trending and recommended videos.
- **Search Functionality:** Search for videos using keywords.
- **Video Player:** Watch videos with playback controls.
- **Video Details:** View video title, description, views, likes, and channel info.
- **Related Videos:** See suggestions based on the current video.
- **Responsive Design:** Works seamlessly on desktop and mobile devices.
- **Dark/Light Mode:** Toggle between themes.
- **Routing:** Navigate between pages using React Router.
- **API Integration:** Fetches data from the YouTube Data API (or mock API).

## Technologies Used

- **React** (with Hooks)
- **React Router**
- **Axios** (for API requests)
- **Material-UI** or **Tailwind CSS** (for UI components)
- **YouTube Data API v3** (or mock data)
- **Context API** (for global state management)

## Project Structure

```
/src
    /components
        - Navbar.jsx
        - Sidebar.jsx
        - VideoCard.jsx
        - VideoPlayer.jsx
        - SearchBar.jsx
        - RelatedVideos.jsx
    /pages
        - Home.jsx
        - SearchResults.jsx
        - VideoDetail.jsx
    /context
        - ThemeContext.js
        - VideoContext.js
    /utils
        - api.js
    App.js
    index.js
```

## Setup Instructions

1. **Clone the repository:**
     ```bash
     git clone https://github.com/your-username/youtube-clone.git
     cd youtube-clone
     ```

2. **Install dependencies:**
     ```bash
     npm install
     ```

3. **Configure API Key:**
     - Create a `.env` file and add your YouTube Data API key:
         ```
         REACT_APP_YOUTUBE_API_KEY=your_api_key_here
         ```

4. **Start the development server:**
     ```bash
     npm start
     ```

## Key Concepts Covered

- **Component-based Architecture:** Modular and reusable components.
- **State Management:** Using React Hooks and Context API.
- **API Integration:** Fetching and displaying dynamic data.
- **Routing:** Navigating between different pages.
- **Responsive UI:** Adapting layout for various devices.
- **Theming:** Implementing dark and light modes.
- **Error Handling:** Graceful handling of API errors and loading states.

## Future Improvements

- User authentication and personalized recommendations.
- Comment section and video uploads.
- Infinite scrolling and advanced filtering.

## License

This project is licensed under the [MIT License](LICENSE).

---

**Made with React ❤️**