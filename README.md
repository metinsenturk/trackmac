# Time Tracker for Mac

This is a simple time tracker for OS X, originally written by @nat in python2. Well, tough I have some ideas on this project, for now, it is just an upgrade to python3.

If you run the download the original script and run `python trackmac.py` through terminal, you will still have see the magic and get a simple time tracker! What an amazing job! 10 years ahead, still runs like clockwork!

However, even tough python2 is still accesible within mac terminal, it may soon be out ouf mac, according to the [article](https://developer.apple.com/documentation/macos_release_notes/macos_catalina_10_15_release_notes) for macOS Catalina 10.15 Release Notes. That's why, in an attempt to make this project ongoing, I will be rewriting it using python3!

Finally, this is what my `trackmac` shows since I've forked the repository!

```
   26m     67%  Code
    8m38s  22%  Google Chrome
    3m 1s   7%  Terminal
      41s   1%  Finder
       8s   0%  Azure Data Studio

   38m28s Sitting at the computer
```

### Original README

```
# A simple time tracker for Mac OS X by Nat Friedman (nat@nat.org).
#
# Written May 6, 2010 in Munich, while a soft rain fell.
#
# Run this script in a terminal. It displays activity statistics 
# from the last 24 hours, like this:
#
# 1h 8m57s  70%  Google Chrome
#   14m17s  14%  Mail
#    8m11s   8%  iChat
#    3m16s   3%  Colloquy
#    1m28s   1%  1Password
#      43s   0%  Terminal
#      12s   0%  TextMate
#       4s   0%  Finder
#       4s   0%  SecurityAgent
#
# 1h37m12s Sitting at the computer
# 3h37m16s Doing something else
# 5h14m28s Total
#
# It detects idle time based on the screensaver, so lower your 
# screensaver delay or use a hot corner to improve accuracy.
#
# It doesn't save the data, so if you kill the script it loses the
# history.
```
