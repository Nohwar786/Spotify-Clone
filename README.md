# Spotify Premium Clone

A responsive music streaming web application inspired by Spotify, built using **HTML, CSS, and JavaScript**. The project features a dark-themed interface, music library, audio playback controls, song search, and a login interface.

## 📌 Project Overview

The Spotify Premium Clone recreates the look and basic music-listening experience of a modern music streaming platform. Users can browse available tracks, search for songs or artists, control playback, adjust volume, and navigate between tracks through a simple web interface.

This is a front-end demonstration project created for learning and portfolio purposes. It is not affiliated with or officially connected to Spotify.

## ✨ Features

* **Login Interface:** Login modal with username and password fields.
* **Music Library:** Displays songs with cover artwork and artist information.
* **Play and Pause:** Start or pause audio playback.
* **Next and Previous:** Navigate between tracks.
* **Song Search:** Search the music library by song title or artist name.
* **Progress Bar:** View and adjust the current playback position.
* **Volume Control:** Adjust the audio volume.
* **Automatic Track Switching:** Automatically play the next track when the current track finishes.
* **Persistent Login State:** Uses browser local storage to remember the demo login state.
* **Responsive Design:** Adapts the interface to different screen sizes.
* **Dark Theme:** Uses a dark interface with green accents inspired by Spotify's visual style.

## 🛠️ Technologies Used

* **HTML5** — Application structure and content.
* **CSS3** — Styling, layout, animations, and responsive design.
* **JavaScript** — Search, login interface, playback controls, and application interactions.
* **HTML Audio API** — Audio playback and track controls.
* **Local Storage** — Stores the demo login state in the browser.

## 📂 Project Structure

```text
Spotify-Clone/
│
├── image/          # Music cover images
├── songs/          # Audio files used for playback
├── index.html      # Main application (HTML, CSS, and JavaScript)
├── .gitignore      # Git ignore configuration
└── README.md       # Project documentation
```

## 🚀 How to Run the Project

### Prerequisites

* A modern web browser such as Google Chrome, Microsoft Edge, or Firefox.
* Visual Studio Code (recommended, but optional).
* The required audio files if you want to test music playback.

### Step 1: Clone the Repository

Open a terminal and run:

```bash
git clone https://github.com/Nohwar786/Spotify-Clone.git
```

### Step 2: Open the Project Folder

```bash
cd Spotify-Clone
```

### Step 3: Launch the Application

Open the project folder in Visual Studio Code.

You can either open `index.html` directly in your browser or use the **Live Server** extension in Visual Studio Code for local development.

### Step 4: Use the Application

1. Open the application in your browser.
2. Enter a username and password in the login interface.
3. Explore the available music library.
4. Search for a song or artist.
5. Use the playback controls to play, pause, or change tracks.
6. Adjust the playback position and volume.

**Note:** The login form is a front-end demonstration. It checks that the fields are not empty; it does not provide real authentication or account security.

## 🎵 Audio Files

The application uses local audio file paths for music playback. The required audio files must be available in the expected `songs/` directory for playback to work correctly.

The `.gitignore` file excludes the `songs/` directory. As a result, audio files in that directory may not be included in the GitHub repository. If you clone the project and playback does not work, check whether the required audio files are present and whether their paths match those referenced by the application.

## 🔐 Login Functionality

The login interface uses browser `localStorage` to save a simple demo login state. The application can retain this state across page reloads until the user logs out or the stored value is cleared.

This is **not a secure authentication system**. It does not validate credentials against a server or database and should not be used to protect real user accounts.

## 📱 Responsive Design

The application includes responsive CSS rules to improve usability on smaller screens, including a layout adjustment for screens narrower than 768 pixels.

## 🔮 Future Improvements

* Implement secure authentication with a backend.
* Add user registration and profile management.
* Store playlists and favorites.
* Add a database for music and user information.
* Improve mobile navigation and accessibility.
* Deploy the application with properly hosted audio assets.
* Add audio streaming from a backend or authorized music service.

## 🎯 Learning Outcomes

Through this project, I practiced:

* Building a web interface using HTML and CSS.
* Implementing interactive features with JavaScript.
* Working with the HTML Audio API.
* Managing application state with browser local storage.
* Implementing search and music navigation.
* Creating a responsive web layout.
* Organizing a front-end project for GitHub.



*Built as a front-end learning project to practice web development and interactive music-player functionality.*
