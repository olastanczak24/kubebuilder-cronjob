# kubebuilder-cronjob

## Overview

This repository contains a Kubebuilder project for creating a CronJob controller in Kubernetes. It demonstrates how to manage CronJobs using custom resources and controllers.

## Repository Structure

- `api/`: Contains API definitions for the CronJob.
- `config/`: Kustomize configurations for Kubernetes resources.
- `controllers/`: Controller logic for managing CronJobs.
- `Dockerfile`: Dockerfile for building the operator image.
- `Makefile`: Makefile for common tasks.

## Getting Started

### Prerequisites

- Kubebuilder installed
- Docker for building images
- Kubernetes cluster

### Build and Run Locally

1. Build the project:

   ```bash
   make build
