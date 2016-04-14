aux
---

Audio utilities.

* `artless` (POSIX shell)

  Given a list of directories, find audio files with missing artwork.
  Requires [mediainfo][mi]

* `bitrate` (POSIX shell)

  Print an MP3 file's bitrate. Requires [mediainfo][mi]

* `blam` (bash)

  Convert stuff to mp3 using ffmpeg.

* `brainless` (POSIX shell)

  Given a list of directories, find audio files not tagged by
  MusicBrainz. Requires Requires [mediainfo][mi]

* `mpd-diff` (bash)

  Show a diff between mpd's library and the files in mpd's
  `music_directory`.

* `mudir` (Python)

  Given a list of directories, find audio files not sorted into
  `$ARTIST/$ALBUM` directory structure. Requires [mutagen](https://code.google.com/p/mutagen/).

* `untunes` (Python)

  Given an iTunes library file and list of directories, find files not
  present in iTunes.

[mi]: https://mediaarea.net/en/MediaInfo
