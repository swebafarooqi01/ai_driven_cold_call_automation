# AI Outbound Calling System

An automated outbound lead-calling platform built with n8n, Vapi AI, Google Sheets, and REST APIs.

## Overview

This system automatically monitors new leads, validates phone numbers, checks the lead's local timezone, initiates AI-powered outbound calls, retrieves call results, and updates the CRM automatically.

The goal is to automate first-touch lead engagement while ensuring calls are made during business hours.

## Features

* Automated lead ingestion from Google Sheets
* Phone number sanitization and validation
* Timezone-aware calling logic
* AI-powered voice conversations using Vapi
* Automated call status tracking
* Transcript collection
* Call recording retrieval
* CRM/Google Sheets updates
* Retry and polling mechanism

## Workflow

1. New lead enters Google Sheets
2. Workflow validates and cleans phone number
3. System determines lead timezone
4. Calls only during business hours
5. AI assistant initiates outbound call
6. Workflow polls call status
7. Retrieves:

   * Transcript
   * Recording URL
   * Call Summary
   * Call Status
8. Updates CRM automatically

## Tech Stack

* n8n
* Vapi AI
* REST APIs
* Google Sheets API
* JavaScript
* OAuth Authentication

## Architecture

Lead Source → Validation → Timezone Engine → AI Call Engine → Call Monitoring → CRM Update

## Future Improvements

* IVR navigation using DTMF
* Multi-agent routing
* CRM integrations (HubSpot, Salesforce)
* Sentiment analysis
* Lead qualification scoring
* Human handoff detection
* Automated follow-up campaigns

## Skills Demonstrated

* Workflow Automation
* API Integration
* Backend Logic Design
* Event-Driven Systems
* Data Processing
* AI Agent Orchestration
* Business Process Automation
