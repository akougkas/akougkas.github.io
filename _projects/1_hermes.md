---
layout: page
title: Hermes 
description: Heterogeneous-Aware Multi-Tiered Distributed I/O Buffering System
img: assets/img/hermes_logo.png
importance: 1
category: NSF
related_publications: true
---

Hermes aims to extend the HDF library to support intelligent I/O buffering for deep memory and storage hierarchy systems (DMSH). It addresses the I/O bottleneck in modern HPC applications by providing efficient and transparent data movement through the hierarchy, employing new buffering algorithms, and enhancing HDF5 technology.

## Background
Hermes is designed to tackle the complexity of data placement and movement in multi-tiered environments, which is often left to application developers. It provides a middleware library that automatically manages buffering in heterogeneous storage environments, ensuring efficient data access and movement.

## Key Features
- **Vertical and Horizontal Buffering:** Access data within different levels locally and spread/gather data across remote compute nodes.
- **Selective and Dynamic Buffering:** Utilize memory layers like NVMe selectively for certain data, and change buffering schema dynamically based on traffic.
- **Adaptive Buffering:** Employ reinforcement learning to adapt prefetching algorithms and cache replacement policies based on application access patterns.

## Architecture
Hermes features a hierarchical, dynamic, modular, and flexible architecture. It includes a middleware library written in C++, supporting POSIX, HDF5, and MPI-IO, with mechanisms for passing user operations and providing efficient, distributed data management.

## Contributions and Impact
Hermes enhances the HDF5 library, supporting scientific discovery by enabling effective data management in DMSHs. It abstracts data movement complexities and maximizes resource utilization and performance, making it suitable for a wide range of scientific and big data applications.

## Future Work
Hermes' design implications and objectives include maximizing productivity, increasing resource utilization, abstracting data movement, and supporting a wide range of scientific applications and domains.

## Contact
For more details, visit the [Gnosis Research Center Hermes project page](https://grc.iit.edu/research/projects/hermes).