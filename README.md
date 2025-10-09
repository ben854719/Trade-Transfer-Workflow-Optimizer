## Trade Transfer Workflow Optimizer

## Objective

This application uses an AI powered algorithm to analyze client stock portfolios with high precision, leveraging Pandas for data modeling and cleaning, and securing sensitive financial data through RS256 asymmetric encryption. Users can instantly access their portfolio by scanning a QR code from their TV or their computer, while an Avatar driven Agentic AI assistant provides personalized, human-like guidance. Key performance metrics include ≥95% portfolio analysis accuracy, <2 – second data latency, 100% encryption compliance, 80% user engagement with the avatar, and 98% cross-device QR scan success—delivering a secure, intelligent, and engaging portfolio experience.

## Video of the project:

## Features:

## AI-Powered Stock Portfolio Analysis:

- Delivers high-precision insights into asset allocation, sector exposure, and performance trends using advanced algorithms.

## Data Cleaning & Modeling with Pandas:

- Ensures reliable analysis by preprocessing and structuring raw portfolio data for consistency and clarity.

##  RS256 Asymmetric Encryption:

- Protects sensitive financial information with secure, industry-standard encryption for data transmission and storage.

##  QR Code Access:

- Allows users to scan a QR code from their TV or computer to instantly access their portfolio view.
  
## Interactive Avatar Agentic AI Assistant:

-  Provides personalized, human-like guidance to help users interpret their portfolio and explore actionable insights.

## Installation Requirements:

- Ensure you have the following software and frameworks installed.

## Prerequistes:

- Python
- Pandas
- PyTorch
- Matplotlib
- Numpy
- RS256 Asymmetric Encruption
- JSON
- QR Code
- LangGraph
- Avatar AI
- Agentic AI
- MCP Server

## Python: Required for all major components.

- Pandas
- PyTorch
- Pandas
- Matplotlib
- Numpy

## RS256 Asymmetric Encryption Setup (JWT-based):

- RS256 is an RSA signature algorithm used with JSON Web Tokens (JWT). It uses a private key to sign data and a public key to verify it.

## QR Code:

- After generating your portfolio data, create a QR code that links to a local file or static message. Display the QR code on a TV or computer screen, and users can scan it with their phone to instantly view the portfolio content or download the file.

 ## LangGraph: Orchestrating Avatar Behavior:
 
- Use LangGraph to define the agentic flow behind your avatar — how it responds, escalates, or loops through reasoning steps.
- Nodes.
- Greeting the user
- Interpreting portfolio metrics
- Answering follow-up questions
- Escalating to deeper analysis or external APIs

## Avatar Setup in Google Colab:

## Create and Download Your Avatar:

- Use Krikey AI to design your avatar.
- Export it  image (PNG/JPEG) depending on your demo style.
  
## Upload the Avatar to Colab:

- In Colab, click the folder icon on the left → upload your avatar file.
- You’ll see it listed under “Files.”
  
## Display the Avatar:

- For images: use Markdown or HTML to show it in the notebook.
  
- Add a Scripted Introduction:

- Write a short welcome message below the avatar (e.g., “Hi, I’m your portfolio assistant!”).

## Overview:

Design a multi-step LangGraph that processes incoming text and generates structured reports based solely on normalized input and detected.

## Node Configuration:

## Input Normalization:

- Purpose: Clean and standardize the incoming text.
  
- Actions:
  
- Remove extra spaces, symbols, and formatting noise
- Normalize punctuation and casing
- Prepare for consistent downstream processing
  
## Intent Detection:

- Purpose: Identify what the user wants (e.g., generate report, summarize, escalate).
  
- Actions:
  
- Use NLP to classify the user’s intent.

## Report Generator:

- Purpose: Produce a structured output based on the detected intent.
  
- Actions:
  
- Format insights into readable sections.
- Highlight key metrics, summaries, or action items.

## Fallback:

## Actions:

## Retry Logic:
- Attempt translation using alternate models or heuristics (e.g., Gemini fallback, rule-based translation, cached phrases).
  
## User Notification:

- Send a friendly message like:
- “I couldn’t fully process that input. Could you clarify or rephrase it?”
  
## Clarification Prompt:

- Ask the user to confirm the source language or intent if confidence is low.

## Output Node Configuration:

- Deliver the final report or summary to the user, enriched with metadata for clarity and traceability.

## Data Referral:




  

  

