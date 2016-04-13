---
title: Picking a GNU+Linux distribution
layout: guide
authors: [
	"Patrick 'tyil' Spek &lt;p.spek@tyil.work&gt;"
]
---

## Foreword
This is a small guide to hopefully help you settle on a certain GNU+Linux
distribution. This guide is written because the question "which distro should I
pick" comes up a lot, and a single reference document to picking a distro would
be much more useful than trying to answer the question to each one
individually.

Be aware that this is not a full, comprehensive guide. You should pick whatever
distro you like, and don't be afraid to experiment a with other distros. If you
feel like a distro should be mentioned, send in a MR on this repository.

## Which distro should I pick for …?
### Beginner friendly
#### [Lubuntu][lubuntu]
Lubuntu is a spin-off from [Ubuntu][ubuntu]. It comes with a graphical
installer and sports the LXDE desktop environment, which is ment to be
lightweight. LXDE by default comes with a taskbar, a "start" menu and desktop
icons which should be pretty straight-forward to anyone coming from a
Windows-like system.

#### [Xubuntu][xubuntu]
Xubuntu is a spin-off from [Ubuntu][ubuntu]. Like Lubuntu, it comes with
a graphical installer and the default UI is pretty similar to Windows.

### Customizability
#### [Funtoo][funtoo]
A spin-off from [Gentoo][gentoo]. Funtoo is against systemd, and uses OpenRC
instead. Other than that, it is pretty similar to Gentoo nowadays.

#### [Gentoo][gentoo]
Gentoo is often hailed as the go-to distribution if you want to customize
**everything**. It has an advanced package system that uses so-called **USE
flags** to indicate which features you want and which ones you don't. This
brings along the downside of having to compile all your packages yourself, save
for a very small set of packages which have ***-bin*** versions available (such
as Firefox and LibreOffice).

#### [Ubuntu netinstall][ubuntu]
This is the most minimal version of Ubuntu available. This means that you have
a small starting base which you can setup completely to your liking. Ubuntu
supports a PPA system to easily add in software that's missing from the main
repositories. There's also a big community behind it which is usually pretty
helpful and friendly.

### Freedom
#### [Parabola GNU/Linux][parabola]
A distribution based on [Archlinux][archlinux]. It does not allow installation
of any non-free software.

#### [Trisquel][trisquel]
A free distribution based on [Debian][debian].

### Lightweight
#### [Debian netinstall][debian]
The netinstaller for Debian is the most minimal version you can start out with.
It's stable, produces a very small OS once done installing is incredibly
stable. Be aware that Debian by default does not allow non-free software in the
main repos, so not all hardware may be supported out of the box.

#### [Lubuntu][lubuntu]
Lubuntu's LXDE desktop environment is made specifically to be usable on systems
with low resources.

### Stability
#### [Debian][debian]
Debian is often described as the most stable GNU+Linux distribution around.
The release cycles are incredibly slow, which is a good thing when going for
stability in general. Before packages hit the stable repositories, they have
been thoroughly tested to make sure that they won't break anything.

### Ricing
Every distro can be customized to be Your Special Snowflake™. Just pick
whatever distribution's package manager feels best to you, and start
customizing everything you want different.

## Why isn't … in this list?
### [Archlinux][archlinux]
Archlinux doesn't provide anything special. People often claim it's
"customizable", but it's no more customizable than Ubuntu itself. The community
is also very unwelcoming to people who want to customize it beyond what the
devs intended.

There's claims of it being "light-weight", but a debian netinstall is smaller
than a base Archlinux installation. This is mostly due to Archlinux including
development headers in all their packages, which is completely unneeded for a
binary package distribution.

### Everything not mentioned
It either doesn't fit the categories, or I just don't know about the
distribution. I'd greatly appreciate any help in maintaining this list, and
that includes suggestions for other distros in the list. You can have one
added by sending in a MR on the repository.

[archlinux]: https://www.archlinux.org/
[debian]: https://www.debian.org/
[funtoo]: http://www.funtoo.org/Welcome
[gentoo]: https://www.gentoo.org/
[lubuntu]: http://lubuntu.net/
[parabola]: https://www.parabola.nu/
[trisquel]: https://trisquel.info/
[ubuntu]: http://www.ubuntu.com/
[xubuntu]: http://xubuntu.org/
