•What is it: TCP SYN Flood attack, form of DOS attack. 

•Happens with: Networking Vulnerabilities(layer 3) 

•When does it happen: During TCP three-way handshake. 

•What does it do: Allows attacker to repeatedly send SYN packets without responding with ACK

What this code does: With this script, we take a specified IP and Port number and forge a SYN packet starting with the IP layer. Forge TCP layer by setting source port to random short and dport as target port. Set flags to "S" indicating type "SYN". Then add flooding raw data to occupy network. Stack all the layers, and send packet. This send function sends packets to layer 3, with loop set to 1 until progam is quit.
