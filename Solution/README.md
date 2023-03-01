### Using a Queue to manage a playlist

**Branch Name:** usingstacksandqueues-prework

**RDE workfows:**
* `rde wflow run stacksandqueues-prework-queues-musicplayerapp`
* `rde wflow run stacksandqueues-prework-queues-playlisttest`

Expected time required: 15 min

The included code represents a Music Player app and the music player's internal playlist
functionality. This is not the same type of playlist that the user would manage, it is the list
that would get sent to the music player app where songs are removed from the list once they are
played. Complete the included `Playlist` class in order to implement the following functionality:

* `addSong()` : adds a song to the end of the playlist.
* `getNextSong()` : returns the next song to be played, which should only be played once.
  * If there is no next song in the playlist, `getNextSong()` should return `null`.

Run the `MusicPlayerApp`'s `main()` method to test your implementation. Take a look through the comments in the
source to see what it is doing.

HINTS:
* [Are there any error conditions I've missed?](hints/hint-01.md)
