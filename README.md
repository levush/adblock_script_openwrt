# adblock_script_openwrt
Retrofit Adblock Script for openwrt, that I found and optimized, to save flash memory

The adblock will use the webserver of the openwrt router by default to deliver a page. Best would be a config that
delivers an empty index.html regardless of the url, but I did not manage. The index.html has a # character to
click to get to luci interface

To get it running, just download the files and copy them with their paths relative to / of openWRT ChaosCalmer.

Credits to:
https://gist.githubusercontent.com/teffalump/7227752/raw/af7d3d365426731015e99698a93e1a072a7da4ba/adblock.sh

