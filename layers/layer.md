# OSI

In networking, data is encapsulated at different layers of the `OSI (Open Systems Interconnection)` model and the TCP/IP model. Each layer has its own name for the data it handles.

![layerwise data](image.png)

## OSI Model Data Names

1.  Application Layer (Layer 7):

        - Data Name: Data (or Message)
        - This is the layer where user-level protocols operate (e.g., HTTP, FTP).

Presentation Layer (Layer 6):

Data Name: Data (or Message)
Responsible for data formatting, encryption, and compression.
Session Layer (Layer 5):

Data Name: Data (or Message)
Manages sessions between applications.
Transport Layer (Layer 4):

Data Name: Segment (for TCP) or Datagram (for UDP)
Provides end-to-end communication and error recovery.
Network Layer (Layer 3):

Data Name: Packet
Handles routing of data across multiple networks.
Data Link Layer (Layer 2):

Data Name: Frame
Responsible for node-to-node data transfer and error detection.
Physical Layer (Layer 1):

Data Name: Bit
Deals with the transmission of raw binary data over physical media.
