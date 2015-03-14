**libwiigui** is a GUI library for the Wii, created to help structure the design of a complicated GUI interface, and to enable an author to create a sophisticated, feature-rich GUI. It was originally conceived and written after I started to design a GUI for Snes9x GX, and found libwiisprite and GRRLIB inadequate for the purpose. It uses GX for drawing, and makes use of PNGU for displaying images and FreeTypeGX for text. It was designed to be flexible and is easy to modify - don't be afraid to change the way it works or expand it to suit your GUI's purposes! If you do, and you think your changes might benefit others, please share them so they might be added to the project!

## Quickstart ##

Start from the supplied template example. For more advanced uses, and more extensions, see the source code for [Snes9x GX](http://code.google.com/p/snes9x-gx), [FCE Ultra GX](http://code.google.com/p/fceugc), and [Visual Boy Advance GX](http://code.google.com/p/vba-wii). A copy of the documentation is included, or you can read it [online](http://www.wiimc.org/libwiigui/).

## Compiling ##

  1. Ensure that you have [devkitPPC r24 and libogc 1.8.7](http://www.devkitpro.org) or higher installed. If you have an older version, completely uninstall it first.
  1. Download and copy the [ported libraries](http://sourceforge.net/projects/devkitpro/files/portlibs) to your PPC portlibs folder (on Windows this is c:\devkitPro\portlibs\ppc)
  1. Download the source.
  1. Run Programmer's Notepad (installed with devkitPro)
  1. Find the Makefile from the source you downloaded. Click Tools > Make.
  1. You're done!

## Credits ##

This library was wholly designed and written by Tantric. Thanks to the authors of PNGU and FreeTypeGX, of which this library makes use. Thanks also to the authors of GRRLIB and libwiisprite for laying the foundations and to Peter de Man for the background music used in the included demo/template.