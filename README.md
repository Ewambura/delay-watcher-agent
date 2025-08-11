# delay-watcher-agent
An AI agent that detects shipment delays from supplier emails and drafts follow-up actions

## Problem Statement
Global supply chains lose billions each year due to late shipments, yet most delay notifications are buried in unstructured emails. Operations teams waste hours manually reading supplier messages, identifying delays, and chasing updates.

## Solution Overview
**Delay Watcher Agent** is an AI-powered assistant that:
- Reads supplier emails.
- Detects shipment delays with high accuracy.
- Drafts polite follow-up messages to suppliers.
- Logs cases into Google Sheets for tracking.

By automating delay detection and supplier follow-ups, the agent helps businesses reduce operational inefficiencies and keep shipments on track.

## Current Status
**Phase 0:** Project scaffold and setup complete. Moving to Phase 1 (Data & Baseline Detector).

## Planned Features
- Email ingestion and parsing.
- Delay classification (rule + AI hybrid).
- Automated follow-up email drafting.
- Google Sheets logging.
- Streamlit dashboard for testing.

## Tech Stack
- **Python**
- **LangChain** – for connecting the AI model with tools.
- **Chroma** – vector database for storing email context.
- **OpenAI / Ollama** – AI models for text understanding.
- **Gmail API** – for reading and sending emails.
- **Google Sheets API** – for logging delay cases.
- **Streamlit** – for creating a simple web demo.

---
*This project is part of a learning journey in AI agent development, with the aim of building an industry-relevant solution and showcasing it for further opportunities.*

