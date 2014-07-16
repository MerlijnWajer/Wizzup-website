.. Wizzup documentation master file, created by
   sphinx-quickstart on Sun Jul 24 18:22:16 2011.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Wizzup.org
=====================

My name is Merlijn (Boris Wolf) Wajer; born in Amsterdam, 16 December 1990
I am 22 years old and currently attend the University of Amsterdam, currently
going for my Master of Science in Computational Science after finishing a
Bachelor of Science in Computer Science.

My `Curriculum Vitae <http://wizzup.org/cv.html>`_ (detailed contact info removed).

I'm generally very open to all kinds of (weird|cool) questions, so please do not
hestitate to contact me.

Contact
-------

You can contact me by mailing me (merlijn) at this website; wizzup.org. (I'm
sure you can construct my email address by now, if you're a human anyway.)

PGP Key ID: 6F12E4C8


Teaching
--------

I regularly assist courses at the University of Amsterdam since 2009.
If you're a student, please don't hesitate to drop my an email.

Blog
----

My web log can be found at http://blog.wizzup.org
I try to post there regularly, but so far that has not worked out.

Hobbies and Interests
---------------------

Activism and Freedom
~~~~~~~~~~~~~~~~~~~~

I have a partiular interest in tools that empower activists. As of 2013, I am
active in the `Hart voor internet vrijheid
<http://hartvoorinternetvrijheid.nl>`_ foundation dedicated to fight censorship
on the internet. If you know of any interesting problems or projects,
please do let me know. Recently I have also gained interest in the Tor project
and hope to contribute in the near future.

Aside from Computer science activism, I also consider myself a
`Militant Atheist
<http://www.ted.com/talks/richard_dawkins_on_militant_atheism.html>`_.

Computer Science
~~~~~~~~~~~~~~~~

I like messing around with Linux. In particular I've had a lot of fun with my
sheevaplug(s) running Gentoo Linux. These days I use a Samsung Chromebook
running Gentoo Linux as my main machine.

The wiki dedicated to mainlining and supporting Exynos hardware is also hosted
by me on this server. We're still looking for many developers and volunteers:

    http://linux-exynos.org/wiki/Main_Page

Music and Sports
~~~~~~~~~~~~~~~~

As for sports; I've been practicing Aikido since I was a child, with a few pauses.

I also like reading and music: Ambient, Classical, New Wave, Black/Viking Metal.

The following bands occupy a special place somewhere inside my head:

* Coil (and The Threshold Houseboys Choir)
* Nine Inch Nails
* Kraftwerk
* Rome (not the french rap band)
* The Cure

Projects
--------

Some of my projects will be quickly covered here, all my other small projects
can be found on "`Het Grote Bos <http://hetgrotebos.org/wiki>`_",
the umbrella project for much of my projects,
or alternative on one of my git hosts,
`git.wizzup.org <http://git.wizzup.org/>`_ and my
`Github account <http://github.com/MerlijnWajer>`_.

Projects I participate in:

    *   `SRL`_

Projects I have started (and participate in):

    *   `Simba`_ (In collaboration with several SRL developers: Niels AD,
        Raymond van Venetië, Benjamin Land, John Peel)
    *   `SRL-Stats`_
    *   `πϱTorrent`_ (In collaboration with Bas Weelinck)
    *   `Tracy`_
    *   `Rubbernose`_
    *   `Neversearch`_
    *   `uinput-mapper`_
    *   `Least`_ (In collaboration with Bas Weelinck)
    *   `SNARP`_

Tracy
~~~~~

`Tracy <http://hetgrotebos.org/wiki/Tracy>`_ is a cross architecture System call
tracing and injection framework for Linux (\*BSD support will hopefully follow).


Neversearch
~~~~~~~~~~~

`neversearch <http://hetgrotebos.org/wiki/neversearch>`_ is a simple but powerful
program that allows you to assign tags to files or directories, if your file
system supports xattr (eXtended ATTRibutes). This can make your life a lot
easier when managing photos or other files.

There are many possible uses cases, see the neversearch page for more info.


uinput-mapper
~~~~~~~~~~~~~

`uinput-mapper <http://hetgrotebos.org/wiki/uinput-mapper>`_ is a
simplistic but powerful project to create (virtual) input devices that can be
fed (and change) events from other input devices. Possible use cases:

- Creating virtual joysticks from a keyboard device. (For example: a device with
  physical joysticks that exposes keyboard device)
- Creating a mouse from joystick input.
- Networked input (it works fine over ssh, etc)
- Combining or splitting input devices.

Immature project, but works for my use cases. I mostly created this for an
arcade machine that exposed two joysticks as a single keyboard device.

.. figure:: img/uinput.png
    :scale: 70 %

    map program running

.. figure:: img/uinput2.png
    :scale: 70 %

    /dev/input *before* the map program is running and while the map program is
    running.


Rubbernose
~~~~~~~~~~

`Rubberfuse <https://hetgrotebos.org/wiki/rubbernose>`_ is a continuation of
the work done on Rubberhose-FS by Julian Assange et al. We're still in the
planning phase.

SRL
~~~

`SRL <https://villavu.com/>`_ is the first project I ever participated in and it
has mainly been the base of my current programming knowledge. SRL was
initially a library created to macroing a game called *Runescape*, but has since
turned into a community full of interesting people, talented programmers and
generally cool fruitcakes. The library still works, by the
way. SRL has lots of *Scripts* that each perform their own task on *Runescape*.

Simba
~~~~~

`SRL`_ is interpreted by a program called Simba, created by
members of the SRL community. `Simba <http://wizzup.org/simba>`_.
Simba can perform many kind of tasks, including faking mouse movements and key
presses, finding bitmaps and colours and reading text from the screen.

Simba is GPL-3 licensed and Open Source and Free Software.

.. figure:: img/simbalinux.png
    :scale: 25 %

    Simba running on my old Linux distribution, Ubuntu Linux.

SRL-Stats
~~~~~~~~~
`SRL-Stats <http://wizzup.org/stats>`_ was created to keep track of the progress
and use of SRL. SRL *Scripts* can gather statistics from their actions and
submit them to SRL stats.

Currently the most popular script has ran for
*954 days, 8:49:00 with 154756 individual commits.*, which is pretty impressive.

.. figure:: img/stats_site.png
    :scale: 25 %

    The SRL Stats website as on http://stats.villavu.com.
    The design was taken from some free templates site, as I stink at web design
    - at least for now.


.. figure:: img/stats.png
    :scale: 50 %

    An example of a graph generated by SRL stats, this is of the fifth month of
    2011.


πϱTorrent
~~~~~~~~~

`πϱTorrent <http://wizzup.org/pyroTorrent>`_ is a web interface to rTorrent. It
was written in Python because I got so fed up with all the crappy PHP
interfaces and generally just PHP being crappy.

It is still work in progress, but it can do some basic stuff like list
and add torrents, connect to multiple rtorrents at once, manage users,
basic login authentication.


.. figure:: img/pyrotorrent1.png
    :scale: 25 %

    pyroTorrent showing my sheevaplug seedbox(e). (Note that none of these
    downloads are illegal, so bite me)


.. figure:: img/pyrotorrent2.png
    :scale: 25 %

    Login screen.


Oh, and `πϱTorrent`_ is really fast compared to any of the PHP web interfaces.

Least
~~~~~

The not so minimalisitic PDF viewer.

`Least <https://github.com/MerlijnWajer/least>`_ is a very simple OpenGL based
PDF viewer. We have some great features we wish to implement, but so far I
have not found the time.

SNARP
~~~~~

Simple Noise Activated Recording in Python.

`SNARP <https://github.com/MerlijnWajer/SNARP>`_ is a noise activated
audio recording program. I initially wrote this for the Nokia N900, but it
should work on most Linux desktops.

.. figure:: img/snarp.png
    :scale: 70 %

    SNARP configuration

.. figure:: img/snarp2.png
    :scale: 70 %

    Running SNARP


Distributed Chat System
~~~~~~~~~~~~~~~~~~~~~~~

`DCS <http://wizzup.org/dcs/>`_ was an assignment for the University of
Amsterdam, we had to form groups and implement a chat protocol similar to IRC.
Our implementation ended up being quite cool, with only one known bug. One that
we've never bothered to fix, though.

.. figure:: img/dcs.png
    :scale: 50 %

    The DCS ncurses client running on my Nokia N900.

Other work
----------

I am an active member of `TechInc <http://techinc.nl>`_, the Amsterdam
Hackerspace. Projects I am working on (or have worked on) include:

-   Software to control the powerbars: https://github.com/MerlijnWajer/powerbars
-   The RGB LED wall. (`lewd <https://github.com/MerlijnWajer/lewd>`_)
