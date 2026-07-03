This directory contains MP3 recordings of a Unix code walkthrough that
Ken Thompson gave around 1975. These recordings were donated by Bob Kridle.
In his e-mail he says:

    I have three or four cassette tapes of Ken Thompson doing a read
    through of one of an early UNIX kernel code listing with a group of
    grad students at UC Berkeley while he was a visiting prof. there. This
    was an informal seminar that lasted six weeks or so. We went through
    the University of New South Wales source listing which only a few
    hundred pages long. Included in the group are Bill Joy, Kirk McKusick,
    Jeff Schreibman and some others I can't remember. Unfortunately I
    didn't make all the talks, so the tapes are not complete. However,
    there are some interesting tid-bits and exchanges.

    The seminar was held, I believe, sometime in the 1975-6 academic
    year when Ken was on sabbatical from Bell visiting Berkeley and
    bringing up perhaps the 2nd through 4th UNIX systems at Berkeley on
    PDP-11/40s and finally on a fully tricked out PDP 11/70 with three
    racks of memory that totalled 2 Megabytes as I remember. I think this
    might have been roughly the same time we put the INGRES Project PDP
    11/40 on the Arpanet as part of a massive network of perhaps 50-100
    systems nationwide.

    Unfortunately there is no metadata on the tapes such as exact
    dates or who the participants are other than Ken and me. Some
    likely possibilities are Bill Joy, Eric Allman, Jeff Schreibman,
    Kirk McKusick and/or Bob Epstein. I am passing this by them to see
    if anyone remembers who was there better than I. Ken was contacted
    in 2018 and gave me permission to further distribute these talks.

Eric Allman responded with this e-mail:

    Yes, I was there, as was Jeff Schriebman, who was at least partially
    responsible for setting it up. Kirk McKusick hadn't arrived
    in Berkeley yet. I don't recall about Bob Epstein or any of the
    others, but Bill Joy is likely; I'm pretty sure he was at Berkeley
    the same time as Ken was taking sabbatical -- they did a lot of
    work together on the instructional 11/70 on the first floor of Cory,
    which I think resulted in the "fifty changes" distribution, The class
    (seminar? tutorial? conversation?) took place in a tiny conference
    room one half floor down from the INGRES offices (273M Cory) that
    could only handle maybe 15-20 people and the room wasn't full.

   Jeff had printed out multiple copies of the V6 kernel onto some
   very flimsy paper with lots of carbons. I still have my copy, with
   annotations, at home. I didn't recall that there were recordings made
   -- that's really cool.

   The INGRES ARPAnet didn't come in until about 1976, and I'm pretty
   sure that was on an 11/70. I think there was an 11/40 on the 4th
   floor of Evans which was shared between math, statistics, and computer
   science which only ran UNIX 1/3 of the time. INGRES needed an 11/70
   because it required separated I/D space, and even with that ran in
   four processes: the user interface, which was just text input, the
   QUEL parser, the main database engine, and the utilities.

The Cleaner/ directory has versions of the recordings which Warren cleaned
up: some noise reduction, some pop removal and some compression.

The file Eric_Allman_Notes.pdf is a scanned copy of the Unix code that
was provided at the walkthrough. The scan has, unfortunately, truncated
the right-hand side of the 132-column printout.

As noted by Jonathan Gray, the code appears to be somewhere between
6th Edition Unix and the "50 changes" tape described by Mike O'Brien in:
https://www.tuhs.org/Archive/Applications/Spencer_Tapes/unsw3.tar.gz
file 'usr/sys/v6unix/changenotes'. Jonathan has also OCR'd the printout
and his version is in the tarball Eric_Allman_v6.tar.gz. He notes that
"Some of the changes are in other v6-derived trees. Some such as the
bootstrap and parity changes I couldn't find elsewhere."

You can see the 6th Edition Unix kernel source code here:
https://minnie.tuhs.org/cgi-bin/utree.pl?file=V6/usr/sys
