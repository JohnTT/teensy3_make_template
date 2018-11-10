1. Install MinGW for Windows: https://osdn.net/projects/mingw/releases/
2. Open CMD and run: copy c:\MinGW\bin\mingw32-make.exe c:\MinGW\bin\make.exe
3. Add make to %PATH% by running: setx PATH "%PATH%;c:\MinGW\bin"
4. Clone this repo off of GitHub and use it for whatever you want.

Open a command line in .\src\teensy3 and type "make" to build. You can use Teensy Loader to put the generated .hex files onto the target Teensy device.

https://www.pjrc.com/teensy/loader.html
