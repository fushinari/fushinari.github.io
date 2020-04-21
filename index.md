# Hi

I'm a guy who enjoys writing code, but doesn't know how to do it well enough just yet. So, any and all projects on my Github will be my experiments with how to do things the right way. They might be simple stuff, but they do work well enough for their purposes.

## [Reo](https://lastweakness.github.io/reo)

Reo is a dictionary application created using Python and GTK 3. It uses dictd and espeak-ng through subprocess to get definitions and pronunciations respectively. As you can probably understand, it doesn't try to be much. But it's made with the Linux desktop in mind and so, does work pretty well. The only actually interesting thing is the ways it parses the console output.

Even though it uses GTK 3 and has a very GNOME-like design, it's not meant to be a true GNOME application. It tries to be as simple as possible while still looking good enough.

There is also a Qt GUI with all the basic features but it's not as usable as the GTK GUI yet because I'm more familiar with GTK in terms of code.

## [corona.py](https://www.github.com/lastweakness/corona.py)

`corona.py` is a tiny script that pulls stats and news from Worldometers and displays it in a neat, reliable format. It also locally caches the stats and news. This allows it to work offline if necessary.

## [pkgup](https://www.github.com/lastweakness/rerun)

`pkgup` is a Python script made to simplify maintaining AUR packages for Arch. It's very simple, so it might not be suited for large packages but it is ideal for smaller packages. It has basic integrity checking, SHA256 updating,

## [Rerun](https://www.github.com/lastweakness/rerun)

Rerun was something made to make life easier on GNOME Wayland and also for switchable graphics. But that was 2 or 3 years ago. GNOME Wayland works well enough now that it's not needed and PRIME has also become much more mature.

That said, Rerun was my experiment with a few things:

- I tried to extract as much performance as possible from the Python and GTK 3 combo. Sadly, the launch times of a Python + GTK 3 application is still just as unsatisfactory as 2 or 3 years ago. BTW, Qt is ridiculously fast.
- Better CHANGELOG model (Didn't make much of a difference since I never made releases for anything after that...)
- Semantic Versioning (Same as above...)
- Better code standards compliance (Huge step towards writing better code.)
- Splitting into separate modules (yeah, i hadn't done that before at the time. Reo was a single Python file with a lot of horribly dirty code. Rerun was kind of the first step to the decently neat code in Reo now.)

## Other works

I have a lot of Python scripts that I wrote to make my Linux usage smoother, but none of them are on my Github yet and most of them will probably never be on Github. As for why... the code is a dirty mess. In my opinion, dirty hacks are better left never published when it doesn't help with stability.

I've also contributed a bit to [Komikku](https://gitlab.com/valos/Komikku). Not much but I try.

### Contact me

You can contact me through:

- [Telegram](https://t.me/fushinari)
- [E-mail](mailto:lastweakness@tuta.io)
- Discord: MaloBoi#5588
