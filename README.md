Simple script to synch subtitles based on a correctly synched subtitle file.
It's useful if you have subtitles in different languages but are meant for different audio/video codecs so you can't simply adjust by a fixed number
Example, you have spanish subtitles for a movie in h.x265 but your movie file is h.x264. If you have the English subtitles for h.x264 you can use that file to synch the timestamps
in your spanish file. All you need to do is make sure the text in the first and the last item of the file match in their content, the script adjusts the rest of the items based on
a ratio (synched file time length / unsynched file time length) and how far away the current item is (timewise) from the first item.
