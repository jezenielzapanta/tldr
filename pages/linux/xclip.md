# xclip

> Copy STDIN to clipboard or print clipboard to STDOUT.

- Copy output to clipboard:

`echo 123 | xclip -i`

- Paste clipboard:

`xclip -o > file.txt`

- Copy file to system clipboard:

`cat {{file.txt}} | xclip -sel clip`
