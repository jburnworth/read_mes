# Getting Started With Mercury 16

This guide will walk you through setting up a development environment (MPLAB X), connencting your Mercury 16 to your computer, and programming it with a basic application (blinky)!

### Table of Contents
1. [Installing MBLAB X](#installing MBLAB X)
2. [Your First MBLAB X Project](#Your First MBLAB X Project)
3. [Connections](#connections)

## Installing MBLAB X
### Windows
First, you will need to download the latest version of [MBLAB X IDE](http://www.microchip.com/pagehandler/en-us/family/mplabx/home.html) and the [XC 8 Compiler](http://www.microchip.com/pagehandler/en-us/devtools/mplabxc/home.html).  You will also need a driver for the USB-to-UART chip onboard, [MCP2200](http://www.microchip.com/wwwproducts/devices.aspx?dDocName=en546923).
#### Direct Download Links (Windows)
* [MPLAB X IDE](http://www.microchip.com/mplabx-ide-windows-installer)
* [XC 8 Compiler](http://www.microchip.com/mplabxc8windows)
* [MCP220 Driver](http://ww1.microchip.com/downloads/en/DeviceDoc/MCP2221%20Windows%20Driver%202014-10-09.zip)

Run the installers and follow the instructions in the setup wizards.  You should now be ready to open MPLAB X and load your first project.

## Your First MBLAB X Project
Begin by cloning the [On_Board_Mercury16]() repository into your local project directory.  Alternatively, you can download the [.zip]() file.  Navigate into Blinky.X if you want to preview the main file.  

Start MPLAB X.  Once it has opened, click on File >> Open Project... (Ctrl + Shift + O).  Navigate to where you saved the On_Board_Mercury16 repositry and select Blinky.X.  Click Open Preject.  MPLAB X open the project and all it's settings.  You can see project information in Dashboard, bottom left.  The project tree, where you can find all the included files, is in the top left.  

## Connections
