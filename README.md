# Task 5: Network Traffic Capture and Analysis

## Objective
To capture live network packets and identify basic protocols and traffic types using Wireshark.

## Protocol Analysis Findings
I successfully captured network traffic and isolated 3 distinct network protocols:

1. **TCP (Transmission Control Protocol)**
   - **Observations:** Captured multiple connection packets between my local IP (`192.168.1.7`) and remote servers showing reliable, connection-oriented data flow.

2. **ARP (Address Resolution Protocol)**
   - **Observations:** Documented packets where my machine broadcasts a request asking *"Who has 192.168.1.1? Tell 192.168.1.7"* to dynamically discover the router's MAC address.

3. **TLS (Transport Layer Security)**
   - **Observations:** Captured encrypted application data payloads (`TLSv1.2`), verifying that modern web communication remains secure from plain-text exposure.

## Deliverables
- `network_traffic.pcapng`: The raw packet capture data.
- Filtered screenshots demonstrating protocol identification.

