About
=====
*Khal* is a CLI (console), CalDAV_ based calendar program, `allowing syncing of
calendars with a variety of other programs on a host of different platforms`__.

*khal* is currently in a early stage of development, has a limited feature set
and is probably full of bugs. If you do try it out, please make sure you have a
backup of your date and please report back any bugs you might encounter.

.. image:: http://lostpackets.de/images/khal.png

Features
--------
(or rather: limitations)

- khal can sync events from CalDAV calendar collections (and load plain
  icalendar files over http(s))
- add simple new events to a calendar and upload them
- ikhal (interactive khal) can show and edit events in the current and next two months
- simple recurring events support (no exceptions just yet)
- you cannot edit the timezones of events
- khal should run on all major
  operating systems [1]_ (has been tested on FreeBSD and Debian GNU/Linux)


.. [1] except for Microsoft Windows

Feedback
--------
Please do provide feedback if *khal* works for you or even more importantly
if it doesn't. You can reach me by email at khal (at) lostpackets (dot) de
, by jabber/XMPP at geier (at) jabber (dot) ccc (dot) de or via github

.. __: http://en.wikipedia.org/wiki/Comparison_of_CalDAV_and_CardDAV_implementations
.. _CalDAV: http://en.wikipedia.org/wiki/CalDAV

