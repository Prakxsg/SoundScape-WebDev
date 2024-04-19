Description
This project is a simple web-based music player that allows users to listen to a curated list of songs. Users can navigate through the song list, play/pause songs, skip to the next or previous song, and see the progress of the currently playing song.

**Features**
1. Play/pause functionality
2. Next and previous song navigation
3. Progress bar indicating song playback progress
4. Display of song information (title and cover image)
5. Responsive design for various screen sizes


**Usage**
1. Clone the repository to your local machine.
2. Open the index.html file in a web browser to launch the music player.
3. Use the play/pause button to control song playback.
4. Use the next and previous buttons to navigate through the song list.
5. The progress bar indicates the playback progress of the current song.

**Technologies Used**
1. HTML
2. CSS
3. JavaScript

**Project Structure**
index.html: HTML file defining the structure of the music player interface.
style.css: CSS file containing styles for the interface elements.
script.js: JavaScript file providing functionality for the music player.
playing.gif: GIF file used for indicating song playback.
logo.jfif: JPEG file containing the logo of the social network.
covers1.jpg: JPEG file containing cover images for songs.
bg1.jpg: JPEG file used as the background image for the music player interface.
songs/: Folder containing audio files (.mp3) for each song.
covers/: Folder containing cover images (.jpg) for each song.

**Note**
Please note that the audio files and cover images for the songs are not included in the repository. You will need to add your own audio files and cover images to the respective folders (songs/ and covers/) in order to use the music player.

JavaScript Functionality
The script.js file adds interactivity and functionality to the music player. Here's how it works:

1. Initialization: The script starts by initializing variables and selecting elements from the HTML document using document.getElementById() and document.getElementsByClassName().
2. Song Data: An array named songs is defined, containing objects with information about each song, including the song name, file path, and cover image path.
3. Rendering Song List: The script dynamically renders the list of songs by iterating over the songItems array and updating the <img> and <span> elements with the appropriate song information.
4. Playback Controls: Event listeners are added to the play/pause button (masterPlay) and the next/previous buttons (next and previous). When clicked, these buttons control song playback, updating the audio element (audioElement) with the selected song's file path and updating the song information displayed on the interface.
5. Progress Bar: An event listener is added to the progress bar (myProgressBar) to update the playback progress of the current song.
6. Play Song: When a song in the list is clicked, its corresponding play button (songItemPlay) is activated. The script updates the audio element with the selected song's file path and starts playback.
