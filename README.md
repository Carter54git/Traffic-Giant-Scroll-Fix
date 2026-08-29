# Traffic-Giant-Scroll-Fix
Just scroll fix for Traffic Giant (2001) game. Included for Steam and other versions

Scroll Fix v1

Traffic Giant — Windows 10/11 patch

Copy the files from the zip into the folder with trafficgiant.exe, then start the game as usual.

Steam zip:

winmm.dll — slows map scrolling
fpslimit.ini — scroll speed

Retail / CD zip:

winmm.dll + fpslimit.ini — same scroll fix
ddraw.dll + ddraw.ini — fixes the very low FPS (old DirectDraw)
Scroll speed (fpslimit.ini)
scroll_hz = steps per second. Lower = slower (e.g. 10), higher = faster (e.g. 25). Default: 15.

Check
After launch, fpslimit.log should say: scroll hooks installed OK.

Uninstall
Delete winmm.dll (and ddraw.dll on the retail version) from the game folder.
