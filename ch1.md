# Chapter 1 - Introduction to Communication Methods

## Objectives

1. What are communication networks?
2. Why communication networks?
3. How do they work?
4. What shall we learn in this course?

Telecommunications: to pass the information by means fo electrical signals

## Basic Communication System

In general, a communication system should consist of 3 parts:

1. __Transmitter__ that has data to send
2. __Receiver__ is the destination of the data
3. __Channel__ is the medium of connecting the transmitter and receiver

```
Transmitter --(Channel)--> Receiver
```

In order to reduce cost, different information flows share common communication channel:

```
(T1, T2, ... , Tn) ----> (R1, R2, ..., Rn)
```

The signal power is attenuated due to distance travelled, but this is usually fixed with __intermediate tranceivers (repeaters)__.

In order to achieve the reliable exchange of information with low cost, we need a mesh connection of links (channels) and switches (transceivers, repeaters etc).

- something -

The links (physical media) includes copper wire, fiber optics (guided channels) as well as radio, microwaves (wireless channel).

The switches (routers) are boxes with input and outp links. When traffic arrives, the router figures out the output link. After some delay, the router sends the traffic on the output link.

Communication networks are arrangements of hardware and software that allows users to exchange information.

Networks can be classified based on the type of the channel:

- Wireless (radio, microwave)
- Wired (fiber optics)

Or on the type of the switching:

- Telephone network -> circuit switching
- Internet -> packet switching

### Circuit Switching

A path from a source to a destination is established before a message is transmitted. All links along the path between the source and the destination are used during the entire transmission. When the traffic is bursty the network resources (links and routers) tend to be poorly utililized.

Circuit switching minimizes the delay of the information transfer because all the forwarding decisions are made once and for all when the connection is setup.

Properties: dedicated path, fixed capacity, minimum delay (good), poor resource utilization (bad)

### Packet Switching

A message is first segmented into blocks of data called __packets__ (a group of bits typically from a few hundres to thousands). Packets are then transmitted