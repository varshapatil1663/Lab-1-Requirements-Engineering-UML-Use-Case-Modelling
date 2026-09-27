# Lab 1 – Requirements Engineering & UML Use-Case Modelling

## Problem Statement #27
### Warehouse Inventory & Pallet Location Tracker

## Overview

This project focuses on requirements engineering and UML use-case modelling for a Warehouse Inventory & Pallet Location Tracker.

The system tracks 3D shelf pallet positions, enforces maximum rack weight limits, and records stock movements using barcode/RFID scanning.

## Actors

- Warehouse Operator
- Logistics Supervisor
- Barcode/RFID Scanner

## Use Cases

- Scan Pallet
- Assign Pallet Location
- Validate Rack Capacity
- Locate Pallet
- Record Stock Movement
- View Inventory & Movement Records
- Authenticate User
- Handle Invalid Scan

## Requirements

The system contains:

- 5 Functional Requirements (FR-001 to FR-005)
- 2 Non-Functional Requirements (NFR-001 to NFR-002)

The requirements cover pallet placement validation, 3D shelf location assignment, pallet lookup, stock movement recording, inventory monitoring, performance, and access control.

## UML Relationships

- **Assign Pallet Location** <<include>> **Validate Rack Capacity**
- **Handle Invalid Scan** <<extend>> **Record Stock Movement**

## Deliverables

### 1. Requirements Table
Contains 5 Functional Requirements and 2 Non-Functional Requirements.

### 2. UML Use-Case Diagram
Shows all actors, use cases, actor associations, and include/extend relationships.

### 3. Use-Case Flow Specification
Describes the preconditions, postconditions, main success scenario, and alternate flow for the system.

## Tools Used

- Draw.io – UML Use-Case Diagram
- Microsoft Word / Excel – Requirements and Use-Case Documentation
- GitHub – Version Control and Submission

## Repository Contents

| File | Description |
|---|---|
| Requirements_Table.xlsx | Functional and Non-Functional Requirements |
| Use_Case_Diagram.pdf | UML Use-Case Diagram |
| Use_Case_Flow_Specification.pdf | Use-Case Flow Specification |

## Lab Information

**Lab:** Lab 1 – Requirements Engineering & UML Use-Case Modelling  
**Problem Statement:** #27  
**Domain:** Smart Cities, Transport & Logistics  
**System:** Warehouse Inventory & Pallet Location Tracker
