shift-layout-switch.ahk features:

Keyboard layout switch: 
 * LShift - US, RShift - RU
 * Win+V : Paste pure text 

How did I make it:

  * Compile:
    Ahk2Exe.exe /in shift-layout-switch.ahk /out shift-layout-switch-winv.exe /icon keyboardbasichd_106130.ico 

  * Sign:
    AutoHotkey.exe "C:\Program Files\AutoHotkey\EnableUIAccess\EnableUIAccess.ahk" shift-layout-switch-winv.exe shift-layout-switch-winv-signed.exe 


