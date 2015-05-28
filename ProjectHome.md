Tailer has moved to [github](https://github.com/six8/pytailer)!

Python tail is a simple implementation of GNU tail and head.

It provides 3 main functions that can be performed on any file-like object that supports seek() and tell().

  * tail - read lines from the end of a file
  * head - read lines from the top of a file
  * follow - read lines as a file grows

It also comes with pytail, a command line version offering the same functionality as GNU tail. This can be particularly useful on Windows systems that have no tail equivalent.