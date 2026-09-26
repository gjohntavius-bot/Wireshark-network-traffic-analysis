# Wireshark Network Traffic Analysis

## Project Overview
This project demonstrates hands-on network traffic analysis using Wireshark. I analyzed DNS traffic to better understand how devices resolve domain names, communicate with DNS servers, and use different DNS record types.

## Tools Used
- Wireshark 4.6.9
- macOS
- DNS protocol analysis

## What I Analyzed
During this project, I examined DNS queries and responses and identified several DNS record types:

- **A Record** — Maps a domain name to an IPv4 address.
- **AAAA Record** — Maps a domain name to an IPv6 address.
- **MX Record** — Identifies mail servers responsible for receiving email for a domain.
- **PTR Record** — Performs reverse DNS lookups by mapping an IP address back to a hostname.
- **TXT Record** — Stores text-based information that can be used for domain ownership and service verification.

## Key Findings
- Identified DNS query and response packets and matched requests with their corresponding responses.
- Examined IPv4 address resolution through DNS A records.
- Analyzed MX records and their preference values to understand mail server priority.
- Examined PTR records to understand reverse DNS lookups.
- Analyzed TXT records and their role in storing domain-related information.
- Observed how DNS servers respond to different types of DNS requests.

## Screenshots

The `Screenshots` folder contains packet captures documenting the analysis:

1. DNS response analysis
2. IPv4 DNS resolution
3. MX record analysis
4. Reverse DNS / PTR lookup
5. TXT record analysis

## Skills Demonstrated
- Network traffic analysis
- Wireshark packet analysis
- DNS analysis
- IPv4 and IPv6 fundamentals
- Network troubleshooting
- Packet inspection
- Technical documentation

## What I Learned
This project gave me practical experience analyzing network traffic instead of only studying networking concepts. Using Wireshark helped me see how DNS requests and responses operate at the packet level and strengthened my understanding of how domain names are resolved across a network.
