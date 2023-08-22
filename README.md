# CreateGCPRunner
Create a self-hosted runner on GCP and register it automatically

This repository provides a module for creating a VM on GCP, which serves as a self-hosted runner for executing GitHub workflows.  
There are existing repositories with similar objectives, one notable example is: https://github.com/terraform-google-modules/terraform-google-github-actions-runners. The primary distinction between this repo and the aforementioned one is the creation of a single machine for the runner, as opposed to an entire MIG. The main aim of this repository is to maintain a single runner for executing workflows specifically within the context of Continuous Benchmarking (a more detailed description will be provided later).




