# Flisk Multi-Service Application

## Overview

This project contains a multi-service application
orchestrated using Flisk.

Services:
- Python Vote Service
- Node.js Result Service
- Python Worker Service
- Redis
- PostgreSQL

## Prerequisites

- Git
- Node.js
- Docker
- Docker Compose
- Tilt

## Installation

Clone the repository:

    git clone YOUR_FORK_URL

Navigate into the project:

    cd flisk-task-starter

## Run the application

Import Docker Compose configuration:

    npx @flisk-sh/flisk import .

Start all services:

    npx @flisk-sh/flisk up

Get application URLs:

    npx @flisk-sh/flisk networks

## Application Endpoints

- Voting: /api/vote
- Results: /api/result

## What was hard

1. Understanding how Docker Compose
   configurations map to Flisk services.

2. Identifying unsupported Compose
   configurations during import.

3. Configuring service dependencies
   and application networking.

4. Verifying that all services start
   and communicate correctly.

## Stopping the application

Refer to the Flisk CLI help for the
supported shutdown command.