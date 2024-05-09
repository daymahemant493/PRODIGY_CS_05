# Packet Sniffer

This Python script is a simple packet sniffer tool that captures and logs network packets. It displays the source and destination IP addresses, protocol, and payload of each packet.

## Usage

1. Ensure you have Python installed on your system.
2. Install the required dependencies listed in the `requirements.txt` file using `pip install -r requirements.txt`.
3. Run the `packet_sniffer.py` script.
4. You will be prompted to accept the terms and conditions.
5. If you accept the terms, packet sniffing will begin.
6. Press `Ctrl+C` to stop packet sniffing.
7. Packet details will be logged in the `packet_log.txt` file.

## Functions

- `display_terms()`: Displays the terms and conditions of using the packet sniffer tool.
- `accept_terms()`: Prompts the user to accept the terms and conditions.
- `packet_callback(packet)`: Callback function to process each captured packet and log its details.

## Requirements

- Python 3.x
- scapy
- colorama

## Terms and Conditions

1. This packet sniffer tool is provided for educational and informational purposes only.
2. You agree not to use this tool for any illegal or unethical activities.
3. The developers of this tool are not responsible for any misuse or damage caused by its usage.
4. Use of this tool may be subject to local laws and regulations. It is your responsibility to ensure compliance.

## Disclaimer

This script is provided for educational purposes only. The author is not responsible for any misuse or damage caused by this software.

