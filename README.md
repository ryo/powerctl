powerctl
========

CUI tool for LANdeBOOT and AP7900


e.g.)
  % cat ~/.powerctl
  servers:
    ap7900:
      type: ap7900
      addr: 192.168.0.100
      user: apc
      pass: apc
  
  targets:
    device1: ap7900/1
    device2: ap7900/2
    device3: ap7900/3
    device4: ap7900/4
    device5: ap7900/5
    device6: ap7900/6
    device7: ap7900/7
    device8: ap7900/8


  % powerctl device1 on
