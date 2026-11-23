# Unix Timeline | README

* Copyright (C) 2026 Ludovic Hansen

Released under a BSD 2-clause like license as found in the LICENSE file

Based on [FabioLolix' BSD-timeline](https://github.com/FabioLolix/BSD-timeline)


## Goal

The goal of this is to provide a visual timeline of the genealogy of Unix history, including each system's relations to each other.

This is not intended as an up-to-date list of past and current Unix systems. As such, families of systems will be included instead of each individual case (This is mostly true for newer systems : i.e. FreeBSD will be included but not GhostBSD or NomadBSD.). I reserve the right to disobey this rule at my own discretion.

As sources can often be contradictory or even difficult to find, I relied heavily on the dates provided by Wikipedia as a eciding factor since it can be fairly neutral in my opinion. Any help in compiling the data is more than welcome.


## CONTRIBUTING

If you want to contribute, feel free to open an issue or make a pull request to add or modify any information. Please, try to use sourced data. If there are contradictions in some sources, we can discuss it.


## Installation

If you want to build your own version, make sure you have gnuclad
installed.

To install gnuclad, you can download the source at:

https://github.com/FabioLolix/gnuclad/archive/refs/tags/0.2.4.p1.tar.gz

or the original source at:

https://launchpad.net/gnuclad/trunk/0.2/+download/gnuclad-0.2.4.tar.gz

For Arch users, use the AUR: https://aur.archlinux.org/packages/gnuclad/

After you have installed gnuclad, to build just the SVG, run:
```sh 
gnuclad unxt.csv SVG unxt.conf
```

You can run the script `build.sh` to build the SVG, PNG, and the tarball
containing the source, as there is a bug currently in ImageMagick, I decided to switch to rsvg-convert so it's required to convert from SVG to PNG.

## Related resources

https://www.levenez.com/unix/

https://distrowatch.com/

https://archiveos.org/

https://github.com/sirredbeard/Awesome-UNIX

https://cgit.freebsd.org/src/tree/share/misc/bsd-family-tree

https://minnie.tuhs.org/cgi-bin/utree.pl

https://www.spinellis.gr/pubs/jrnl/2016-EMPSE-unix-history/html/unix-history.html

[https://williambader.com/museum/dell/xenixhistory.html](https://williambader.com/museum/dell/xenixhistory.html)
[https://levenez.com/unix/unix_letter.pdf](https://levenez.com/unix/unix_letter.pdf)

- [List of Unix systems](https://en.wikipedia.org/wiki/List_of_Unix_systems) — Wikipedia

- [List of BSD operating systems](https://en.wikipedia.org/wiki/List_of_BSD_operating_systems) - Wikipedia

- [Comparison of BSD operating systems](https://en.wikipedia.org/wiki/Comparison_of_BSD_operating_systems) - Wikipedia

- [History of the Berkeley Software Distribution](https://en.wikipedia.org/wiki/History_of_the_Berkeley_Software_Distribution) - Wikipedia
