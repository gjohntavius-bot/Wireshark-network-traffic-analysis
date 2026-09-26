{\rtf1\ansi\ansicpg1252\cocoartf2870
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 HelveticaNeue-Bold;\f1\fnil\fcharset0 HelveticaNeue;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\deftab560
\pard\pardeftab560\pardirnatural\partightenfactor0

\f0\b\fs40 \cf0 Wireshark Network Traffic Analysis Project Notes\
\pard\pardeftab560\slleading20\partightenfactor0

\f1\b0\fs26 \cf0 \
\
\
\pard\pardeftab560\slleading20\pardirnatural\partightenfactor0

\fs28 \cf0 Project: Network Traffic Analysis Using Wireshark\
\
Date: September 26, 2026\
\
Objective:\
Learn how to use Wireshark to analyze network traffic and identify common network protocols such as DNS, TCP, and HTTPS/TLS.\
\
Tools:\
- Wireshark 4.6.9\
- macOS\
\
What I Learned: I analyzed DNS traffic using Wireshark. I identified a DNS AAAA query for {\field{\*\fldinst{HYPERLINK "http://www.l.google.com"}}{\fldrslt www.l.google.com}} and examined the corresponding response. The DNS server returned the response without an error, but the response contained 0 answer records. I also learned that an A record requests an IPv4 address, while an AAAA record requests an IPv6 address. \
\pard\pardeftab560\slleading20\pardirnatural\partightenfactor0

\f0\b\fs26 \cf0 \
\
\'95 Learned how DNS converts domain names into IP addresses that computers use to communicate.
\f1\b0 \
\pard\pardeftab560\slleading20\partightenfactor0

\f0\b \cf0 \
\pard\pardeftab560\slleading20\pardirnatural\partightenfactor0
\cf0 \
\'95 Learned how to identify DNS query and response packets and match a request with its response.\
\pard\pardeftab560\slleading20\partightenfactor0
\cf0 \
\
\pard\pardeftab560\slleading20\pardirnatural\partightenfactor0
\cf0 \
\'95 Learned that A records map domain names to IPv4 addresses, while PTR records perform reverse DNS lookups by mapping IP addresses back to hostnames.\
\pard\pardeftab560\slleading20\partightenfactor0
\cf0 \
\
\pard\pardeftab560\slleading20\pardirnatural\partightenfactor0
\cf0 \
\'95 Learned that MX records identify the mail servers responsible for receiving email for a domain and use preference values to determine priority.\
\pard\pardeftab560\slleading20\partightenfactor0
\cf0 \
\
\pard\pardeftab560\slleading20\pardirnatural\partightenfactor0
\cf0 \
\'95 Learned that TXT records can store text-based information used for purposes such as domain ownership and service verification.}