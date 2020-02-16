<font face="courier"><pre>
# MIDI-Sysex-MFG-IDs
 A collection of tabularized versions of the publicly available MMA Sysex ID list

https://www.midi.org/specifications/item/manufacturer-id-numbers

A properly formatted Sysex ID request (decimal):

240 126 127 6 1 247
||| ||| ||| | | |||
||| ||| ||| | | End Sysex
||| ||| ||| | ID Request
||| ||| ||| General Info
||| ||| Device ID, 127 = all devices on the port, other values can refer to channel, devices != model #s
||| Universal sysex, non real-time message
Begin Sysex

Response from a Roland TR8s:

240 126 17 6 2 65 69 3 0 0 0 3 0 0 247
||| ||| || | | || || | | | | | | | |||
||| ||| || | | || || | | | | | | | End Sysex
||| ||| || | | || || | | | | | | Software Revision Level
||| ||| || | | || || | | | | | Software Revision Level
||| ||| || | | || || | | | | Software Revision Level
||| ||| || | | || || | | | Software Revision Level
||| ||| || | | || || | | Family Member ID Code (MSByte)
||| ||| || | | || || | Family Member ID Code (LSByte)
||| ||| || | | || || Product Family ID Code (MSByte)
||| ||| || | | || Product Family ID Code (LSByte)
||| ||| || | | Manufacturer Sysex ID (65 = Roland)
||| ||| || | ID Reply
||| ||| || General Info
||| ||| Device ID (in this case the TR8S was set to #18)
||| Universal sysex, non real-time message
Begin Sysex

Additional info gleaned from:
https://www.fumph.com/ensoniq_mr/mrsysex.txt
https://static.roland.com/assets/media/pdf/TB-3_MI_1.pdf</pre</font>
