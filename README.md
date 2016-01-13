yagv-ng
=======
Yet Another Gcode Viewer - next generation

A G-Code viewer for 3D printer slicer generated outputs.


---
## Origins

  This software was derived from [yagv][1] (also see [here][2]), created by [jonathanw][3].


---
## License

  [CC BY 4.0, Attribution 4.0 International][6]

  You are free to:

  Share — copy and redistribute the material in any medium or format  
  Adapt — remix, transform, and build upon the material for any purpose, even commercially.
  
  The licensor cannot revoke these freedoms as long as you follow the license terms.
  

---
## News

### CHANGES 2016/01/12

    - initial upload of the "ng" version
    - full mouse/trackpad/touchpad and mouse modifier support
    - viewpoint can now be moved up and down
    - rotation is now performed around the center of the screen


---
## Plans

  3D print analyses:
  
   - amount of extrusion
   - speeds
   - distances
   - ...


  Program:

   - proper loading of all G-Code files
   - selection of single elements
   - save/load state for comparing files
   - ...
   
   
---
## Requirements

   - Python 2 ([www.python.org][4])
   - pyglet ([www.pyglet.org][5])
   

  Python 3 is not _yet_ supported [...].


  Yagv-ng was developed and tested under
  
   - Linux, Ubuntu 14.04 LTS
   - Mac OS X Yosemite and El Capitan
   - Windows 7
  
  but should work with all system, that support OpenGL and mouse or touchpad/trackpad 
  support.


--- 
## Installation

  Right now, yagv-ng does not require an installation.  
  If Python and pyglet are installed, it can be run from any directory by
  just executing "yagv-ng".
  
  Notice that there aren't any dialogs for opening and loading files, hence  
  yagv-ng should be executed from a command line, inside a terminal:
  
    ./yagv-ng yourfilename.gcode
    
    
### Linux

  Python, as well as pyglet should [tm] be available via your distribution's
  package management system.
  
  t.b.c...


### Mac OS X

  Yagv-ng does run with Python as distributed from Apple.  
  To install pyglet, execute:
  
    sudo pip install pyglet
    
  in a terminal window.  
  If "pip" is not installed, it can be obtained by typing
  
    sudo easy_install pip
    

### Windows

  To be written...

 
---
## Usage:

    yagv <file name>

  If no file name is given, a file from the "data" directory is automatically loaded.
  


---

Have fun
FMMT666(ASkr)


[1]: https://github.com/jonathanwin/yagv
[2]: http://www.thingiverse.com/thing:38118
[3]: http://www.thingiverse.com/jonathanw/about
[4]: https://www.python.org/
[5]: https://bitbucket.org/pyglet/pyglet
[6]: http://creativecommons.org/licenses/by/4.0/
