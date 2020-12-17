---
title: 'What is the Internet and how does it work?'
date: '2020-12-16'
---

It's hard to imagine life today without the **Internet**.
It is part of our daily life and makes us to be always connected and available on our phones and apps, from the time we wake up to the time that we go to bed.
But have you ever asked yourself **what is** the Internet?
In this post I'll talk about the technology and some interesting details that connects us and completely changed the way we live our lives and interact.


**Part 1: what is the Internet**

The technical definition says that the Internet is **a global system of interconnected computer networks that communicate using a set of predefined protocols**.
In other words, it is a very large scale network that connects computers all around the world and has a specific set of rules that allow new devices to communicate with the existing infrastructure.

To breakdown this idea, let's first look at what is a computer network.
Computer in this definition refers to a loose set of devices that can run programs and send and receive digital messages. It's not only the desktop or laptop computer that comes to mind, which has a monitor, a keyboard, or other input/output peripherals. For example, our smartphones are definitely computers and can communicate to other devices in many ways, including the cellular network, the wi-fi, Bluetooth, the usb cable, etc.
When we have two or more of these devices connected by any technology we have a computer network.

It is said to be global because the Internet today connects devices all over the world. The infrastructure to achieve this large scale is very diverse. We use many technologies to connect computers, and each of them has a limit of how many simultaneous devices can be connected and communicating.
The network of networks concept starts here. The global scalability of the Internet comes from this idea of connecting various smaller networks to create a global system with a much higher ceiling for the number of devices.
It is achieved by a set of predefined protocols, most notably the Internet Protocol (IP) and the  Transmission Control Protocol (TCP), which allow messages to be sent out and arrive reliably at the intended destination in a  decentralised set of communication links.


**Part 2: the TCP/IP protocols**

The digital computer as we know is a relatively recent technology, which emerged from the work of many researchers and engineers. The first electronic digital computer - ENIAC - was built in 40's (Yes, I think 80 years is a short time ;p). Initially, the challenge of building a single machine was large enough. But soon the need to exchange messages between those machines in order to perform more complex tasks inspired the development of computer networks.

Earlier in this post we saw that two communication protocols called IP and TCP are a important for the Internet in some way. Well, it turns out that they are the CORE of what we call Internet and now we will understand why.

IP is a common term in the context of computer networks and applications and is commonly used to refer to the IP address of a machine in a network. Well, IP is also the name of the protocol that allows for multiple machines to exchange messages, which uses a numeric address to identify all unique hosts that are connected to this network. We can imagine that the IP address in a computer network is comparable to the address of our house. Our street address together with the information of the city, state/region and country is a unique identifier that can be used to locate our house in the planet. Using this information we can send a letter from anywhere and, hoping the mail service works correctly, we can be sure that it will be delivered to the intended destination. In the same way, an IP address on the Internet can  be used to identify and locate a specific machine and send a message to that host. What the IP protocol does is exactly that: given the information about the source and destination of a packet - together with the message content - it moves this packet around with the goal of eventually delivering it to the intended destination. There's a lot to how IP can know exactly what to do with each packet that is sent and what is the infrastructure that is used to move those packets from one computer to the other, but that's the basic idea of this protocol.

One detail about the IP protocol is that after we send a message to the Internet, we completely lose control of what happens to that information. In other words, there's no way for the sender to know if a message was correctly delivered or if it was delivered at all only with the IP protocol. Going back to the snail mail parallel, it is the same as sending an unregistered letter. If the letter is lost, or delivered to the wrong destination, the sender will not receive any alert or message back. But we may have the option to send a registered letter, which requires a signature at the delivery and can be tracked by the sender using a protocol number. And that's where TCP works for the Internet. The TCP protocol provides reliable, ordered and error-checked delivery of a stream of bytes between two hosts in an IP network. These features are achieved by creating a closed loop connection between the two hosts where, for instance, messages from one host are acknowledged by the other side with a small packet that confirms the correct arrival of the packet, among other features.

TCP also controls the rate in which the messages should be sent in order to achieve a reasonable speed without exceeding the capacity of the underlying infrastructure. That's a topic for another post that I want to write here in the blog some day.

**Conclusion**

Coming down to the technical details, what we call the Internet is in fact a set of communication protocols that allows digital computers to communicate with each other in a very scalable way.

However, the term has a much larger meaning. It is a social space and connects people in ways that were unimaginable not too long ago. Together with many other technology improvements it changed the life as we know and has became central to the human experience.

But it is a topic for another day and post...
