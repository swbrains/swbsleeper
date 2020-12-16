SWBSleeper
(C)2020 Software with Brains, LLC
All rights reserved.

SOFTWARE LICENSE AGREEMENT:
By using this application, you agree to be bound by the terms and conditions
of the software license agreement set forth in this text. You are granted a
non-exclusive license to use the software according to the terms set forth in
this agreement. All ownership and copyright to the materials in this package,
both software and documentation, remain exclusively with Software with Brains,
LLC.

Duplication, Usage, and Distribution
This application may be redistributed at will, however, it may only be
distributed in its original package form and free of charge, with all
accompanying files and documentation included in the original distribution
package, including this document.

Modifications to Software
It is a violation of this license agreement to modify any of the files in
the original software package in any way, including executable (EXE)
application files or this document.

Warranty of Fitness for Use
The software is provided "AS IS" without any warranty, either expressed or
implied, including, but not limited to, the implied warranties of
merchantability and fitness for a particular purpose. You accept all risk as
to the performance of the software. In no way will Software with Brains, LLC
be liable for any damages or loss caused by the use, or inability to use this
software, regardless of its awareness of the potential for such damages or
loss. Software is complex, and by its very nature will contain defects.
Software with Brains, LLC may or may not attempt to correct such defects in
its software at its own discretion.

APPLICATION USAGE (do not include brackets):
swbsleeper.exe  [delay] [units] [displayonly] [quiet]
  [delay] = the number of minutes or hours until system sleeps (1-60 minutes or 1-24 hours)
  [units] = "minutes" or "hours"
  [displayonly] = (optional) turn off display only; no system sleep
  [quiet] = (optional) do not display tray notifications during startup, close, pause or restart

swbsleeper [close]
  terminate running instance (does nothing if not running)

swbsleeper [pause]
  pause running instance (does nothing if not running)

swbsleeper [restart]
  restart running instance (does nothing if not running)

swbsleeper [help]
  display command-line usage

Right-click on the tray icon allows you to:
  "Pause" = disable the sleep timer
  "Restart" = enable the sleep timer
  "Sleep" = put the system to sleep
  "Close" = terminate SWBSleeper

SWBSleeper only detects mouse and keyboard activity to keep the system awake.
It will put the system to sleep (or turn off the display as directed) if there
is no keyboard or mouse activity for [delay] time units. Other running
applications will not stop the timer or prevent sleeping.  If you need to have
another application run uninterrupted, you should pause or close SWBSleeper
first and restart it after the other application is complete.

