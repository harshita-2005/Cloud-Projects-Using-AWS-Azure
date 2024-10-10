# Azure Load Balancer with Application Gateway

This project demonstrates how to create an Azure Load Balancer using an Application Gateway that routes traffic to multiple virtual machines. The setup includes four virtual machines that serve different types of content, showcasing the load balancing capabilities of Azure.

## Purpose

The primary purpose of this project is to illustrate the implementation of a Layer 7 Application Gateway in Azure, which efficiently manages and distributes incoming HTTP and HTTPS traffic across multiple backend virtual machines. This setup is ideal for ensuring high availability and reliability of web applications by balancing the load among several instances.

## Features

- **Virtual Network**: Created a virtual network (vnet1) to host the Application Gateway and virtual machines.
- **Application Gateway**: Configured an Application Gateway that routes traffic to multiple backend servers based on HTTP requests.
- **Backend Pool**: Set up a backend pool containing four virtual machines named:
  - movie
  - series
  - song
  - video
- **Custom HTML Content**: Each virtual machine serves custom content, indicating which VM is handling the request.

## Usage

- Access the Application Gateway using the frontend IP address.
- Refresh the page to observe load balancing in action as different virtual machines serve the content.

## Tech Stack

- **Azure**: Used for cloud infrastructure and services.
- **Virtual Machines**: Deployed to serve content.
- **Application Gateway**: Manages and balances incoming traffic.
