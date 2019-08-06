This repo is mostly based on https://github.com/ameeno/Lenovo-Thinkpad-T440P-Hackintosh with several changes:

* Different version of VoodooPS2 Controller to support Alps trackpad (also supports the nub scrolling without any additional software)
   * I also swapped Caps Lock and Escape in the kext's config.plist
   * Unfortunately, since it's a kext from a different laptop, the function keys are messed up (F5 doesn't lower the brightness). Using Karabiner-Elements to solve this at the moment
* Special config.plist for USBInjectAll to support docking station USB ports

#### If you have a Synaptics trackpad or don't want Escape and Caps Lock to be swapped
Check out the "Alternative trackpad drivers" folder

TODO:
* Proper brighness keys implementation
* Docking station audio
* Address reboots when trying to suspend on docking station


Instructions coming soon!
