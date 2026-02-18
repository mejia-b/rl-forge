# RL Forge

A lightweight backend platform for managing reinforcement learning training runs — built for autonomy and robotics teams.

## What it does

Training RL agents involves a lot of moving parts: launching jobs, tracking metrics across experiments, saving checkpoints, and comparing runs. RL Forge provides a clean backend API and dashboard to manage all of that in one place.

Inspired by tools like MLflow and Ray Train, but designed to be simple enough to self-host and extend.

## Features (in progress)

- REST API for creating and managing training runs
- Job queue for dispatching and cancelling training jobs
- Metrics collection and experiment comparison
- Dashboard for visualizing training curves and telemetry

## Tech stack

- **Backend:** Python, FastAPI
- **Job orchestration:** Custom async worker queue
- **Frontend:** React
- **Storage:** PostgreSQL (planned)

## Project status

Active development. Built as a learning project to explore RL infrastructure patterns used in production autonomy systems.
