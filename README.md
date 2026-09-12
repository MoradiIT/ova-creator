# OVA File Creator

OVA File Creator is a Windows-based utility created by **Moradi IT** that simplifies the process of exporting virtual machines created with VMware Workstation into a single OVA file.

The utility uses **VMware OVF Tool** to perform the actual virtual machine export.
</br> </br>

## Features

* Exports VMware Workstation virtual machines to a single OVA file.
* Simple interactive setup through a batch file.
* Designed to make the OVA export process easier for users who do not want to manually work with OVF Tool commands.
 </br> </br>

## Usage

1. Download or clone this repository.
2. Run `01 Setup.bat`.
3. Follow the instructions displayed by the script.
4. Provide the requested virtual machine path, destination, and other information.
   </br> </br>

## Start Menu Shortcut

To add an icon for this `.bat` file to the Windows Start Menu:

1. Create a shortcut for the `.bat` file.
2. Give the shortcut an appropriate name.
3. Assign a suitable icon to the shortcut.
4. Copy or move the shortcut to the following Start Menu folder:

```text
%AppData%\Microsoft\Windows\Start Menu\Programs
```

The shortcut will then appear in the Windows Start Menu.
 </br> </br>
 
## Troubleshooting

If an error occurs during the export process, make sure that:

* The virtual machine is not currently being used by another program.
* The virtual machine files are accessible.
* The paths and file names you provide are valid.
* The destination has sufficient free disk space.
* No required files are locked or being accessed by another application.

If the export fails, review the error message displayed by OVF Tool for additional information.
 </br> </br>
 
## Third-Party Software

This project includes and uses **VMware OVF Tool**.

**VMware OVF Tool and its associated files are third-party software. All rights, title, and interest in VMware OVF Tool remain with their respective copyright and license holders, including VMware/Broadcom.**

VMware OVF Tool is not created, modified, or owned by Moradi IT.

The batch files, scripts, documentation, and other original material created specifically for this project are the work of **Moradi IT**.

VMware and Broadcom are trademarks of their respective owners. This project is not affiliated with, sponsored by, or endorsed by VMware or Broadcom.

Please refer to the applicable VMware/Broadcom license terms accompanying OVF Tool for the rights and restrictions applicable to the included third-party software.
 </br> </br>
 
## Project License

Unless otherwise stated, the original scripts and documentation created by Moradi IT are provided under the license included in this repository.

The project license applies **only to the original material created by Moradi IT** and does not grant any additional rights to the included VMware/Broadcom software.
