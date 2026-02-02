1. INTRODUCTION
1.1 Purpose

The purpose of this Software Requirements Specification (SRS) document is to clearly define the functional and non-functional requirements of the proposed Scalable Embedded Face Recognition Attendance System. This document serves as a reference for understanding system behavior, constraints, and expectations, and acts as a communication medium between developers, evaluators, and stakeholders involved in the project.

1.2 Target Audience

This SRS document is intended for individuals involved in the analysis, design, development, evaluation, and maintenance of the system. It is written to be understandable by readers with basic knowledge of software systems, including project developers, academic evaluators, system reviewers, and future maintainers who may extend or deploy the system in real-world environments.

1.3 Project Scope

The scope of this project is to design a scalable, backend-integrated, and embedded-ready attendance management system based on face recognition technology. The system focuses on automating attendance recording using facial embeddings while ensuring data integrity, reduced human intervention, and compatibility with existing camera infrastructure.

The project includes requirement specification, system design, and phased development of core modules such as face recognition, attendance processing, and backend integration. Implementation details such as advanced hardware deployment or large-scale institutional rollout are considered beyond the immediate scope but are supported by the proposed system architecture.

2. OVERALL DESCRIPTION
2.1 Product Perspective

The proposed Scalable Embedded Face Recognition Attendance System is designed as a standalone software solution that integrates automated face recognition with centralized attendance management. The system is intended to replace manual and basic digital attendance methods by providing a backend-integrated, reliable, and scalable alternative.

From a system perspective, the product functions as a distributed attendance management platform capable of operating with existing camera infrastructure and supporting future deployment on embedded or edge devices. The system is designed to interact with multiple components such as camera input devices, a centralized data store, and administrative interfaces. It follows a modular structure in which face capture, recognition, and attendance processing are logically separated to ensure maintainability and scalability.

The product is not dependent on any proprietary hardware and is designed to operate within standard computing environments. Its architecture allows integration with external systems or future extensions without requiring fundamental redesign, making it suitable for long-term institutional use.

2.2 Product Functions

The major functions of the proposed system are as follows:

Capture facial images using camera-enabled devices in real time.

Register and manage authorized user facial data within the system.

Perform face recognition using embedding-based matching techniques.

Automatically record attendance with associated timestamps and identification details.

Maintain centralized and secure storage of attendance records.

Prevent duplicate or invalid attendance entries within defined constraints.

Provide access to attendance data for monitoring and review purposes.

Support scalability by allowing multiple input devices and users.

These functions collectively enable automated, accurate, and efficient attendance management while minimizing manual intervention.

2.3 Operating Environment

The system is designed to operate in a standard computing and embedded-friendly environment. The primary operating environment includes:

Operating Systems: Windows or Linux-based platforms

Hardware: Camera-enabled systems or embedded devices capable of image capture

Software Platform: Python-based execution environment

Database Environment: Relational database system for structured data storage

Network Environment: Local area network or internet-enabled environment for centralized data access

The system is designed to be hardware-agnostic and can operate with existing system cameras without requiring specialized equipment.

2.4 Product Design

The system follows a modular and layered design approach to ensure clarity, maintainability, and scalability. The design divides the system into logically independent components, each responsible for a specific function within the attendance workflow.

At a high level, the system consists of the following modules:

Face Capture Module: Responsible for acquiring facial images from camera devices.

Face Recognition Module: Responsible for identifying individuals using facial features.

Attendance Management Module: Responsible for validating and recording attendance events.

Data Management Module: Responsible for secure storage and retrieval of attendance records.

Monitoring and Interface Module: Responsible for providing access to attendance information.

Each module interacts through defined interfaces, ensuring minimal dependency and enabling future enhancements such as embedded deployment, analytics integration, or system scaling without major structural changes.