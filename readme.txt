ח����������� ������������������������������ �����������������������-����-���
|0O��o�                      libwiigui 1.02                           �o��O0|
|                   http://code.google.com/p/libwiigui                      |
|                          (Under GPL License)                              |
`������� ���������������� ��������������� �������������������� �������������'

libwiigui is a GUI library for the Wii, created to help structure the
design of a complicated GUI interface, and to enable an author to create
a sophisticated, feature-rich GUI. It was originally conceived and written
after I started to design a GUI for Snes9x GX, and found libwiisprite and
GRRLIB inadequate for the purpose. It uses GX for drawing, and makes use
of PNGU for displaying images and FreeTypeGX for text. It was designed to
be flexible and is easy to modify - don't be afraid to change the way it
works or expand it to suit your GUI's purposes! If you do, and you think
your changes might benefit others, please share them so they might be
added to the project!

Quickstart

Start from the supplied template example. For more advanced uses, see the
source code for Snes9x GX, FCE Ultra GX, and Visual Boy Advance GX.

Contact

If you have any suggestions for the library or documentation, or want to
contribute, please visit the libwiigui website:
http://code.google.com/p/libwiigui/

Documentation

See the included doxygen documentation, or visit the libwiigui website.

Credits

This library was wholly designed and written by Tantric. Thanks to the
authors of PNGU and FreeTypeGX, of which this library makes use. Thanks
also to the authors of GRRLIB and libwiisprite for laying the foundations.

���������-- - �������������� �������-- - �������������� �������-- - ���������
|                                                          UPDATE HISTORY  |
���������-- - �������������� �������-- - �������������� �������-- - ���������

[1.02 - April 13, 2009]
* Fixed letterboxing on PAL
* Add STATE_HELD for held button actions (eg: draggable elements)
* Now tracks state changes per-remote
* Default constructor for GuiImage
* Keyboard corrections, added more keyboard keys
* Better handling of multiple wiimote cursors on-screen
* Added functions for the ability to alter button behavior for all states
* Documented GuiTrigger class
* Refactor - moved trigger class definition to gui.h

[1.01 - April 5, 2009]
* Changed default sound format to 16bit PCM 48000 
* Added loop option for OGG sound playback 

[1.00 - April 4, 2009]
* Initial release