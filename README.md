# Music Playlist Manager

## Overview
The Music Playlist Manager is a Java-based application that allows users to manage a playlist of songs. It provides functionality to view a song database, create and manage playlists, and perform various operations such as adding, removing, reordering, and sorting songs. The application uses a custom linked list implementation and follows the MVC (Model-View-Controller) architecture.

## Features
- View a database of songs
- Add songs to a playlist
- Remove songs from a playlist
- Reorder songs in the playlist
- Sort the playlist alphabetically by song title
- Clear the playlist
- Extendable functionality (e.g., randomize playlist, remove duplicates)

## Project Structure
- **`MusicPlaylistManager.java`**: Main application class with GUI setup.
- **`LinkedList.java`**: Generic linked list implementation.
- **`BetterLinkedList.java`**: Extended linked list with additional functionality.
- **`Song.java`**: Class representing a song with metadata.
- **`PlaylistController.java`**: Controller for playlist operations.
- **`SongDatabaseController.java`**: Controller for the song database.
- **`songs.csv`**: CSV file containing the song database.

## Setup Instructions
1. Clone or download the repository to your local machine.
2. Open the project in your preferred Java IDE (e.g., IntelliJ IDEA, VS Code, Eclipse).
3. Ensure you have Java 8 or higher installed.
4. Run the `MusicPlaylistManager.java` file to start the application.

## Usage
1. **View Song Database**: The application displays a list of songs from the database.
2. **Create Playlist**: Add songs from the database to the playlist.
3. **Manage Playlist**:
   - Add or remove songs.
   - Reorder songs using "Move Up" and "Move Down" buttons.
   - Sort the playlist alphabetically by title.
   - Clear the playlist.
4. **Extend Functionality**: Add custom features such as randomizing the playlist or removing duplicates.

## Implementation Details
- **Data Structures**: The playlist is managed using a custom linked list (`BetterLinkedList`) that extends a generic linked list (`LinkedList`).
- **Sorting**: The playlist can be sorted using a bubble sort algorithm implemented in `BetterLinkedList`.
- **MVC Architecture**: The application separates concerns into models (`Song`), views (GUI), and controllers (`PlaylistController`, `SongDatabaseController`).

## Extensions
The project is designed to be extendable. Some ideas for extensions include:
- Adding a button to randomize the playlist order.
- Removing duplicate songs from the playlist.
- Saving and loading playlists.
- Adding functionality to play songs using audio files.

## Testing
Test the application by:
- Adding and removing songs at different positions.
- Reordering songs in the playlist.
- Sorting the playlist and verifying the order.
- Handling edge cases such as empty playlists or invalid indices.

## License
This project is for educational purposes and is not licensed for commercial use.

## Acknowledgments
- Java Swing for GUI components.
- GeeksforGeeks for linked list and sorting algorithm references.
