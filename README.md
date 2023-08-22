# CreateGCPRunner
Create a self-hosted runner on GCP and register it automatically

This repository contains a module for creating a VM on GCP which acts as a self-hosted runner for running GitHub workflows.
There are already some repositories for achieving this goal, is particular: https://github.com/terraform-google-modules/terraform-google-github-actions-runners.
The main differnce between this repo and the mentioned repository is creation of a single machine for the runner instead of the whole MIG.
The main purpose of this repo is to have a single runner for running workflow within the scope of Continuous Benchmarking (description will come later).




