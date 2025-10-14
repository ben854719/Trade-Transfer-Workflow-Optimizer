## Trade Transfer Workflow Optimizer

## Objective

This application showcases an AI-powered portfolio analysis tool designed to deliver secure, emotionally intelligent insights across devices. The application will use Pandas for data modeling and cleaning.  RS256 encryption safeguards the use financial information by providing a secure and tamper-proof layer of protection. The avatar-driven assistant offers users a warm, human-like clarity that feels both intuitive and personal. The graph compares actual vs. predicted close prices, enriched with sentiment overlays—“Confident,” “Cautious,” and “Surprised”—based on model accuracy. The AI delivers high-precision insights into asset allocation, sector exposure, and performance trends using advanced algorithms, while adapting its guidance dynamically based on user behavior and portfolio context. With ≥95% analysis precision, <2-second latency, 100% encryption compliance, and 80% avatar engagement.

## Video for the project:

[YouTub](https://youtu.be/Lwz7VxuqY3M)

## Features:

## AI-Powered Stock Portfolio Analysis:

- Delivers high-precision insights into asset allocation, sector exposure, and performance trends using advanced algorithms.

## Data Cleaning & Modeling with Pandas:

- Ensures reliable analysis by preprocessing and structuring raw portfolio data for consistency and clarity.

##  RS256 Asymmetric Encryption:

- Protects sensitive financial information with secure, industry-standard encryption for data transmission and storage.

## Interactive Avatar Agentic AI Assistant:

-  Provides personalized, human-like guidance to help users interpret their portfolio and explore actionable insights.

## Installation Requirements:

- Ensure you have the following software and frameworks installed.

## Prerequistes:

- Cryptography
- Python
- Pandas
- PyTorch
- Matplotlib
- Numpy
- Seaborn
- RS256 Asymmetric Encruption
- JSON
- LangGraph
- Avatar AI
- Agentic AI
- OpenCV
- MCP Server

## Python: Required for all major components.

- Pandas
- PyTorch
- Pandas
- Matplotlib
- Numpy
- Seaborn

## RS256 Asymmetric Encryption Setup:

- RS256 is an RSA signature algorithm used with JSON Web Tokens (JWT). It uses a private key to sign data and a public key to verify it.

 ## LangGraph: Orchestrating Avatar Behavior:
 
- Use LangGraph to define the agentic flow behind your avatar — how it responds, escalates, or loops through reasoning steps.
- Nodes.
- Greeting the user
- Interpreting portfolio metrics
- Answering follow-up questions
- Escalating to deeper analysis or external APIs

## Avatar Setup in Google Colab:

## Create and Download Your Avatar:

- Use insmind to design your avatar.
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

- Dataset title: MarketWatch
- Links: https://www.marketwatch.com/investing/index/gsptse/download-data?startDate=9/7/2025&endDate=10/07/2025&countryCode=ca

- Dataset title: Simplewallet ST>
- Links: https://simplywall.st/stocks/ca/banks/tsx-bmo/bank-of-montreal-shares

- Dataset title: Simplewallet ST.
- Links: https://simplywall.st/stocks/ca/banks/tsx-cm/canadian-imperial-bank-of-commerce-shares/news/is-cibcs-recent-25-rally-justified-after-strong-quarterly-ea

- Dataset title: Simplewallet ST.
- Links: https://simplywall.st/stocks/ca/banks/tsx-bns/bank-of-nova-scotia-shares/news/scotiabank-tsxbns-valuation-in-focus-after-new-bond-offering

- Dataset title:  Simplewallet ST.
- Links: https://simplywall.st/stocks/ca/banks/tsx-na/national-bank-of-canada-shares/news/a-fresh-look-at-national-bank-of-canada-tsxna-valuation-foll




  

  

