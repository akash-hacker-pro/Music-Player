# Music Player Website

A dynamic and interactive music player website built with HTML, CSS, and JavaScript. This music player allows users to play, pause, skip, and navigate through a playlist of songs. It also supports functionality such as looping, shuffling, and displaying a music list.

## Features

- **Play/Pause Music:** Play or pause the current track with a button toggle.
- **Next/Previous Track:** Navigate through the playlist using next and previous buttons.
- **Playlist Control:** Shuffle and repeat options for playlist control.
- **Music List:** Display a list of available songs with details.
- **Progress Bar:** Visualize the progress of the current track.

## Technologies Used

- **HTML:** Structure and markup of the music player.
- **CSS:** Styling and layout of the player interface.
- **JavaScript:** Functionality and interactivity of the music player.
- **Pygame:** Not used in this project.

## Installation

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/rvrakash17/Music-Player-Website.git
   cd Music-Player-Website
   ```

2. **Project Structure:**
   Ensure your project directory contains the following files:
   - `index.html` (HTML file for the structure)
   - `style.css` (CSS file for styling)
   - `js/music-list.js` (JavaScript file containing the music list)
   - `js/script.js` (JavaScript file for player functionality)
   - `images/` (Directory for album cover images)
   - `songs/` (Directory for audio files)

3. **Add Your Music and Images:**
   Place your music files (e.g., `.mp3` format) in the `songs/` directory.
   Place album cover images (e.g., `.jpg` format) in the `images/` directory.

## Usage

1. **Open the Music Player:**
   Open `index.html` in a web browser to start using the music player.

2. **Controls:**
   - **Play/Pause:** Click the play or pause button to control the music.
   - **Previous Track:** Click the previous button to go to the previous song.
   - **Next Track:** Click the next button to skip to the next song.
   - **Shuffle/Repeat:** Toggle the repeat or shuffle mode using the corresponding button.
   - **Music List:** Click on a song in the music list to play it.

3. **Interacting with the Progress Bar:**
   - **Seek:** Click on the progress bar to seek to a specific point in the track.

## Code Explanation

### HTML Structure

- **Wrapper:** Contains the main structure of the music player, including controls, progress bar, and music list.
- **Top Bar:** Displays the current song title and additional options.
- **Image Area:** Shows the album cover for the currently playing song.
- **Song Details:** Displays the name and artist of the current song.
- **Progress Area:** Includes the progress bar and song timer.
- **Controls:** Contains buttons for play, pause, next, previous, and playlist options.
- **Music List:** Displays a list of available songs.

### JavaScript Functionality

- **Initialization:**
  - Loads the initial song and sets up event listeners for user interactions.
  
- **Music Control Functions:**
  - `playMusic()`: Plays the current song and updates the UI.
  - `pauseMusic()`: Pauses the current song and updates the UI.
  - `prevMusic()`: Plays the previous song in the playlist.
  - `nextMusic()`: Plays the next song in the playlist.
  
- **Progress Bar Updates:**
  - Updates the width of the progress bar and song timers as the song plays.
  
- **Playlist Handling:**
  - Displays and updates the music list with song durations.
  - Handles clicks on the music list to play selected songs.

- **Repeat and Shuffle:**
  - Allows users to set the playlist to repeat or shuffle.

## Author

- **Akash R**
