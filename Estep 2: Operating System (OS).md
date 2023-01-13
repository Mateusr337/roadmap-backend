# Operational System (OS)

## What is an OS?

An operating system is a program that acts as an interface between the user and the computer hardware and controls the execution of all kinds of programs.

**Example** Linux, Windows, AXIS etc.

## Memory Management

Memory management is a method in the operating system to manage operations between main memory and disk during process execution.

**Main Memory** ⇒ known as RAM.

**Physical and logic memory** ⇒ The physical memory is locals of data is allocated, and the logic memory is the steps who to go to process.

**Swapping** ⇒ It is the change in allocated memory process

- Swapping in ⇒ allocated in main memory
- Swapping out ⇒ withdraw of main memory

## **Inter Process Communication (IPC)**

Inter-process communication (IPC) is a mechanism that allows processes to communicate with each other and synchronize their actions

**A process can be of two types:**

- **Independent process** ⇒ It doesn't have influence with others processes.
- **Co-operating process** ⇒ It has influence with others processes.

**Co-operating process can be of two types:**

- **Shared Memory** ⇒ ****Some processes will have access from the same memory.
- **Message passing** ⇒ this can be by link (indirect or direct) or exchanging messages:

## I/O Management

One of the important jobs of an Operating System is to manage various I/O devices including mouse, keyboards, touchpad, disk drives, display adapters, USB devices, Bit-mapped screen, LED, Analog-to-digital converter, On/off switch, network connections, audio I/O, printers etc.

An I/O system is required to take an application I/O request and send it to the physical device, then take whatever response comes back from the device and send it to the application. I/O devices can be divided into two categories:

- **Block devices** − A block device is one with which the driver communicates by sending entire blocks of data. For example, Hard disks, USB cameras, Disk-On-Key etc.
- **Character devices** − A character device is one with which the driver communicates by sending and receiving single characters (bytes, octets). For example, serial ports, parallel ports, sounds cards etc

**Device Controllers**

Device drivers are software modules that can be plugged into an OS to handle a particular device. Operating System takes help from device drivers to handle all I/O devices.

## **What is computer networking?**

Computer networking refers to interconnected computing devices that can exchange data and share resources with each other. These networked devices use a system of rules, called communications protocols, to transmit information over physical or wireless technologies.

## **What is network topology?**

The arrangement of nodes and links is called network topology. They can be configured in different ways to get different outcomes. Some types of network topologies are:

**Bus topology** ⇒ Each node is linked to one other node only. Data transmission over the network connections occurs in one direction.

**Ring topology** ⇒ Each node is linked to two other nodes, forming a ring. Data can flow bi-directionally. However, single node failure can bring down the entire network.

**Star topology** ⇒ A central server node is linked to multiple client network devices. This topology performs better as data doesn’t have to go through each node. It is also more reliable.

**Mesh topology** ⇒ Every node is connected to many other nodes. In a full mesh topology, every node is connected to every other node in the network.
