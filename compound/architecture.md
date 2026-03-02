# Compound Engineering Architecture – ClaimLens AI

## Overview

ClaimLens AI follows Compound Engineering principles by separating
the system into modular, composable components.

## System Modules

### 1. Frontend (Lovable)
- Handles UI interactions
- Collects PDF uploads
- Displays analysis dashboard
- Sends structured payload to backend webhook

### 2. Backend Orchestration (n8n)
- Webhook trigger
- PDF parsing
- LLM-based extraction
- Claim eligibility calculation
- Structured JSON response

### 3. Compound Engineering Layer

The system follows compound engineering principles:

- Modular workflows
- Decoupled frontend and backend
- Reusable automation blocks
- Scalable orchestration logic
- Clear separation of concerns

## Data Flow

User Upload → Lovable UI → n8n Webhook → PDF Parsing →
Policy Extraction → Claim Calculation → JSON Response →
Dashboard Rendering

## Why Compound Engineering?

This architecture enables:

- Independent evolution of modules
- Faster iteration
- Workflow composability
- Backend portability
- AI-driven extensibility

