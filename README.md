# QoL Scripts

## codersawk

Dependencies:

* awk (tested with gawk)
* isutf8 (from `moreutils` package on Ubuntu)

Coder's Awk is a grep replacement for searching local repos. It will not search in (some) typical places you wouldn't want it to, only search text files, and limit the line length to the width of your console. It's bash so if you're grepping full-width characters or using a variable width font this won't work well.

If you pass a folder it will automatically recurse it. If you pass no folder, it will recurse the CWD.

Usage: codersawk query [file/folder]

