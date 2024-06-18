---
layout: about
title: home
permalink: /
subtitle: "[ io = data input/output ]"
# -----------------------------------------------------------------------------
# Profile Sidebar
# -----------------------------------------------------------------------------
profile:
  align: right
  name: Anthony Kougkas
  image: avatar_profile.png
  image_circular: true # crops the image to make it circular
  more_info: >
      <div style="text-align: center;"><strong> Anthony Kougkas</strong></div>
      <div style="text-align: center;font-size: 0.75em;">
      <p> Data Management and Storage </p> 
      <p> Distributed and Parallel Systems</p>
      <p> Input/Output for HPC & AI/ML</p>
      <br><br>
      <p> Assistant Research Professor</p>
      <p><i class="fa fa-university" aria-hidden="true"></i> Illinois Tech</p>
      <p><i class="fas fa-map-marker-alt"></i> Chicago, IL</p>
      <p><i class="fas fa-envelope"></i> <a href="mailto:a.kougkas@gmail.com">Email</a></p>
      <p><i class="fas fa-graduation-cap"></i> <a href="https://scholar.google.com/citations?user=hiNO0EEAAAAJ&hl=en">Google Scholar</a></p>
      <p><i class="fab fa-github"></i> <a href="https://github.com/grc-iit">Github</a></p>
      <p><i class="fab fa-orcid"></i> <a href="https://orcid.org/0000-0003-3943-663X">OrcID</a></p>
      <p><i class="fab fa-linkedin"></i> <a href="https://www.linkedin.com/in/anthonykougkas/">LinkedIn</a></p>
      </div>

# -----------------------------------------------------------------------------
# Featured Content
# -----------------------------------------------------------------------------
news: false # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---

### introduction

I am an Assistant Research Professor in computer science at [Illinois Tech](https://www.iit.edu/directory/people/antonios-kougkas), where I serve as the Associate Director of the [Gnosis Research Center](https://grc.iit.edu). My work at Illinois Tech and as a Guest Research Faculty at [Argonne National Laboratory](https://www.anl.gov/mcs) involves developing cutting-edge data management and storage solutions. With a strong focus on High-Performance Computing (HPC) and Artificial Intelligence (AI), I lead innovative projects and guide the next generation of computer scientists.

### research interests

**data management and storage systems**: Exploring multi-tiered storage architectures and distributed storage solutions to efficiently manage and replicate large datasets, employing advanced compression techniques.

**i/o optimization**: Developing asynchronous input/output (I/O) techniques, multi-tiered buffering systems, data prefetching algorithms, and I/O scheduling strategies to enhance throughput and reduce latency in HPC environments.

**distributed scientific workflows**: Optimizing workflow execution through dataflow semantics, context-aware active storage, and hierarchical data streaming engines for high-throughput scientific applications.

**AI and machine learning integration**: Advancing data management for AI/ML frameworks (e.g., TensorFlow, PyTorch) with exascale-ready storage solutions and accelerating AI-driven scientific discovery.

**i/o bottlenecks**: Implementing automated detection and optimization techniques to address bottlenecks in HPC and deep learning workflows, enabling efficient resource utilization and improved performance.

**task-based i/o**: Proposing novel task-driven frameworks and data labelling techniques to optimize performance and resource utilization in distributed computing environments.

**data prefetching, compression, compression**: Developing hierarchical prefetching techniques for scientific workflows involves optimizing data prefetching to minimize latency, enhancing compression to reduce data size, and coordinating buffer usage to prevent I/O interference and ensure efficient data movement.

### projects

<span style="vertical-align:middle;"><img src="/assets/img/nsf_logo.png" height="30px" /></span> <strong>hermes</strong>: A state-of-the-art I/O buffering platform for HPC environments, utilizing HDF5 data structures to optimize data placement across memory and storage hierarchies, including NVRAM and SSDs. <i class="fas fa-dollar-sign"> 2.87M</i>

<span style="vertical-align:middle;"><img src="/assets/img/nsf_logo.png" height="30px" /></span> <strong>iris</strong>: A unified data access framework merging HPC and Analytics and AI, enabling integrated data and metadata management, and intelligent data placement. <i class="fas fa-dollar-sign"> 515K</i>

<span style="vertical-align:middle;"><img src="/assets/img/nsf_logo.png" height="30px" /></span> <strong>chronolog</strong>: A high-performance, distributed log storage system that manages activity and log workloads using physical time for event ordering, reducing contention, and enabling elastic scaling across storage tiers. Supports plugins, SQL-like engines, and TensorFlow. <i class="fas fa-dollar-sign"> 2.67M</i>

<span style="vertical-align:middle;"><img src="/assets/img/doe_logo.png" height="25px" /></span> <strong>coeus</strong>: A framework that accelerates scientific insights through enriched metadata management, optimizing queries by leveraging AI/ML to balance computation and storage, and enhancing query performance with tiered data placement and staging. <i class="fas fa-dollar-sign"> 750K</i>

<span style="vertical-align:middle;"><img src="/assets/img/doe_logo.png" height="25px" /></span> <strong>dtio</strong>: A task-driven I/O framework for HPC, AI, and Big Data, offering scalable, distributed I/O optimization, enhanced data movement, and improved fault tolerance. <i class="fas fa-dollar-sign"> 750K</i>

<span style="vertical-align:middle;"><img src="/assets/img/nsf_logo.png" height="30px" /></span> <strong>labios</strong>: An innovative, energy-efficient label-based I/O system for multi-tiered HPC environments, providing solutions such as multi-tenancy, resource scheduling, and seamless integration with diverse storage pools. <i class="fas fa-dollar-sign"> 600K</i>

<span style="vertical-align:middle;"><img src="/assets/img/doe_logo.png" height="25px" /></span> <strong>deepio</strong>: A scalable I/O runtime for AI workflows, optimizing DNN model updates between training and inference tasks. It balances inference quality, training duration, and throughput using novel caching, versioning, and asynchronous data transfer techniques. <i class="fas fa-dollar-sign"> 135K</i>

<span style="vertical-align:middle;"><img src="/assets/img/doe_logo.png" height="25px" /></span> <strong>deepio</strong>: A scalable I/O runtime for AI workflows, optimizing DNN model updates between training and inference tasks. It balances inference quality, training duration, and throughput using novel caching, versioning, and asynchronous data transfer techniques. <i class="fas fa-dollar-sign"> 135K</i>

### key contributions

**publications**: Over 55 peer-reviewed publications, contributing significantly to the fields of HPC, data management, and storage systems

**patents**: Holder of a US patent for the "Label-Based Data Representation I/O Process and System" (US 2021/0374152 A1)

**funding**: Successfully secured over $17.63M in research funding, with $8.55M in active projects, demonstrating a strong track record in acquiring competitive grants

**educational**: Mentored 36 graduate students (8 PhD + 28 Masters), 8 undergraduates, and 3 full-time engineers/staff, fostering the next generation of researchers and professionals

**awards**: Recipient of several prestigious awards, including the Best Paper Award at CCGrid'21 and the Karsten Schwan Best Paper Award at HPDC'19, recognizing excellence in research and contribution to the field

**software**: Developed and deployed critical software systems such as Hermes, LABIOS, ChronoLog, and IRIS, addressing key challenges in data management and I/O optimization for HPC environments.

## mentoring and teaching

- **Mentoring**: Current graduate students (8 PhD + 2 Masters), 1 undergraduate student, and 3 full-time engineers/staff
- **Teaching Philosophy**: Fostering an active and engaging learning environment emphasizing hands-on, lab-focused experiences and active mentoring, bridging theoretical knowledge with practical application


## contact  
For collaboration opportunities, please reach out via [Email](mailto:a.kougkas@gmail.com) or connect on [LinkedIn](https://www.linkedin.com/in/anthonykougkas/).