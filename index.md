## Hi.

I'm a guy who enjoys writing code, but doesn't know how to do it well enough just yet. So, any and all projects on my Github will be my experiments with how to do things the right way. They might be simple stuff, but they do work well enough for their purposes.

### [Reo](https://www.github.com/lastweakness/reo)

Reo is a dictionary application created using Python and Gtk3. I call it an application, but really, it's just a simple script and the UI is done with Glade. It uses dictd and espeak-ng through subprocess to get definitions and pronunciations respectively. As you can probably understand, it doesn't try to be much. But it's made with the Linux desktop in mind and so, does work pretty well. The only actually interesting thing is the ways it parses the console output.

Even though it uses Gtk3 and has a CSD-style UI, it's not meant to be part of the GNOME group. It tries to be as simple as possible while still looking good enough. However, I've tried to make it work well across many configurations including Gtk3-NoCSD and slightly older Gtk versions.

The code is not high quality but is quite readable and easy to modify.

### [Rerun](https://www.github.com/lastweakness/rerun)

Rerun was something made to make life easier on GNOME Wayland and also for switchable graphics. But that was 2 or 3 years ago. GNOME Wayland works well enough now that it's not needed and PRIME has also become much more mature.

That said, Rerun was my experiment with a few things:
 - I tried to extract as much performance as possible from the Python and Gtk3 combo. Sadly, the launch times of a Python+Gtk3 application is still just as unsatisfactory as 2 or 3 years ago.
 - Better CHANGELOG model
 - Semantic Versioning
 - Better code standards compliance
 - Splitting into separate modules (yeah, i hadn't done that before)

### Other works

I have a lot of Python scripts that I wrote to make my Linux usage smoother, but none of them are on my Github yet and most of them will probably never be on Github. As for why... the code is a dirty mess. In my opinion, dirty hacks are better left never published when it doesn't affect stability.

### Contact me
You can contact me through:
 - [Telegram](https://t.me/fushinari)
 - [E-mail](mailto:lastweakness@tuta.io)
 - Discord: MaloBoi#5588
