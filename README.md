注意eFuse烧录是一次性的，改1后不能改0
# Ralink-3070-2770F-EEPROM-tools-docs.
https://xiaopan.co/forums/threads/ralink-3070-2770f-eeprom-tools-docs.6453/
Just got my hands on this stuff from various places and put it all together, so don't ask me how it works fully yet. I don't have a clue yet either...

I've gathered some docs from various sources about the tool itself and the structure of the EEPROM's (in a separate folder) and put them together inside with the tool for

R E A D I N G F I R S T before randomly pressing away at buttons.

Like the RTL8187L Mass Production Kit I posted earlier to edit the EEPROM of the 036H and it's ilk, this tool also has a special driver that needs loading in order to play around with the eeprom contents for Ralink chipped adapters, and the tool is for Windows XP only, the same as Realtek's Mass Production Kit is.

The docs explain the power setting positions in the EEPROM for all the 2.4 and 5.8 Ghz channels amongst other various info depending whether you want to hack 036NH or 051NH or any other adapter catered for in the driver .inf.

Should help with trying to crank up and fine tune the Signal Kings and Kasens by comparing them with the ALFA values.

I haven't even tried it in any significant depth yet, but the potential is definitely there to alter things for all the tinkerers, and the "special" driver supports 3070 and 2770F...(036NH and 051NH)

Concordantly, Don't blame me if you brick your Ralink adapter fooling around with this utility. It's certainly more "involved" and complicated than operating the Realtek MPK.

It's not a tool for newbies that don't know what it's for, or what to buttons to click on without READING and RESEARCHING *exactly* what it is you are doing first.

Take care and happy Ralink hacking...
