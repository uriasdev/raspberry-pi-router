# Raspberry Pi 4 Home Router

A Raspberry Pi 4-based home router designed, configured, and benchmarked as a replacement for an ISP-provided Spectrum router.

This project began as a hands-on engineering exercise to better understand the networking services that allow a home router to function. Rather than relying entirely on ISP-provided hardware, I configured the routing system from the ground up and documented the design, implementation, troubleshooting, and performance testing.

## Final Network Architecture

![Final Network Topology](images/final-topology.png)

The final topology consists of:

```text
Internet
   |
Spectrum EN2251 Modem
   |
  eth0
   |
Raspberry Pi 4
   |
  eth1
   |
NETGEAR GS305 Switch
   |              |
Wired Clients   TP-Link EAP650
                      |
                 Wi-Fi Clients
