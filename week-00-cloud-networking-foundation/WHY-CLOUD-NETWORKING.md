# How Networking Worked Before Cloud

## Before cloud, companies had:

- On-prem data centers

- Physical routers (Cisco/Juniper)

- Firewalls

- MPLS links

- Manual configuration

Example:
A company hosting servers in their office connects users via:

- LAN

- MPLS

- VPN

## Everything was:

- Hardware dependent

- Slow to scale

- Expensive

- Manually managed

## ❓ Problems with Traditional Networking

- Scaling takes weeks

- Hardware procurement delays

- Complex DR setup

- Expensive MPLS

- Global expansion is slow

- Manual config = human error

# What Cloud Changed

Enter:

Amazon Web Services

Microsoft Azure

Google Cloud Platform

They introduced:

🔹 Virtual Data Centers

Instead of racks → You create:

VPC

Subnets

Route Tables

Gateways

All via API.

🔹 What is a VPC?

A VPC is:

A logically isolated virtual network inside a cloud.

It includes:

IP ranges

Subnets

Route tables

NAT gateways

Internet gateways

Security groups

It looks like networking…
But it is software-defined networking (SDN).

# Why Cloud Networking is Critical

Now answer this:

If compute moved to cloud,
Where does traffic flow?

Between:

VM ↔ VM

Pod ↔ Pod

Cloud ↔ On-prem

Cloud ↔ Cloud

User ↔ SaaS

Branch ↔ Cloud

Everything depends on networking.

Without networking:
Cloud is useless.

🚨 Key Realization

Cloud is not compute.
Cloud is networking + compute + storage.

Networking is the backbone.

# Relationship Between Cloud & Networking
Traditional Networking	Cloud Networking
Hardware routers	Virtual routers
CLI config	API-driven config
Static provisioning	Elastic scaling
Physical topology	Logical topology
Manual BGP	Automated BGP

Cloud networking = Networking as Code

# Why This Matters For You

You want to build:

Self-service IPSec

Multi-cloud routing

FRR automation

Control plane design

Hybrid connectivity

That is pure cloud networking innovation.

