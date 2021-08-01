About
====

Secondary Distribution Power Network (SDPN) End Nodes Emulation Framework for  Smart Grid networks. A Researcher can customise WiFi based end nodes scenarios to observe different results.


Requirements
------------

For running the framework:

- python2.
- pip.
- Wireshark.
- Pre-configured Virtual Machine with Mininet-WIFI [[3.3GB Size] - Ubuntu 18.04 x64](https://drive.google.com/file/d/1gRqGmkyPcw1waBlwfSGnOcucvXsHvATx/view?usp=sharing) -       Mininet-WiFi (_pass: wifi_).


Building Simulations
---------------------

```
  $: git clone https://github.com/GChugs/SDPN-End-Nodes-Emulation-Framework net-sim
  $: cd net-sim
  $: pip install -r requirements.txt 
  $: python2 bin/igrid-net
```

Interface sw-eth1 can be used to capture nodes (sensors) traffic. 
