The need for this comes up especially with [Squeezebox Server](http://wiki.slimdevices.com/index.php/SlimServer): if you rip your CD collection both to FLAC (for the SqueezeBoxes) and MP3 (for your iPod etc.) and store the files together, Squeezebox Server will find 2 copies of every song, and will be happy to play either one (or both).  Likewise if you have high and low-quality MP3s, or ogg files for the Squeezebox plus low-quality MP3s for your undersized MP3 player...

You can use mutl to build a tree of symlinks with the same organization as your main library, consisting only of links to the "best available quality" file for each duplicated track.  It is implemented as a Python script.

Or you can build e.g. an MP3-only tree, so that iTunes will not see your FLACs (which it doesn't know how to handle anyway).

MUTL is pronounced approximately like "muddle", which is what it does... muddle through your music collection.