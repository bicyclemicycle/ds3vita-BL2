# ds3vita

**Download**: https://github.com/xerpi/ds3vita/releases

**Enable the plugin:**
1. Add ds3vita.skprx to taiHEN's config (ux0:/tai/config.txt):
	```
	*KERNEL
	ux0:tai/ds3vita.skprx
	```
2. You need to refresh the config.txt by rebooting or through VitaShell.

**Pairing the controller:**
1. Download [this](http://dancingpixelstudios.com/sixaxis-controller/sixaxispairtool/) tool (or [this](https://help.ubuntu.com/community/Sixaxis?action=AttachFile&do=get&target=sixpair.c) other one if you want to compile it yourself)
2. Connect your DS3 to the PC and open the tool
3. Introduce the Vita's **MAC address plus 1** to the tool (Settings -> System -> System information)

**Using it once paired (see above):**
1. Just press the PS button and it will connect to the Vita

**Note**: If you use Mai, don't put the plugin inside ux0:/plugins because Mai will load all stuff you put in there...

The original code written by xerpi. The code was modified using the ds4vita plugin to understand hooking and patching inputs to the PS Vita. The locations for inputs are mostly arbitrary and made to be a default location a user might click. Either way, it works for me. As my first release, someone more reputable please review and verify the code (and plugin if you want). Thank you xerpi.

PS Vitas  known to work (so far):
1000:3.60
