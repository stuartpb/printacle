# Printacle

Printacle is a command-line controller for OctoPrint that uses a CDN-style approach to print jobs, where gcode is stripped of its comments and uploaded directly to an object store (ie. a Toshiba FlashAir) to be printed, rather than submitting the file's commands to the printer directly (which is susceptible to timing issues when the server is under load, and isn't capable of using firmware print resumption features).
