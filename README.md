﻿# WebexMeetingMute

Tiny AHK script useful for quickly muting\unmuting your participant audio in a Webex Meeting on Windows.  Works by flipping the Meeting application to the foreground (if not already there), sending keypresses to mute\unmute, and then restoring the previously active window back to the foreground.

AHK script included, or just use the compiled EXE if you don't have auto-hotkey installed already.

To use:
1. Copy EXE\AHK and ICO files somewhere local
2. Execute EXE, you will note a gray\red systray button 
3. To mute, hold CTRL-ALT and press M
4. To unmute, hold CTRL-ALT and press U
5. Tray icon will change to reflect status

Todos: 
1. Does not currently work when Meeting is in full-screen view or you happen to be sharing your screen.  Need to investigate other methods to control floating controls in these modes.  Assuming you have the Webex application selected, you can still use the built-in CTRL-M function to toggle mute status as well.
2. Make it work for OSX too.
