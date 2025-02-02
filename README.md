# terraform-k8s-ansible

## F1 Application Deployment

This repository contains the infrastructure and deployment configuration for an F1 application using Terraform, Kubernetes, and Ansible on DigitalOcean.

## Architecture Overview

The application is deployed on a DigitalOcean Kubernetes cluster with the following components:
- Kubernetes cluster with multiple worker nodes
- Load balancer for traffic distribution
- VPC for network isolation
- Container-based deployment

## Prerequisites

- DigitalOcean account and API token
- Terraform (>= 1.0.0)
- kubectl
- Ansible
- Docker (for local development)

## Repository Structure
