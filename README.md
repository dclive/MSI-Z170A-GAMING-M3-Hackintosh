# MSI-Z170A-GAMING-M3-Hackintosh
Sample GeekBench 6.03 Output with PC3000 RAM, XMP on, "game mode" BIOS setting set to off:

![239713593-3e6ef1a1-064c-4ed7-a90c-b06a24a4abc4](https://user-images.githubusercontent.com/4536776/239713593-3e6ef1a1-064c-4ed7-a90c-b06a24a4abc4.png)

Sample GeekBench 6.03 Output with PC3000 RAM, XMP on, "game mode" BIOS setting set to on: 



**Suggestion:  Keep game mode setting in BIOS set to OFF outside of very special use cases.  XMP should always be set to ON.**

Boot EFI to get one going on a basic Mac install with the MSI Z170A Gaming M3; read the readme for important details

**Please note:  This is a quick guide.  The intent is only for this to get you into MacOS, and then you can use OpenCore Aux Tools (OCAT) to modify this to suit your configuration.  It's basic, and that's how it's intended.  Once you're in MacOS, grab OCAT, and modify away.**  This uses OpenCore .88; be sure to tell OCAT to update to "latest version of OpenCore" inside the OCAT application.  Note this is different from an OCAT update (do those, too).  Find the directions on how to do this on my github page (look in the index).  

As of 5/20/23 OCAT .92 is tested and confirmed working, as is MacOS 13.4.  

This is a basic EFI to get the MSI Z170A Gaming M3 motherboard plus AMD graphics (I use a RX580; YMMV) booting.

If you use a more modern AMD card, you may need agdpmod=pikera in NVRAM boot args; google for more details. 

I use a basic Broadcom / Fenvi wifi card mounted on a PCIe card for wireless and BT.  BT works fine (tested with Apple watch) and Wifi works great.  

Sound via the 3.5MM in/out is untested since I use HDMI audio for output and don't use input.  

USB remapping may be required depending on your specific requirements.  This works for me.  If you add the wifi/BT PCIe card, you'll have better luck with the extra USB mappings file posted on Jan 13. 

NIC:  Qualcomm Atheros E2400 Killer.  Works fine. 

Recommendation:  Add a Wifi/BT PCIe card.  Apple-based Broadcom / Fenvi cards strongly recommended.  

