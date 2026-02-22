*This project has been created as part of the 42 curriculum by enchevri.*

## Description

In this 42 school project, no coding is required. The goal is to learn **networking basics** using the *NetPractice* web tool.

This tool helps you understand how simple networks work by configuring **IPv4 addresses** and **subnet masks** for different hosts and routers. You must connect all devices while following the network rules given in each level.

## Instructions

### Requirements
- Python 3 installed
- Modern web browser (Firefox, Chrome, etc.)
- The NetPractice archive from the 42 intranet

### How to run the training interface

1. Download the NetPractice archive from the 42 intranet
2. Extract the files in a directory of your choice
3. Run the script:
   ```bash
   ./run.sh
   ```

### Using the interface

1. Enter your **42 login** on the main page
2. Choose **Training** tab for levels 1-10 in order
3. Or use **Evaluation** tab for random levels 7-10 (good for practice too!)
4. For each level, configure IPs/masks until objectives are met
5. Click **Check again** to validate

### Exporting configurations and submission

- For **each solved level**, click **Get my config** to download the file
- You need **10 config files total** (one per level)
- Place all 10 files at the **root** of your Git repository

## Resources

### Networking concepts studied

This project covers essential networking fundamentals including:

- **IPv4 Addressing**: Understanding IP address classes, address structure, and assignment methods
- **Subnet Masks**: CIDR notation, subnet calculations, determining network and broadcast addresses
- **Default Gateways**: Router configuration and routing between subnets
- **Routers and Switches**: Differences in functionality and network layer operations
- **Network Segmentation**: Dividing networks into subnets, calculating available hosts
- **IP Routing**: Direct and indirect routing, route determination based on routing tables

### Documentation and tutorials


- [Networking Fundamentals](https://www.youtube.com/playlist?list=PLIhvC56v63IKrRHh3gvZZBAGvsvOhwrRF): A full playlist of videos that helps me understand how a network works.
- [Subnet Cheat Sheet](https://www.aelius.com/njh/subnet_sheet.html): Quick reference for subnet calculations and IP addressing

### Use of AI

I used AI to help me reformulate and structure everything in this README while ensuring I fully understood all networking concepts.
