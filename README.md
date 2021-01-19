(1)..............
    install code::block (IDE)Intigrated Development Environment
Make sure you have installed Code::Blocks IDE on your machine. If you don't have this IDE or have any issue with compiler download and install it from here.
http://sourceforge.net/projects/codeblocks/files/Binaries/16.01/Windows/codeblocks-16.01mingw-setup.exe



(2)......... Include graphics.h and winbgim.h
Copy and Paste the graphics.h and winbgim.h files into include folder of Code::Blocks directory.

Path: C:\Program Files (x86)\CodeBlocks\MinGW\include

(3)........ Include libbgi.a
Copy and paste libbgi.a file in the lib folder of Code:Blocks

Path: C:\Program Files (x86)\CodeBlocks\MinGW\lib

(4)....... Add Link Libraries in Linker Setting
In the Code::Blocks application go to, Settings > Compiler

In the Global Compiler setting, click on the Linker Settings

In Link Libraries, Add and browse to C:\Program Files (x86)\CodeBlocks\MinGW\lib\ and select libbgi.a.

Paste this in the Other Linker Option tab of Linker Settings (i.e. on the right-hand side)

-lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32

Save the setting and restart the application

All step are read carefully are use the #include<graphics.h> libraby and header file......c and c++ environment.....
signature by............ Shubham Kumar Vishnoi........
