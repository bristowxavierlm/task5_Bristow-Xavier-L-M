Fifth task of the cyber security internship

Wireshark Network Packet Capture Report

Objective
Capture live network traffic and identify key protocols used during normal internet activity using Wireshark.



Tools Used
- Wireshark 
- Youtube (Firefox)



Steps Performed

1. Installed Wireshark and started a live capture on my active network interface (eth0).
2. Visited website (www.youtube.com) to generate HTTP and HTTPS traffic.
3. Stopped capture after 1 minute.
4. Applied filters to inspect various protocols:
   - http
   - dns
   - tcp


Protocols Identified

| Protocol | Description | 
|-----|--------------------------|
| DNS | Resolving domain names | 
| HTTP | Unencrypted web traffic |
| TCP | Connection-oriented communication |



Files
- network-capture.pcap: Captured network traffic containing DNS, HTTP, ICMP, and TCP/TLS packets.


Summary
This short experiment demonstrated basic internet communication protocols using Wireshark. DNS queries were made to resolve website addresses, HTTP/TLS traffic occurred during browsing (Youtube). The `.pcap` file can be opened in Wireshark for detailed analysis.

