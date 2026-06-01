Project(OLD) : An all-purpose external trainer for the game APEX Legends in C++. Uses two custom drivers that map onto native windows ring0 drivers to access memory. 

Usermode: Custom made executive files that maps a driver and communicates with the driver using the parameters of the hooked windows function. Creates threads with main logic with a rendering thread and a security thread. Uses signatures to access classes in game's memory and reads the memory through the mapped kernel driver. Hooks native Windows function to simulate mouse movement to specific coordinates. Renders enenmies skeleton and menu on an overlay.


# Notes (OLD)
- Using Two Different Driver
- Needs a few driver exceptions
- Needs love

(Patch 1.0.0 - 12/10/2022) (Start here, and go down)
- Project Started

(Patch 1.0.1 - 12/17/2022)
- Updated Aim Method
- Fixed Overlay
- Fixed Mapper
- Added Triggerbot Beta

(Patches Void Here)
- Unknown Changes, don't worry about it

(Patch 1.0.2 - 1/22/2023)
- Updated Driver
- Updated Triggerbot
- Updated Overlay
- Updated Mapper


(Patch 1.0.3 - 1/23/2023)
- Experimentally added no spread and bullet tp

Disclaimer: ****FOR EDUCATIONAL PURPOSE**** not liable for what is done with this source.
