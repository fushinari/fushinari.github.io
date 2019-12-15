## What is Reo?

Reo is a dictionary application made using Python and Gtk+ 3. It has some simple features but nothing too fancy.

### Screenshots

Light Mode                                                   |  Dark Mode
:-----------------------------------------------------------:|:-----------------------------------------------------------:
![Light Mode](https://lastweakness.github.io/assets/ss.png)  |  ![Dark Mode](https://lastweakness.github.io/assets/ss1.png)

### Features

 - Properly color-coded and formatted definitions
 - Random Word search: To maybe try learning some new words
 - Custom Definitions: Add your own definitions with the Pango Markup Syntax for formatting
 - Lightweight: 1 mb only and further reducible (It does nothing on its own, so yeah)
 - Support for GNOME Dark Mode, gtk3-nocsd and most current Linux distributions.

### Requirements

 - DICT official client and server (dictd and dict, they may or may not be in separate packages depending on the Linuxte distribution)
 - WordNet 3.1 or 3.0 database for dictd (dict-wn)
 - Python 3
 - Python GObject
 - Gtk+ 3.20+
 - eSpeak-ng (For pronunciations and audio)

### Status

Reo was originally made to be a simple and beautiful alternative to WordWeb, made with Linux in mind. It was entirely made for personal use, especially because I used to write a lot while I was still a Windows user. Even though I've almost completely stopped writing, I do still use Reo almost everyday and I have a hotkey assigned to it.

But this also means that while I did want it to be more advanced at one point, I don't think I'll be adding many more features. Mostly, it will be bug fixes, cleaning up the code, improving the implementation of everything and minor features that don't take much effort. I had made it for personal use and as such, not everything is done the way it's really meant to be done. I plan to set that right one step at a time as I learn through mistakes.

### How did Reo come to exist?

I was looking for a decent dictionary application on Linux and came across [this answer](https://askubuntu.com/a/417132). The first part in specific, with dictd and espeak, really seemed nice. First, I made a Gambas application for the purpose called "Define".  

It had a lot of features including really advanced customization options. But it had a lot of issues including color-coding being impossible. The customization options were also to make up for the lack of native appearance (even though it used Gtk3 too).  

Considering all that, I rewrote the application in Python and called it "PyDict". Yeah, very original, I know. Google Drive was my 'version control' until then. Soon, when I made some huge changes to how it worked, I renamed it to "Reo" and put it up on Github.
