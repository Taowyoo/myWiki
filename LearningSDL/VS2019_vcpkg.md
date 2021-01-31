Dependencies

vs2019

vcpkg



install vcpkg



install vs2019



install sdl2,sdl2_ttf,sdl2_image

x86

x64



setup project

use source code of https://lazyfoo.net/tutorials/SDL/25_capping_frame_rate/index.php as example:

1. create a new empty project
2. Setup sdl in solution configuration
   1. Add library include path
   2. Add sdl2_main lib to linker input
   3. Why do such things?
3. add source code
4. Correct include path and font file path in source code
5. Run