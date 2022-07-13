### How to install Syntax Highlighting 
***
Open User Defined Language folder:

![1](https://github.com/Siqsuruq/notepad-plus-plusTCL/blob/main/README/1.png)

Copy the tcl2.xml file from the repository to this folder and reload Notepad++:

![2](https://github.com/Siqsuruq/notepad-plus-plusTCL/blob/main/README/2.png)

New syntax highlighting appears in the language menu:

![3](https://github.com/Siqsuruq/notepad-plus-plusTCL/blob/main/README/3.png)

Write your code:

![4](https://github.com/Siqsuruq/notepad-plus-plusTCL/blob/main/README/4.png)


### How to install Tcl/Tk auto-completion and function list definition files  
***
Notepad++ uses XML configuration files to define the per-language function and parameter auto-completion. Those AutoComplete files are located in the autoCompletion subdirectory of the Notepad++ install folder. (In older versions, Notepad++ v7.6.1 and earlier, they were found in the plugins\APIs subdirectory of the intstall folder.)

In my case just copy `autoCompletion/tcl.xml` to `C:\Program Files\Notepad++\autoCompletion\`
and `functionList/tcl.xml` to `C:\Program Files\Notepad++\functionList\`

Reboot Notepad++

Enjoy