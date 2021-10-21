- 4th layer from top
- Main role: connect communication services to application processes on diff hosts
- transport layer protocols are implemented in the end systems but not in the network routers
- Protocols:
  - TCP - Transmission Control Protocol - Relaible
  - UDP - User Datagram Protocol - Unrelaible
- Services provided: multiplexing/demultiplexing, reliable data transfer, bandwidth guarantees, and delay guarantees.
- The applications can read and write to the transport layer. Therefore, we can say that communication is a two-way process.

---


![](https://static.javatpoint.com/tutorial/computer-network/images/transport-layer.png)

---

- The services provided by the transport layer are similar to those of the data link layer. The data link layer provides the services within a single network while the transport layer provides the services across an internetwork made up of many networks. The data link layer controls the physical layer while the transport layer controls all the lower layers.

- 5 categories

  - End-to-end delivery
    - The transport layer transmits the entire message to the destination. Therefore, it ensures the end-to-end delivery of an entire message from a source to the destination.

  - Addressing
    - 


  - Reliable delivery
    - The transport layer provides reliability services by retransmitting the lost and damaged packets.
    - Error control
    - Sequence control
    - Loss control
    - Duplication control

  - Flow control
    - Uses Sliding window protocol - Byte oriented

  - Multiplexing
    - Upward - make cost effective
    - Downward - improve throughput - slow/low capacity


