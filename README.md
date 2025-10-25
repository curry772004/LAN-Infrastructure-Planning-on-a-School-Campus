# School Campus LAN Infrastructure Planning

## Context

This repository contains the project materials developed for the **Structured Cabling** course unit, part of the Computer Engineering degree at the **Coimbra Institute of Engineering (ISEC)**, during the 2024/2025 academic year.

## Project Goal

The primary objective was to plan and design a modern, robust, secure, and scalable Local Area Network (LAN) infrastructure for a school campus comprising four buildings, following best practices and the international standard **ISO/IEC 11801**.

## Key Aspects Covered

* **Network Topology:** Definition of a hierarchical star topology featuring a Main Distribution Frame (MDF/CD), Building Distribution Frames (BDFs), and Floor Distribution Frames (IDFs).
* **Cabling Selection:**
    * **Backbone (Campus and Vertical):** Multimode Fiber Optic **OM4** to ensure high bandwidth and immunity to interference.
    * **Horizontal:** Twisted-pair cable **Category 6A (Cat6A)** to support future applications up to 10 Gbps at workstations.
* **Network Coverage:** Planning the distribution of Telecommunications Outlets (TOs) and **Wi-Fi** coverage across all relevant areas (classrooms, labs, library, administrative areas, etc.).
* **Segmentation and Security:** Planning the use of **VLANs** to segment traffic for different user groups (students, staff, visitors) and services.
* **Labelling:** Definition of an identification and labelling scheme for cables and equipment based on the **ANSI/TIA-606** standard.
* **Equipment Selection:** Preliminary identification of the type of active equipment (Switches, Routers, Access Points) required for each network layer.

## Tools Used

* **Cisco Packet Tracer:** Utilised for simulating the logical network topology and visualising the physical equipment placement on floor plans.

## Repository Contents

* `/Structured Cabling -  Group Project.pdf`: PDF document containing the detailed project report, including requirements, analysis, planning, diagrams, and budget. 
* `/Equipments.pkt`: Cisco Packet Tracer file showing the **strategic physical placement** of network equipment on the school's floor plan. **(Note: To view the equipment placement, open this file in Cisco Packet Tracer, switch to "Physical" mode, and navigate to either "Piso 0" or "Piso 1" within the physical workspace.)**
* `/Logical_Topology.pkt`: Cisco Packet Tracer file detailing the **logical network topology**, showing the interconnections between devices.

## Authors

* Henrique Dias Neves Simões Ferreira
* João Pedro Vila Pomar
* José Pedro Leal Neto
* Rodolfo Miguel de Sousa Belchior Brás Oliveira

