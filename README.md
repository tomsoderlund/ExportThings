ExportThings.applescript
========================

An AppleScript for exporting Things database to the Desktop as Things Backup.txt.

Somewhat based on "Export Things to text file (ver 1)" by John Wittig<br />
and from reading the Things AppleScript Guide (rev 13).

With contributions by Rob de Jonge - @robdejonge on Twitter

Notes
-----

- Added Notification Center support for OS X Mavericks as alternative to afplay for completion notification... but I haven't had a chance to test it.
- Tested with Things 2.2.1 and OS X Mountain Lion.
- Enhanced configurability and added wrapper to allow script to run without activating the application. Script no longer activates Things unless configured to do so. Output
can now go to both disk and screen by configuring toggleShowOutput. When the application is not running and not activated by the script, the script will attempt to read previous output from disk and print this to screen.

To dos
------

1. Get Repeating ToDos (currently no way via AppleScript).
2. Make tags tab delimited by heirarchy.
3. Export Areas. Maybe.
4. For each exported ToDo, also include their tags and areas. Maybe.
5. Maybe find a way to export as OPML and not just plain text.

Copyright & License
-------------------

Copyright (c) 2013 Dexter Ang

ExportThings.applescript is released under the MIT license:

- http://www.opensource.org/licenses/MIT
