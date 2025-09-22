# AI Analyst: The Autonomous Diligence Engine

[![Hackathon](https://img.shields.io/badge/Hackathon-Google%20Gen%20AI%20Exchange-blue)](https://hack2skill.com/) [![Platform](https://img.shields.io/badge/Platform-Google%20Cloud-orange)](https://cloud.google.com/)

A fully autonomous platform that ingests, analyzes, interviews, and ranks startups for investors, powered by a multi-agent AI system on Google Cloud.

## The Problem

Early-stage investment is broken. Investors are inundated with pitch decks, while founders struggle to get noticed. The manual process of due diligence is slow, inconsistent, prone to bias, and fundamentally unscalable. This creates a massive bottleneck, preventing promising startups from connecting with the right capital.

## Our Vision: A Fully Autonomous Pipeline

We are building a solution that represents a fundamental paradigm shift—from analyst *tools* to a fully **autonomous analyst**. Our platform manages the entire startup evaluation lifecycle, from the moment a founder submits their application to the delivery of a personalized investment report to an investor, with no manual intervention required.

For a complete overview of our vision and the opportunity, please see our **[Project Presentation](./GenAI-Exchange-Hackathon-Prototype.pptx)**.

## Key Features

*   **🤖 Autonomous Multi-Agent Synthesis:** Ingests multi-modal founder data (PDFs, videos, audio) and validates it against a vast array of public and private data sources.
*   **🎤 AI-Powered Founder Dialogue:** A revolutionary AI Voice Agent proactively engages founders in a Q&A session to clarify ambiguities and enrich the data—a task previously exclusive to humans.
*   **📊 Dynamic, Multi-Stage Memo Generation:** Creates an evolving diligence trail, from an initial automated memo to a refined memo enriched with insights from the founder dialogue.
*   **🎛️ Personalized Investor Ranking Engine:** Allows investors to apply their unique investment thesis via a simple weighting system to score and rank startups according to their personal preferences.
*   **🔄 Closed-Loop Learning System:** Every investor interaction is fed back into the platform, continuously training the AI agents to become smarter and more accurate over time.

## How It Works: The Architecture

Our system operates on a three-stage, fully automated workflow orchestrated by a team of specialized AI agents.

1.  **Stage 1: Synthesis & First Memo:** Ingests and processes founder data, enriches it with external research, and generates a comprehensive "First Investment Memo".
2.  **Stage 2: AI Dialogue & Refinement:** An AI Voice Agent uses the First Memo as context to conduct a Q&A session with the founder, producing an enriched "Second Investment Memo".
3.  **Stage 3: Personalization & Reporting:** The refined memo is scored and ranked based on an investor's personal weightages, delivering a final, actionable report.

For a detailed technical breakdown of the multi-agent system and data flows, please see our **[Architecture Diagrams](./Complete-architecture.png)**.

## Technology Stack

This project is built entirely on the Google Cloud Platform, leveraging its cutting-edge AI and data services.

*   **AI & Machine Learning:** Vertex AI, Gemini Pro, Cloud Vision API, Speech-to-Text, Dialogflow
*   **Backend & Orchestration:** Google Cloud Functions, Cloud Run
*   **Database:** BigQuery, Firebase Firestore
*   **Frontend:** Firebase Hosting

## Hackathon Prototype

The current prototype in this repository demonstrates the core of this vision by implementing:
*   **Stage 1:** A working pipeline that ingests a pitch deck, synthesizes its data with public web searches, and produces a structured "First Memo".
*   **Stage 3:** A functional front-end interface with a dynamic weighting engine that allows a user to generate a personalized and ranked final report from the memo.

The AI Voice Agent for Stage 2 is a core part of our future vision and is detailed in our architecture diagrams.

---
