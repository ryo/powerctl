powerctl
========

CUI tool for LANdeBOOT, AP7900, and TP-LINK HS105
---------------------------------

powerctl is command line interface script for <a href="http://www.meikyo.co.jp/products/5lc.html">LANdeBOOT serials</a>,
<a href="http://www.apc.com/resource/include/techspec_index.cfm?base_sku=AP7900&ISOCountryCode=en">APC AP7900</a>, and
<a href="https://www.tp-link.com/jp/home-networking/smart-plug/hs105/">TP-LINK HS105</a>.

	e.g.)
	
	% cat ~/.powerctl
	servers:
	  ap7900:
	    type: ap7900
	    addr: 192.168.0.100
	    user: apc
	    pass: apc
	  landeboot:
	    type: landeboot
	    addr: 192.168.0.101
	    pass: magic
	  tplink1:
	    type: tplink
	    addr: 192.168.0.102
	
	targets:
	  my-device1: ap7900/1
	  my-device2: landeboot/2
	  my-device3: tplink1
	
	% powerctl my-device3 on
