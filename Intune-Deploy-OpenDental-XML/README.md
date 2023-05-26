# IntuneDeployOpenDentalXML
Is a set of scripts used to push Open Dental XML with Intune. Source script comes from <br>https://www.deploymentresearch.com/use-a-win32-app-to-copy-files-and-folders/<br>
Included is the configurations to deploy the Open Dental app as a dependency. <br><br>

Intune Win32 app configuration for Open Dental<br><br>
![alt text](https://github.com/JamesHorvath/Intune-Windows-Software-Deployment/blob/master/Intune-Deploy-OpenDental-XML/IMG/IntuneWin32OpenDental.JPG)
<br><br>
Intune Win32 app configuration for powershell scripts to copy Open Dental XML. Note the file names FilesandFoldersInstall/uninstall should be changed to Win32CopyFilesOpenDentalXML.ps1 and Win32UninstallFilesOpenDentalXML.ps1. Note also we've made the Open Dental app a dependecy for the XML push. It will automtically be installed before the powershell execution.<br><br>

![alt text](https://github.com/JamesHorvath/Intune-Windows-Software-Deployment/blob/master/Intune-Deploy-OpenDental-XML/IMG/IntuneWin32OpenDentalXML.JPG)
