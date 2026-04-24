# 🧩 packet-tracer-network-project - Simple Network Setup Practice

[![Download the project](https://img.shields.io/badge/Download%20Project-blue?style=for-the-badge)](https://github.com/Denagobletshaped136/packet-tracer-network-project)

## 📥 Download

Use this link to visit the project page and download the files:
https://github.com/Denagobletshaped136/packet-tracer-network-project

## 🖥️ What this project is

This project shows a basic network setup in Cisco Packet Tracer. It uses a router, a switch, and end devices to show how network parts connect and work together.

You can use it to:

- see how devices connect in a small network
- learn simple IP address setup
- test if devices can talk to each other
- open the file in Cisco Packet Tracer on Windows

## ✅ What you need

Before you start, make sure you have:

- a Windows PC
- Cisco Packet Tracer installed
- a web browser
- enough space to save the project file

If you do not have Cisco Packet Tracer yet, install it first, then open the project file after download.

## 🔧 Files in the project

This project focuses on a small network lab. You can expect files such as:

- Packet Tracer project file
- saved network layout
- device setup for router and switch
- IP address setup for connected devices

## 🚀 How to download on Windows

1. Open the project link above.
2. On the GitHub page, look for the file list or release files.
3. Download the project file to your computer.
4. Save it in a folder you can find later, such as Downloads or Desktop.
5. If the file comes in a ZIP folder, right-click it and choose Extract All.

## 🧭 How to open the project

1. Start Cisco Packet Tracer.
2. In Packet Tracer, choose File.
3. Select Open.
4. Go to the folder where you saved the project.
5. Open the Packet Tracer file.

If the file does not open right away, make sure you are using a version of Packet Tracer that can read the project format.

## 🖱️ Basic steps inside the project

When the file opens, you should see a small network with a router, a switch, and one or more devices.

Check these parts:

- router links to the switch
- switch links to the end devices
- each device has an IP address
- devices can reach each other through the network

## 🌐 IP addressing used in this project

This lab uses simple static IP addressing so the network is easy to follow.

A basic setup may look like this:

- Router interface: 192.168.1.1
- Switch management IP: 192.168.1.2
- PC 1: 192.168.1.10
- PC 2: 192.168.1.11
- Subnet mask: 255.255.255.0
- Default gateway: 192.168.1.1

These addresses help each device find the others on the same network.

## 🧪 How to test connectivity

After you open the file, test the network connection.

### On a PC in Packet Tracer

1. Click the PC.
2. Open Desktop.
3. Select Command Prompt.
4. Type:

   ping 192.168.1.1

5. Press Enter.

If the reply works, the PC can reach the router.

You can also test another PC:

- ping 192.168.1.11

If the reply works, the devices can communicate through the switch and router.

## 🔌 Router and switch setup

This project includes a simple setup for a small local network.

### Router

The router helps move traffic between parts of the network. In a basic lab like this, it usually:

- has one active interface
- uses an IP address on the local network
- acts as the default gateway for devices

### Switch

The switch connects the devices inside the network. It helps:

- pass traffic between PCs
- keep the network organized
- connect multiple devices with Ethernet cables

### End devices

The end devices are the user computers. They:

- have IP addresses
- use the router as the gateway
- send test traffic with ping

## 🪟 How to use this on Windows

To run the project on Windows:

1. Download the file from the GitHub link.
2. Install Cisco Packet Tracer if it is not already on your PC.
3. Open Packet Tracer.
4. Load the downloaded project file.
5. Check the device setup and run a ping test.

If the file is in a ZIP folder, extract it first before opening it in Packet Tracer.

## 🧰 Common checks if the network does not work

If the test fails, check these items:

- the cable connections are in place
- each device has the right IP address
- the subnet mask matches on all devices
- the router interface is turned on
- the default gateway is set on each PC
- the file opened in the right version of Packet Tracer

## 📚 What you can learn from this project

This project can help you learn:

- how a small network is built
- how to connect a router and switch
- how to set IP addresses
- how to check network reachability
- how basic LAN traffic works

## 🧩 Simple project layout

A basic layout for this project may include:

- 1 router
- 1 switch
- 2 PCs
- Ethernet cables
- one local IP network

This is a good starting point for learning network setup without a large lab.

## 📝 Example setup steps

If you want to rebuild the lab, use these steps:

1. Add a router to the workspace.
2. Add a switch next to it.
3. Add two PCs.
4. Connect the router to the switch.
5. Connect each PC to the switch.
6. Set the IP address on each PC.
7. Set the router IP address.
8. Test with ping.

## 🛠️ Suggested Packet Tracer settings

For a clean lab, use:

- straight-through cables for device links
- one subnet for all devices
- manual IP settings
- simple device names like PC1, PC2, Router1, and Switch1

These settings keep the lab easy to read and easy to test.

## 📂 Where to keep the file

Use a folder such as:

- Downloads
- Desktop
- Documents\PacketTracer

A short folder path makes it easier to find the file when you open Packet Tracer.

## 🔎 Troubleshooting file access

If Windows does not open the file the right way:

- right-click the file
- choose Open with
- select Cisco Packet Tracer
- make Packet Tracer the default app if needed

If the file is inside a ZIP folder, extract the contents first.

## 📶 Expected result

When the project is set up right, you should be able to:

- open the network in Packet Tracer
- see the router, switch, and PCs
- ping between devices
- confirm the network path works

## 📎 Download and setup link

Use this page to download the project files:
https://github.com/Denagobletshaped136/packet-tracer-network-project

## 🖼️ Quick view of the workflow

Download the file → Open it in Packet Tracer → Check device IPs → Run ping tests → Confirm connectivity