# DNS Secure Orchestrator

This repository contains the GitHub Actions workflow for deploying the DNS Secure application, which includes:

- Frontend (React + TypeScript + Vite)
- Backend (FastAPI + Python)
- Data Ingestion (API endpoints for DNS event ingestion)

## Deployment

The deployment workflow is defined in `.github/workflows/deploy.yml` and can be triggered manually via GitHub Actions or automatically on push to the main branch.

## Components

- **Frontend**: Located in the `dns-secure-frontend` repository
- **Backend**: Located in the `dns-secure-backend` repository
- **Data Ingestion**: Part of the backend API with endpoints at `/api/ingest/event` and `/api/ingest/batch`
