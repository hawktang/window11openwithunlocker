# Window 11 open with unlocker
 
Windows 11 locked the ablity to change default open with (default app) for all the image and video files.

## Here is how to unlock

Get-AppxPackage Microsoft.Windows.Photos -AllUsers | Reset-AppxPackage

Get-AppxPackage Microsoft.ZuneMusic -AllUsers | Reset-AppxPackage

Get-AppxPackage Microsoft.ZuneVideo -AllUsers | Reset-AppxPackage

Get-AppxPackage Microsoft.WindowsNotepad -AllUsers | Reset-AppxPackage

## Show all windows apps

Get-AppXPackage -AllUsers|Format-Table

