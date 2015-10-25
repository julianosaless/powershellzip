#Install

`Import-Module .\powershell-zip.ps1`

#Uninstall
`remove-module powershell-zip`

#Usage

###Create zip folder

`Zip -source 'C:\Users\juliano.sales\Pictures\Saved Pictures' -destination 'c:\backup\Pictures'`
 
###Create zip only files

`Zip -source 'C:\Users\juliano.sales\Pictures\Saved Pictures\*' -destination 'c:\backup\Pictures'`
