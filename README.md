![CI](https://github.com/meerabdraz5412/devops-intern-final/actions/workflows/ci.yml/badge.svg)
# DevOps Intern Final Project
**Name:** [Meerab Draz]  
**Date:** 2026-01-07  

## Project Description
This repository demonstrates basic DevOps skills including Linux scripting, Docker containerization, CI/CD with GitHub Actions, Nomad job deployment, and monitoring with Grafana Loki.
## Linux & Scripting Basics

A shell script is included under the scripts/ directory.

Script: scripts/sysinfo.sh  
This script prints:
- Current logged-in user
- Current system date
- Disk usage information

Run it using:
bash scripts/sysinfo.sh
## CI/CD with GitHub Actions

A GitHub Actions workflow is configured at:
.github/workflows/ci.yml

The pipeline automatically runs on every push and executes:
python hello.py

This ensures basic CI validation of the project.

## Docker Basics

Build the Docker image:
docker build -t hello-devops .

Run the container:
docker run hello-devops
## Nomad Deployment

A Nomad job file is provided at:
nomad/hello.nomad

Run the job using:
nomad job run nomad/hello.nomad
## Monitoring with Grafana Loki

Grafana Loki was configured locally using Docker.  
Setup steps and log viewing commands are documented in:

monitoring/loki_setup.txt
## Repository Structure

This repository contains Docker, CI/CD, Linux scripting, Nomad deployment, and monitoring configurations as part of the DevOps internship final project.
