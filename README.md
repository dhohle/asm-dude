# Asm-Dude
Assembly syntax highlighting (and more) for Visual Studio 2015

Download installer [AsmDude.vsix (v1.0)](https://github.com/HJLebbink/asm-dude/releases/download/v1.0/AsmDude.vsix)


To run the extension from source code the Visual Studio 2015 SDK needs to be installed. To run the extension, hit F5 or choose the Debug > Start Debugging menu command. A new instance of Visual Studio will launch under the experimental hive.

Not happy with the highlighting or the descriptions. Mnemonics and descriptions can be added and changed by updating the AsmDudeData.xml file that will be stored next to the binaries when installing the plugin (.vsix). The directory where plugins are installed can be difficult to find, try something as C:\Users\user\AppData\Local\Microsoft\VisualStudio\14.0\Extensions

Updates:
* 19 February 2016: Initial alpha release. Basic highlighting and descriptions for i368 instructions are available.
* 20 February 2016: Added highlighting and descriptions for SSE, AVX, AVX2 instructions.
* 21 February 2016: Added .vsix Installer
