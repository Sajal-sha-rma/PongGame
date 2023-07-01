# PongGame
This is a two player Pong Game which is entirely developed using C++. The game library used is Raylib.

## Installing and building raylib via vcpkg

You can download and install raylib using the vcpkg dependency manager:

 ```
git clone https://github.com/Microsoft/vcpkg.git
  
cd vcpkg

bootstrap-vcpkg.bat
  
vcpkg integrate install
  
vcpkg install raylib
```


#### The default triplet in vcpkg is set to "x86-windows". If you want to install x64 version instead, you should use following command:

  ```
vcpkg install raylib:x64-windows
```

  The raylib Windows Installer comes with all the required tools to develop with raylib, those tools are:

* C Compiler (TCC or MinGW) - To compile the code, it includes all required system libraries.
* Notepad++ (preconfigured) - To edit code, it includes ready-to-use scripts to compile code and examples.
* raylib library - Including, source, release, examples and templates.

If you want, you can use a different code editor (e.g. Visual Studio) or another compiler.

