nds4ios - nds4droid port for iOS
=======

nds4ios based on Desmume and nds4droid

[Desmume](http://desmume.org/) 

[nds4droid](http://jeffq.com/blog/nds4droid/) 


Build instructions
------------------------

1.  Open terminal and go to your working directory;

2.  Print
<code>git clone https://github.com/rock88/nds4ios.git</code>

3. 
    <code>cd nds4ios</code>

4. 
    <code>git submodule update --init</code>

5. Open "nds4ios.xcodeproj", connect your device, select it on Xcode and click "Run" button (or Command + R), don't build it for Simulator.


To-do
------------------------
* Cleanup and refactor code, remove "ugly hack" (see nds4ios-Prefix and android/log.h);
* JIT (oh, for clang compiler it be very hard);
* OpenGLES rendering;
* Sound;
* Save state;
* iPhone 5 and iPad support;
* Better on-screen pads;
* Using Cmake for generate Xcode project;
* and more.