![](https://dl.dropboxusercontent.com/u/12733424/github/delphi-dev-shell-tools/logo.png)The <strong>Delphi Dev. Shell Tools</strong> is a  Windows shell extension with useful tasks for Object Pascal Developers (Delphi, Free Pascal).

### Features ###

* Supports Delphi 5, 6, 7, 2005, BDS/Turbo 2006
* RAD Studio 2007, 2009, 2010
* RAD Studio XE-XE8 
* RAD Studio 10 Seattle, [RAD Studio 10.1 Berlin](https://www.embarcadero.com/es/app-development-tools-store/rad-studio)
* Appmethod
* [Lazarus 1.6](http://www.lazarus-ide.org/)
* Works in Windows 10/8/7/Vista/XP. (x86 and x64 versions)

[![](https://dl.dropboxusercontent.com/u/12733424/Images/followrruz.png)](https://twitter.com/RRUZ)


---

### Common Tasks ###

![](https://dl.dropboxusercontent.com/u/12733424/Blog/DevShell/Images/common_tasks.png)

This is a list of taks available for these file extensions .pas, .dpr, .inc, .pp, .dpk, . dproj, .dfm, .fmx, .rc, .lpk, lpr, .lpi


 * _Copy File Path to the clipboard_  : Copy the path of the selected file to the clipboard.
 * _Copy Full FileName to the clipboard_  : Copy the full file-name (Path + Name) of the selected file to the clipboard.
 * _Copy FileName using URL format to the clipboard_ : Copy the full file-name (Path + Name) of the selected file to the clipboard using the Internet Path format
 * _Copy FileName using UNC format to the clipboard_  : Copy the full file-name (Path + Name) of the selected file to the clipboard UNC format.
 * _Copy file content to the clipboard_  : Copy the content of the selected file to the clipboard.
 * _Open In Notepad_  : Open the selected file in the notepad editor.
 * _Open In Default text file editor_ : Open the selected file in the default text editor installed.
 * _Open In associated text editor_  : Open the selected file in the associated text editor.
 * _Open Command Line here_  : Open the cmd.exe application in the folder of the selected file.
 * _Open Command Line here as Administrator_  : Open the cmd.exe application in the folder of the selected file as Administrator.


---

![](https://dl.dropboxusercontent.com/u/12733424/Blog/DevShell/Images/CmdRAD.png)
 * _Open RAD Studio Command prompt here_  : Open the RAD Studio Command prompt (of any installed Delphi version) in the folder of the selected file.

---

![](https://dl.dropboxusercontent.com/u/12733424/Blog/DevShell/Images/pas_menu.png)
 * _Open with Delphi(N)_  : Open the selected file with any version of Delphi or Rad Studio installed.

---

### Specific Tasks for .dpr, .dproj files (Rad Studio Projects), .groupproj (Group Projects) ###
![](https://dl.dropboxusercontent.com/u/12733424/Blog/DevShell/Images/dproj_menu_new.png)


 * _Run MSBuild (Default Settings)_ : Execute MSBuild using the default settings of the selected .dproj file.
 * _Run MSBuild With .._: Execute MSBuild using any of the platforms and targets detected in the selected .dproj file.
 * _MSBuild_: Allow to select and execute the MSBuild tool (associated to any version of the RAD Studio installed) using the default configuration of the project.


---

### Specific Tasks for .lpi, .lpk files (Lazarus Projects and packages) ###
![](https://dl.dropboxusercontent.com/u/12733424/Blog/DevShell/Images/lazarus_menu.png)

 * _Open with Lazarus IDE_: Allow to open the selected file with the installed Lazarus IDE.
 * _Build with lazbuild_: Allow to build a project or package using the lazbuild tool.


---

### Calculate CheckSum ###
![](https://dl.dropboxusercontent.com/u/12733424/Blog/DevShell/Images/checksum_menu.png)

---

### Support for custom extensions ###

The shell extension can be customized to support additional file extensions in some tasks.

![](https://dl.dropboxusercontent.com/u/12733424/Blog/DevShell/Images/settings1.png)

### Support for register custom applications ###
![](https://dl.dropboxusercontent.com/u/12733424/Blog/DevShell/Images/Custom_Tools.png)

This option allows you register a script which will be associated to any specified extension.

---
Looking for the installer? Check the [Release Area](https://github.com/RRUZ/elphi-dev-shell-tools/releases/latest) 
