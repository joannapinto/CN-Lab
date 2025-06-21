#### Network Simulation and Error Detection Programs

This repository contains various C programs related to network simulation, error detection, and correction algorithms. Each program serves as a practical example for exploring computer networking and data communication concepts.

#### Programs List

1. **CRC-CCITT Error Detection**
   Computes the 16-bit CRC-CCITT value for a given message.

2. **Hamming Code Generation**
   Generates and verifies Hamming codes for error detection and correction.

3. **Frame Sorting Techniques**
   Simulates sorting frames in network buffers using multiple sorting techniques.

4. **TCP/IP Socket Communication**
   A simple client-server file transfer program over TCP/IP sockets.

5. **Distance Vector Algorithm**
   Implements a routing protocol to determine the shortest data transmission path.

6. **Leaky Bucket Algorithm**
   Demonstrates congestion control using the leaky bucket mechanism.

7. **Point-to-Point Network Simulation (3 Nodes)**
   Simulates a network with three nodes, allowing queue and bandwidth adjustments.

8. **Point-to-Point Network Simulation (4 Nodes)**
   Models a four-node network with TCP and UDP agents to measure packet loss.

9. **Internet Traffic Simulation**
   Analyzes the throughput of FTP and TELNET traffic in a simulated environment.

10. **Ping Message Transmission**
    Simulates sending ping messages in a six-node topology and identifies packet drops.

11. **Ethernet LAN Simulation**
    Simulates Ethernet LAN behavior with multiple nodes to study collisions.

#### How to Compile and Run

1. Install a C compiler, such as GCC.
2. Download the source files for the desired program.
3. Navigate to the program's directory:

   ```
   cd path/to/program
   ```
4. Compile the program:

   ```
   gcc program_name.c -o program_name
   ```
5. Execute the compiled program:

   ```
   ./program_name
   ```

#### Simulation Notes

* Network simulation programs (7–11) may require advanced network simulation tools, such as NS2 or NS3, for visualization.
* You can modify the source code for custom parameters like node count, bandwidth, or queue size.
* Ensure all required libraries and dependencies are installed for smooth execution.
