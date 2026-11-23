# Aetherflow AI CRM Intelligence & Automation Platform

An AI-powered CRM intelligence prototype built using **n8n, PostgreSQL, Google Gemini, JavaScript, and Docker**.

## Project Overview

Aetherflow enables users to retrieve customer information and analyze CRM records by asking natural-language questions.

The system uses AI to classify questions, generate controlled SQL queries, retrieve database records, and present understandable answers.

## Key Features

- Customer profile retrieval
- Subscription and payment lookups
- Support ticket analysis
- Customer counts and grouped analytics
- AI-powered question classification
- Allowlisted SQL generation with parameterized filters
- Fallback handling for unsupported questions

## Technology Stack

- n8n — Workflow automation
- PostgreSQL — CRM database
- Google Gemini — AI processing
- JavaScript — Workflow logic
- Docker Desktop — Local container environment
- pgAdmin — Database administration

## Dataset

The project was tested with **5 million synthetic CRM records**, including:

- 1 million customers
- 1 million subscriptions
- 1 million payments
- 2 million support tickets

## Project Status

Working local portfolio prototype. Not production-ready. Authentication, role-based access control, and policy retrieval are not implemented.

## Demonstration

See the `screenshots` folder for workflow screenshots and CRM query examples.
