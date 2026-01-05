# Sentinel Privacy Middleware

A lightweight FastAPI service that detects and anonymizes sensitive user data before sending prompts to Large Language Models (LLMs), and safely restores them in the final response.

## Key Features
- PII detection using Microsoft Presidio
- Anonymization of pii
- Context-preserving masking
- REST API-based design for easy integration

## Tech Stack
- Python
- FastAPI
- Microsoft Presidio

## API Endpoints
- POST /anonymize
- POST /deanonymize

## Use Case
Designed as a privacy layer for AI applications in domains like banking, healthcare, and customer support.
