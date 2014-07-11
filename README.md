# Undead U.S. Keyboard Layout

## Removes dead keys from default U.S. Mac keyboard layout.

## Motivation

I wanted to map some keys in Vim and decided to try to remap `<Alt-u>` and then began to rip out my hair in confusion and frustration at what was incredibly inconsistent behavior. It turns out that the keys are dead keys reserved for doing accent marked and umlauts for those german lovers out there.

Therefore I sought to remove those characters and mapped them to moderately useful math characters that I might actually use. While doing this I thought to replace other keys as well with more useful characters, and so `Undead Fancy` was born.

Therefore, there are two files here:
- `Undead U.S.`: This one replaces only the dead keys and changes nothing else. This is what you probably want.
- `Fancy Undead U.S.`: This one replaces the dead keys (same as above) and expands by replacing more characters that I didn't like. It's mostly a personal file.

## Installation

- Simply copy the files to `~/Library/Keyboard Layouts/`. I've provided a simple script `install.sh` that does that for you.

- Then you go to `System Preferences > Keyboard > Input Sources`. Press the `+` button to add a new layout, and scroll down the list to `Other`. There you should see `Undead U.S.` and his fancy brother. Press `Add`.

- Now by default the input source selection button should pop up in your menu bar and you can choose it from there.
