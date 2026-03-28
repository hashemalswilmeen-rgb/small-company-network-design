# Small Company Network Design using Cisco Packet Tracer

## Overview

This project simulates a small company network using Cisco Packet Tracer. The network is divided into multiple departments using VLANs, with inter-VLAN communication handled by a router-on-a-stick design. A separate server VLAN was also implemented, along with DHCP and SSH for remote management.

## Network Structure

The network contains:

* 1 Router
* 2 Switches
* 6 PCs
* 1 Server

## VLAN Configuration

* VLAN 10: HR
* VLAN 20: IT
* VLAN 30: Sales
* VLAN 40: Server

## IP Addressing

* HR: 192.168.10.0/24
* IT: 192.168.20.0/24
* Sales: 192.168.30.0/24
* Server: 192.168.40.0/24

## Technologies Used

* Cisco Packet Tracer
* VLANs
* Trunking
* Router-on-a-Stick
* Inter-VLAN Routing
* DHCP
* SSH

## Features

* Department segmentation using VLANs
* Trunk links between router and switches
* Inter-VLAN communication
* Separate server VLAN
* Automatic IP assignment using DHCP
* Secure remote access using SSH

## Configuration Summary

* VLANs were created on the switches and assigned to department ports
* Trunk ports were configured between the router and main switch, and between both switches
* Router subinterfaces were configured for each VLAN
* DHCP pools were created on the router for automatic IP assignment
* SSH was configured on the router for remote access

## Testing

The following tests were completed successfully:

* PC to default gateway
* Communication between VLANs
* Communication with the server
* DHCP address assignment
* SSH login to the router

## What I Learned

Through this project, I learned how to:

* Design a segmented company network
* Configure VLANs and trunk ports
* Implement inter-VLAN routing
* Configure DHCP on a router
* Use SSH for remote device management
* Troubleshoot connectivity issues in Packet Tracer

## Files

* `company_network.pkt` — Packet Tracer project file
* `topology.png` — network topology screenshot
* `ping-test.png` — connectivity test screenshot
* `dhcp-test.png` — DHCP assignment screenshot
* `ssh-test.png` — SSH access screenshot
