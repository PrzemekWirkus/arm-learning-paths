---
title: Scaling Snort3 - use multithreading for improved performance

draft: true
cascade:
    draft: true

minutes_to_complete: 45

who_is_this_for: This blog is for engineers familiar with Snort who want to enhance its performance by leveraging the benefits of multithreading.

learning_objectives: 
    - Install Snort with all of its dependencies.
    - Configure Snort Lua files to enable multithreading.
    - Use multithreading to process capture files and measure performance.

prerequisites:
    - An Arm-based instance from a cloud provider or an Arm server running Ubuntu 20.04 or 22.04.
    - A basic understanding of Snort's operation and configuration.
    

author_primary: Preema Merlin Dsouza

### Tags
skilllevels: Introductory
subjects: Libraries
armips:
    - Neoverse
tools_software_languages:
    - AWS EC2
    - Snort3
    - Bash
    - GCC
operatingsystems:
    - Linux

### FIXED, DO NOT MODIFY
# ================================================================================
weight: 1                       # _index.md always has weight of 1 to order correctly
layout: "learningpathall"       # All files under learning paths have this same wrapper
learning_path_main_page: "yes"  # This should be surfaced when looking for related content. Only set for _index.md of learning path content.
---
