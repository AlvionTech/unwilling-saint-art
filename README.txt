THE UNWILLING SAINT - ART DOWNLOAD KIT
======================================

My workspace can't reach image sites, so this kit lets your computer fetch the
art. It downloads 166 candidate images, a first choice and usually a backup,
for about 85 patrons and the chapter openers. It skips files it already has, so
you can run it again after a failure.

1. Unzip this kit into its own folder.
2. Run ONE of these scripts:
   - Windows:  right-click download_art.ps1 > "Run with PowerShell"
   - Mac:      open Terminal, type "bash " (with a space), drag download_art.sh
               into the window, then press Enter
   - Any OS with Python 3:  python3 download_art.py
3. It takes about 5-10 minutes and creates unwilling_saint_art.zip next to the
   scripts. Upload that zip to our chat.

Some downloads may fail, because a few wikis block scripts. Touhou Wiki is the
most likely. Failures are listed in unwilling_saint_art/_failed.txt. If you
like, open those links in your browser, save the images into the
unwilling_saint_art folder under the listed file name, then zip the folder
again. This is optional: I'll work with whatever arrives.

MISSING_ART.txt lists 12 patrons I couldn't find a verified image for. If you
find one you like, add it with that number, e.g. 084_tiamat.jpg.

You can also add:
  - 000_vessel.jpg     art of your character, if you have some you're allowed
                       to use (a commission, your own drawing, etc.)
  - 099_goddess.jpg    art for the amnesiac goddess, only if her player agrees
  - 100_bbeg.jpg       only if your DM wants it in the book

art_manifest.csv lists the artist, title, license and source page for every
file. I credit each image in the book from this list.
