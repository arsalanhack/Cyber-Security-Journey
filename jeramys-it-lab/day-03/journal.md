# Day 3 - Jeramy's IT LAB (CCNA by Jeramy)

**Topic: TCP/IP**

**2026-08-18**

Learned a few basic things about standards and their history.

In my own words:
- A protocol is a set of rules that defines how data should be communicated between devices over the Internet
- Vint Cerf and Bob Kahn began developing TCP (Transmission Control Program) in 1974.
    - Later branched to TCP (Transmission Control Protocol) and IP (Internet Protocol).
- A standard is an agreed-upon specification that describes how a protocol or technology should work.
    - With vendor-neutral standards, devices of all types can communicate with each other.
    - For example: A MacBook can access a website hosted on a server that runs Linux.

- Standards are developed by independent organisations rather than a single engineer. Two big networking organisations are the IEEE (Institute of Electrical and Electronics Engineers) and IETF (Internet Engineering Task Force).
    - IEEE mainly develops technologies used in local area networks, for example: Ethernet and Wi-Fi.
    - IETF defines protocols used on the Internet, for example: TCP, IP, UDP, HTTP, DNS, etc.


**2026-08-23**

The layered model

In my own words:
- Networks do a lot of jobs: Physical transmission of signals, local delivery on LAN and routing traffic between networks etc.
- A model lets us group related jobs into layers.
    - Each layer has a specific role.
    - Each layer uses the services of the layer below it and provides services to the layer above.
- Each individual protocol primarily belongs to one particular layer.
    - TCP, UDP -> Application layer.
    - Internet protocol -> Internet layer (IPv4, IPv6).

We are finally getting into the models, I never understood these models properly before. This time I will understand them fully.


**2026-08-24**

Further into TCP/IP model.

In my own words:
- Each layer has its own job
    - Layers work together to deliver the message, but each one focuses on its own task.
- What happens inside one layer doesn't change the job of the other layers.
- Web browsers(like Chrome) are also called Web client application.
1. Application layer: Protocols for communication between application process; create and interpret the data.
2. Transport layer: Provides end to end communication between application process using port numbers.
3. Internet layer: Provides end to end communication between hosts across networks using IP addresses and routers.
4. Local network layer: Provides hop to hop delivering within a local network using MAC address and switches.
5. Physical layer: Sends bits as electrical, optical, or radio signals over physical medium.

Finally understood how the TCP/IP model works. How the layers work together and how important each one is. Excited to learn the OSI model next.
