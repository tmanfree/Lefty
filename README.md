# Lefty - in honour of the proprieter of the leftorium.
MAC address follower
Lefty is a tool to search for a mac address on Cisco switches and uses CDP neighbour to jump between switches, finding the furthest downstream port

#Usage
lefty [IP] [MAC]

For Example: lefty 1.1.1.1 BBBB.CCCC.DDDD

The IP specified should be the furthest upstream or downstream layer 2 end point that the MAC address would appear on. If unsure, going upstream is a safer bet (going to an aggregation switch, for example)

#Notes
currently works on Cisco Devices


