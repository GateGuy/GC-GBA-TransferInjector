# GC-GBA TransferInjector
This is a Python script that uses several existing tools to inject a GBA ROM (<= 256 KB) into the official transferrable WarioWare demo found on the Gamecube Preview Disc.

### Usage
```
Usage: GCGBA_ti.py -a <input GBA> -c <input GC> --err <TPL/PNG> --load <TPL/PNG> --ind <TPL/PNG> --done <TPL/PNG>

-a <the GBA ROM that will be injected>
-c <the Gamecube file that the GBA ROM will be injected into; this is wario_agb.tgc, which can be extracted from the Nintendo Gamecube Preview Disc>
--err  \<optional; a new texture/PNG file that displays when the transfer from Gamecube to GBA has not started>
--load \<optional; a new texture/PNG file that displays when the transfer is in progress>
--ind  \<optional; a new texture/PNG file that represents the progress bar for the transfer (such as a dot or a pill)>
--done \<optional; a new texture/PNG file that displays when the transfer is complete>

All textures have a recommended size of 640x480 except indicator, which is 30x28.
```

### Legal Disclaimer
No copyrighted content is included with this program. You have to supply the files for GBA injection.

### Included Programs/Credits
Some of the tools bundled with this program are not made by me, but are required for its use:
- [Gamecube ISO Tool](http://www.wiibackupmanager.co.uk/gcit.html) (Made by FIG2K4)
- [TGCtoGCM](https://www.gc-forever.com/forums/viewtopic.php?t=17&start=24) (Made by Zochwar & Plootid)
- [Wiimms Image Tool](https://szs.wiimm.de/wimgt/) (Made by Wiimm)
