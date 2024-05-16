*Sorry for the lack of comprehensive documentation feel free to ask if you encounter any issues*



<br>If you want to install Windows 10 22H2 and not Windows 11 or later versions and using an Asus AdolBook ADOL14ZA
<br>you might encounter some *missing drivers issue* in device manager

<br>to fix that:

<br>go to - https://www.asus.com/us/supportonly/adol14za/helpdesk_download/ - and download the drivers from there

<br>Then you'll still need some drivers for the unrecognized devices:

<br>go to: 

<br>press "Windows key"/"Super key" => type "device manager"
<br>=> enter device manager => go to the section of devices with exclamation point above theme
<br>=> double click on the device
<br>=> go to "Driver"
<br>=> click one "update driver"
<br>=> go to the folder
<br>=> go to the designated driver position according to the following list <br>=> click "Next"
<br>=> go to the next driver and do the same thing
<br>=> when finishing exit device manager and restart your pc if needed *probably not needed*
<br><br><br>
<br>========== THE SPECIFIED ORDER ==========



<br>Base System Device == the same name as in device manager
<br>PCI Device 1 == the first device right under Base System Device
<br>PCI Device 2 == the device under PCI Device 1 in placement
<br>PCI Device 3 == the device under PCI Device 2 in placement
<br>Unknown Device == the device labeled "Unknown Device" right under the "last PCI Device"
