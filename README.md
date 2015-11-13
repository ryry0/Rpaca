Package manager inspired by pacman and [lfs-me](https://github.com/FSMaxB/lfs-me)!

TODO:

flags:

* ~~-d|--download~~
* ~~-c|--compile~~
* ~~-b|--build~~
* ~~-i|--install~~
* ~~-r|--remove~~
* ~~-l|--list-installed~~
* -s|--search
* ~~-I|--full-install~~
* ~~-L|--list-installed-files~~
* --list-dependencies
* --delete-all-packages
* --delete-all-sources
* --delete-all-downloads
* --help
* --debug
* --log

other: 

* Check if already downloaded.
* Check if already installed.
* Check if already uninstalled.
* Run removal check fully and not per-file.
* Report if stuff is successful, and only run if it is.
* make each flag a boolean flag, so you can run any combination.
* swizzling(?)
* Prevent install if dependencies aren't met
* fix output when there is no file provided
* meta packages
* tie to rss feed or other site for automatic updating? possible sites: [freshcode](http://freshcode.club/) [fsf](http://directory.fsf.org/wiki/Main_Page)
[archlinux feeds](https://www.archlinux.org/feeds) gentoo feeds
