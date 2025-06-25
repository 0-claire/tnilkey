# TNILKey

This is an X11 keyboard layout for [TNIL](https://ithkuil.net) and [the fonts](https://github.com/shankarsivarajan/IthkuilBasic) designed for it
## Install
Copy this file to /usr/share/X11/xkb/tnilkey. Then run `setxkbmap tnilkey`. I advise having a terminal open to be able to reset the keyboard layout to us (`setkxbmap us`) or whatever you use. I use sxhkd to bind super+shift+backscape to `setxkbmap tnilkey` and super+backspace to `setxkbmap us`

## Keymap

Shift + vowel adds diareses: shift + a -> ä
Alt + vowel adds acute: alt + a -> á
Alt + shift + vowel adds circumflex: alt + shift + a -> â

Some consonants with shift, or shift and alt are remapped:

Shift + l: ļ
Shift + s: š
Shift + r: ř
Shift + t: ţ
Shift + c: č
Alt + c: ç
Shift + z: ž
Alt + z: ż


q: ż

They can be capitalized with caps lock
Caps lock + l: L
Caps lock + t: T
Caps lock + shift + l: Ļ
Caps lock + shift + t: Ţ
And so on

Some special symbols are also mapped:
[tbd]
