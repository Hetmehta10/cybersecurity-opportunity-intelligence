# Cybersecurity Opportunity Intelligence

A frontend-first cybersecurity opportunity discovery platform for students, freshers, and early-career professionals in India.

## What is included

- Searchable internship and entry-level opportunity directory
- Filters for role, location, work mode, experience, and focus area
- Opportunity detail views with explainable match scoring
- Save and application tracking using browser persistence for the demo
- Profile, dashboard, alerts, and admin moderation demo experiences
- Clear demo/seed labeling for sample opportunity data

## Project structure

- artifacts/cyber-opportunities — React/Vite frontend product
- artifacts/api-server — existing API server scaffold
- lib — shared workspace packages and API/database contracts

## Run locally

This repository uses pnpm workspaces. Install dependencies, then start the opportunity web artifact:

    pnpm install
    pnpm --filter @workspace/cyber-opportunities run dev

The current MVP intentionally uses browser-local persistence and labeled seed data. Backend persistence, authentication, verified ingestion, and production moderation are planned follow-up capabilities.
