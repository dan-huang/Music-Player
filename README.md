Music Player
============

Fork from [bpolat's Music Player](https://github.com/bpolat/Music-Player)


Major Changes
============

When screen is locked while music is playing:
  * Buttons('next track', 'last track' and 'pause or play') can be clicked.
  * Music name, album name, artist, cover image and music progress will show.
  * Earphone will do things right too.
  
Slider smoothly slides when progress value changes.

If current track is the first track, Swipe Right GestureRecognizer or Clicking 'previous track button' will go to the last track.

Similar behavior if current track == the last track.

Remove some large music files for debug purpose.

Bugs need to be fixed
=========

Music progress on lock screen will be wrong if user pause/play on lock screen. (fixed)

  




