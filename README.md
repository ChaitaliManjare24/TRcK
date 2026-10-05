# AI Personal Assistant Automation | n8n

## Overview

An AI-powered personal assistant workflow built with **n8n** that integrates Telegram, AI models, Google services, and automated workflows to manage conversations, tasks, and financial transactions.

The system uses specialized AI agents for different functions and routes user requests to the appropriate workflow.

## Key Features

- AI-powered conversational assistant through Telegram
- Intelligent routing of user requests to specialized workflows
- Task management through natural language
- Financial transaction management and tracking
- File and document analysis
- AI-powered data analysis
- JavaScript-based data processing and transformation
- Automated email and Telegram notifications
- Memory-enabled AI interactions
- Google Sheets integration for structured data management

## Workflow Architecture

### 1. Chat Assistant

The Chat Assistant handles general user requests and uses AI to understand and process messages.

**Workflow:**
Telegram → Request Routing → AI Agent → Data Processing → Output

The workflow includes:
- OpenAI Chat Model
- Simple Memory
- Tool-based AI interactions
- File retrieval and analysis
- JavaScript data processing
- Google Sheets integration
- Telegram responses

### 2. Task Management

The Task Agent handles task-related requests using natural language.

Users can interact with the assistant to manage tasks through Telegram.

**Workflow includes:**
- AI-powered task understanding
- Task creation
- Task updates
- Task deletion
- Task-related data management
- Telegram notifications

### 3. Finance Management

The Finance Agent handles financial transaction-related requests.

**Workflow includes:**
- AI-powered financial request processing
- Transaction-related data handling
- Transaction recording
- Transaction deletion
- Financial data analysis
- Telegram notifications

## Technologies and Tools

- n8n
- AI Agents
- OpenAI Chat Model
- Google Gemini
- Telegram Bot
- Google Sheets
- JavaScript
- APIs
- Workflow Automation
- AI-powered Data Analysis
- Natural Language Processing

## Workflow

```text
User Message
     ↓
Telegram
     ↓
Request Routing
     ↓
AI Agent
     ↓
┌──────────────┬──────────────┬──────────────┐
│ Chat Assistant│ Task Agent   │ Finance Agent│
└──────────────┴──────────────┴──────────────┘
     ↓
Data Processing / AI Analysis
     ↓
Google Sheets / Other Tools
     ↓
Telegram Response
