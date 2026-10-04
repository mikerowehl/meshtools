# Meshtastic Tools

I got a Heltek V3 board to just poke around some Meshtastic. There is a
community run mesh project in my area. But as luck would have it their web
presence went down between me ordering my board and it arriving. There is an
overlapping community that has a web presence, but our connectivity is spotty.
I can see nodes through my radio that I can look up on their map, but almost
all of them are offline and not recently connected. So it's been hard for me
to really verify the operation of my radio.

During that process I just wanted to see actual realtime activity in from the
radio. There's a raw listen mode in the Meshtastic CLI, but that is really
hard to parse. I just wanted to see packets in realtime and find addresses I
could try to look up. So I made the listener here to just output one line per
packet effectively with a nice regular node info format.
