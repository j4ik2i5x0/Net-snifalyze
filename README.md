<h1>Snifalyze: Network Packet Sniffer & Analyzer</h1>

## Overview
**Snifalyze** is a powerful network packet sniffer and analyzer built using Go (Golang). Designed for developers, network engineers, and security professionals, it provides a comprehensive solution for capturing, analyzing, and visualizing network traffic in real-time. With an intuitive interface and robust features, PacketScope empowers users to gain valuable insights into network activity.

## Features

- **Real-time Packet Capture**: Capture live packets from selected network interfaces with customizable filters for TCP, UDP, and ICMP protocols.
- **Detailed Packet Analysis**: Examine packet details, including source and destination IP addresses, ports, and protocol types.
- **Traffic Statistics**: View comprehensive statistics, including packet counts for TCP, UDP, and ICMP, providing insights into network performance.
- **PCAP File Logging**: Save captured packets to PCAP files for later analysis, enabling detailed examination of historical network traffic.
- **User-Friendly Interface**: Easy-to-navigate interface with HTML, CSS, and JavaScript for effective visualization and interaction with captured data.

## Technologies Used

- **Programming Language**: Go (Golang)
- **Libraries**: 
  - [gopacket](https://github.com/google/gopacket) for packet capture and analysis
  - [pcap](https://github.com/google/gopacket/pcap) for working with network interfaces
- **Frontend**: HTML, CSS, JavaScript

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/snifalyze.git
    cd Snifalyze
    ```

2. **Install Dependencies**:
    ```bash
    go get github.com/google/gopacket
    go get github.com/google/gopacket/pcap
    ```

3. **Run the Application**:
    ```bash
    go run main.go
    ```

## Usage

1. Select the network interface from which you want to capture packets.
2. Set any optional filters for specific protocols (TCP, UDP, ICMP).
3. Start capturing packets and monitor the traffic in real-time.
4. Review statistics and export data as needed.

## Contribution

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

## Acknowledgments

- Thanks to the [Go](https://golang.org/) community for their support and excellent resources.
- Special thanks to the developers of [gopacket](https://github.com/google/gopacket) for creating a powerful packet processing library.

## Contact

For questions or feedback, please reach out to me at [your.email@example.com](mailto:your.email@example.com).
