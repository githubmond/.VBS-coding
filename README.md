.VBS-coding
===========

here is some of the bassics X=MsgBox("Message Description",0+16,"Title")  Here's what the numbers mean -  Number before the + =  0 = Ok Button 1 = Ok/Cancel Button 2 = Abbort/Retry/Ignore button 3 = Yes/No/Cancel 4 = Yes/No  Here are what the numbers mean after the + =  16 - Crtitcal Icon 32 - Warning Icon 48 - Warning Message Icon 64 - Information Icon  for i=1 to 1 Set oWS = WScript.CreateObject("WScript.Shell") oWS.Run "%comspec% /c echo " &amp; Chr(07), 0, True  next  a=inputbox("yeah") msgbox"e "  Set WshShell = WScript.CreateObject ("WScript.Shell") WshShell.Run ("C:\WINDOWS\system32\mspaint.exe") 
