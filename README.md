rtcmix-mode-textwrangler
========================

SYNTAX HIGHLIGHTING AND HOT KEY FOR CMIX
=====================================
These are add-ons to TextWrangler that highlight RTcmix keywords and
allow you to execute your RTcmix file from within the TextWrangler window.

There is an install script that will copy them to the (probably) correct
location, or, if you are not the trusting type, you can copy them there yourself.

METHOD 1: SCRIPT (semi-automatic)
==============================
1. in a terminal, open the folder rtcmix_textwrangler
2. type: bash install.sh (you will be prompted for your password)
3. open TextWrangler
4. select Window -> Palettes -> Scripts
5. choose the rtcmix script
6. in the pop-up window, press Set Key... and choose your hotkey (OPT-TAB works pretty nicely)
7. if you are using the Python version of CMIX, choose a hot key for pycmix

METHOD 2: Manual Copy
====================
1. Go to your home folder and open Library -> Application Support -> TextWrangler
2. If there is no folder called Language Modules, create it now.
3. Move or copy rtcmix.plist into Language Modules
4. Go up one directory level and open the folder Scripts
5. Move or copy the scripts rtcmix and pycmix into Scripts
6. Open TextWrangler, and then follow steps 4-7 of Method 1 above.

That's it! Enjoy.
