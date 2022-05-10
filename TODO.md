# svDialogstcltk To Do list

-   Most dialog boxes still need to be done for a complete implementation. This is mostly a demonstration of the concept for now with just a couple of dialog boxes available.

-   Reimplement `dlgMessage.tcltkWidgets()` using something else than `tkmessageBox()` which is ugly under Linux and buggy under MacOS.

-   For the moment, `dlgList.tcltkWidgets()` just delegates to `tk_select.list()`... but we could build a nicer list selector (also look at old code from previous versions).
