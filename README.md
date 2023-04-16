# How to use xkcdd

`xkcdd` downloads comics and metadata from xkcd.com and writes them out to files in the current directory. The files will be named with the comic's number followed by an underscore and then the comic's name. For example, the image and metadata of  xkcd 1287, "Puzzle", would be written to the files `1287_puzzle.jpg` and `1287_puzzle.json` respectively.

`xkcdd` only accepts a single argument, either a number or a url. If more than one argument is given, only the first is used.

Giving `xkcdd` a numerical argument will download the comic with that number.  Only integer numbers greater than zero without any leading zeros are accepted.

Alternatively, you could give `xkcdd` a url, such as `xkcdd https://xkcd.com/1287/`. This works as expected, downloading the comic linked to by the url. The leading `https://` is optional.

Running `xkcdd` without any arguments downloads the most recent comic and metadata.
