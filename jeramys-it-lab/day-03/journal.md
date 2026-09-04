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


**2026-08-24**

TCP/IP layers one by one.
Layer 1: Physical layer

In my own words:
- The Physical layer sends and receives bits as electrical, optical, or radio signals over a medium.
- It defines things like cables, connectors, signal levels, and link speeds.
- Examples: copper UTP cables, fiber-optic cables, Wi-Fi (radio and antennas), and network interface cards (NICs).

Breaking down these layers in depth will help me understand them better.


**2026-09-01**

Layer 2: The local network

In my own words:
- Layer 2 provides hop-to-hop delivery of messages on a local network.
    - A hop is one step along the path between two devices (a router and an end host).
    - Switches don't count because they only extend the LAN.
    - MAC addresses are used for hops so the message can travel along the correct path.
- A MAC (Media Access Control) address is the unique hardware address of a network interface (NIC) on a local network.

When I was learning this, MAC addresses really confused me. I thought they were something else, but after a quick chat with ChatGPT, it all became clear to me.


**2026-09-02**

Layer 3: The internet layer (Internetwork layer)

In my own words:
- This layer provides end to end delivery between hosts across multiple networks. It identifies devices/Servers/Computers across the internet.
- This layer uses IP addresses to identify hosts.
- Routers operate mainly at this layer, using the messeges's destination Ip address to forward the message towards its final distenation host.
- Protocol at this level include: IP(IPv4, IPv6) and ICMP(Internet control messege protocol).

Routers are very interesting because they are one of the hardware you install in your home, so I am exicited to study and understand it further.
No idea what the difference between the two version of IP addresses is yet, excited to learn about it in further videos.
