# Introduction to Static Routing-Computer Networks 


## Description
This project delves into the world of static routing, explaining how routers forward packets in a network using manually configured routes. It covers the essentials of configuring static routes, understanding the routing table, and applying routing principles to ensure successful packet delivery between devices.

## Table of Contents
- [Introduction](#introduction)
- [Directly Connected Networks](#directly-connected-networks)
- [Static Routing](#static-routing)
- [Routing Table Principles](#routing-table-principles)
- [Summary and Default Routes](#summary-and-default-routes)
- [Summary](#summary)

## Introduction
Routers forward packets from the source device to the destination device using a routing table. This project illustrates a network topology with three routers and two hosts, demonstrating the setup and configuration of static routes to enable communication between the hosts.

## Directly Connected Networks
The routing table contains information about various networks. By default, a router only knows about directly connected networks. This section explains how directly connected networks are identified and how routers communicate with them.

## Static Routing
Static routes are used to manually configure paths to remote networks. This section covers:
- Configuring static routes.
- Understanding stub networks.
- Example commands to configure static routes on routers.

## Routing Table Principles
Three key principles guide routing decisions:
1. Routers forward packets based on their routing tables only.
2. Routing information on one router does not imply other routers have the same information.
3. Routes to a remote network do not mean the remote router has return paths.

Applying these principles ensures proper configuration of static routes across all routers in a network.

## Summary and Default Routes
Summarizing routes and configuring default static routes helps manage complex networks with multiple LANs and connections to the internet. This section provides examples and commands to configure summary and default routes.

## Summary
In this project, we learned:
- How routers find paths to remote networks.
- How to configure static routes using routing table principles.
- The concept of recursive lookup.
- Configuring summary and default static routes.

## Example Topology
Refer to the exhibit below, illustrating the network topology used throughout this project:

