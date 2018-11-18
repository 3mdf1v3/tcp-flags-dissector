# tcp-flags-dissector
Extract tcp flags from pcap

# Install
Edit file C:\Program Files\Wireshark\init.lua and insert:

	[...]
	dofile(DATA_DIR.."\\lua\\tcp-flags-dissector.lua")
	[...]
