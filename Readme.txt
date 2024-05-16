*Sorry for the lack of comprehensive documentation feel free to ask if you encounter any issues*



If you want to install Windows 10 22H2 and not Windows 11 or later versions and using an Asus AdolBook ADOL14ZA
you might encounter some *missing drivers issue* in device manager

to fix that:

go to - https://www.asus.com/us/supportonly/adol14za/helpdesk_download/ - and download the drivers from there

Then you'll still need some drivers for the unrecognized devices:

go to: 

press "Windows key"/"Super key" => type "device manager"
=> enter device manager => go to the section of devices with exclamation point above theme
=> double click on the device
=> go to "Driver"
=> click one "update driver"
=> go to the folder
=> go to the designated driver position according to the following list => click "Next"
=> go to the next driver and do the same thing
=> when finishing exit device manager and restart your pc if needed *probably not needed*

========== THE SPECIFIED ORDER ==========



Base System Device == the same name as in device manager
PCI Device 1 == the first device right under Base System Device
PCI Device 2 == the device under PCI Device 1 in placement
PCI Device 3 == the device under PCI Device 2 in placement
Unknown Device == the device labeled "Unknown Device" right under the "last PCI Device"