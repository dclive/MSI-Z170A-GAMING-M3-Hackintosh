# MSI-Z170A-GAMING-M3-Hackintosh
Boot EFI to get one going on a basic Mac install with the MSI Z170A Gaming M3; read the readme for important details

**Please note:  This is a quick guide.  Very little support can be given on this; the intent is only for this to get you into MacOS, and then you can use OpenCore Aux Tools (OCAT) to modify this to suit your configuration.  It's basic, and that's how it's intended.  Once you're in MacOS, grab OCAT, and modify away.**  This uses OpenCore .88; be sure to tell OCAT to update to "latest version of OpenCore" inside the OCAT application.  Note this is different from an OCAT update (do those, too).

This is a basic EFI to get the MSI Z170A Gaming M3 motherboard plus AMD graphics (I use a RX570; YMMV) booting.

If you use a more modern AMD card, you may need agdpmod=pikera in NVRAM boot args; google for more details. 

I use a basic Broadcom wifi card mounted on a PCIe card for wireless and BT.  BT is untested; wifi is only lightly tested.  

Sound via the 3.5MM in/out is untested since I use HDMI audio for output and don't use input.  Reminder:  Quick guide.  :) 

USB remapping may be required depending on your specific requirements.  This works for me.  

NIC:  E2200 Killer.  Works fine. 



