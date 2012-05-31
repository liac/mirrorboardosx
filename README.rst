MirrorBoardOSX
==============
A port of Mirrorboard (Randall Munroe and neale) for OS X. Revisited as 
A one-handed keyboard layout for people with demanding pets.

Supports both Querty and Dvorak layouts.

Original blog post:
http://blog.xkcd.com/2007/08/14/mirrorboard-a-one-handed-keyboard-layout-for-the-lazy/

private.xml documentation can be found here:
http://pqrs.org/macosx/keyremap4macbook/xml.html

INSTALL
=======
1. Install KeyRemap4MacBook from
   http://pqrs.org/macosx/keyremap4macbook/index.html
2. Replace the file 'private.xml' with this one (or Copy the <item> code from 'private.xml' into yours if you already have some personal settings saved).
   To find your 'private.xml,' go to System Preferences -> KeyRemap4MacBook ->
   Misc & Uninstall -> Custom Setting -> Open private.xml
3. Switch back to the Change Key tab and ReloadXML. (Open KeyRemap4MacBook Preferences first if not already open) Type Mirrorboard into the 
   search box: MirrorBoardOSX and DvorakMirrorBoardOSX should be in the list. 
   Activate one and type with a happy pet by your side.



FEATURES
========
If you check querty mode then CAPS-LOCK changes the querty keyboard to::

 ` 0 9 8 / ; 5 7 8 9 0 - =
    p o i u y t I U O P [ ] \
    ' l k j h g J K L ; '
     . , m n b N M , . / 

If you check dvorak mode then CAPS-LOCK changes the dvorak keyboard to::

 ` 0 9 8 z - 6 7 8 9 0 [ ]
    l r c g f y G C R L / = \
    s n t h d i H T N S -
     v w m b x B M W V Z

In both cases Space bar becomes Return and Tab becomes Delete.