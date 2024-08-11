# Task Six: ICMP Packet Capture Using Wireshark

This repository contains a packet capture file (`ping.pcapng`) generated using Wireshark on Kali Linux. The task involved capturing ICMP packets during a `ping` operation to `google.com`, filtering the capture to only include four ICMP Echo Request and four ICMP Echo Reply packets, and saving the results.

## Steps Followed

### 1. Open Wireshark and Start Capturing Packets
- **Wireshark Interface**: Wireshark was opened on Kali Linux.
- **Network Interface**: The `eth0` interface was selected for packet capture.
- **Packet Capture**: The capture was started to monitor network traffic on `eth0`.

### 2. Ping Google.com from the Terminal
- **Ping Command**: The following command was executed in the terminal:
  ```bash
  ping -c 4 google.com
### 3.Observe Captured ICMP Packets in Wireshark
- **Stopping the Capture**: After the ping command completed, the packet capture was stopped.
- **Filtering for ICMP**: The capture was filtered to display only ICMP packets using the icmp filter.  
- **File Saving**: The filtered capture was saved as `ping.pcapng`.
