# Wireshark-Capture-Packets

## Objective

Acquired proficiency in utilizing Wireshark, a leading network protocol analyzer, for capturing, analyzing, and interpreting network traffic data. Developed the ability to troubleshoot network issues, identify security threats, and optimize network performance through hands-on experience with packet capture and analysis techniques. Demonstrated competency in protocol decoding, session reconstruction, and statistical analysis, enhancing capabilities in network monitoring, optimization, and security analysis.


### Skills Learned

- Install and set up Wireshark on Linux.
- Capture and save packets on a detected network using Wireshark.
- Use a display filter to observe certain packet protocols.
- Employ a display filter to detect a certain IP address in a capture.
- Use a conditional filter to locate certain packets in a capture.

### Tools Used

- Wireshark
- Tcpdump
- Mozilla Firefox

## Steps
Problem: Use wireshark to create a capture file and then use a display filter to list all https and http packets.
You will then eliminate one I.P. Address from the capture using a display filter.


<p align="center">
Start a packet capture on the ethernet in wireshark. Visit google, duck duck go and http.cygwin.com.  
<br/>
<img src="https://i.imgur.com/tKocPI6.png" height="80%" width="80%"/>
<br/>
<br/>
<img src="https://i.imgur.com/ZEJkAVH.png" height="80%" width="80%"/>
<br/>
<br/>
Stop the packet capture in wire shark and save the capture to a file. Then created a filter to just display port 80 TCP data. This should show the I.P. Address of Cygwin.  
<br/>
<img src="https://i.imgur.com/BHpGaL4.png" height="80%" width="80%"/>
<br/>
<br/>
Created a filter to display only http and https packets and Eliminate the Cygwin site visits from the displayed packets
<br/>
<img src="https://i.imgur.com/USTdLt3.png" height="80%" width="80%"/>
<br/>
<br/>
