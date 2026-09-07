# AI Pulse

AI Pulse is an automated AI news intelligence pipeline built with **n8n** and **Gemini**. It collects recent AI news from multiple sources, filters and processes the articles, uses an LLM to identify the most important stories, and generates an HTML newsletter.

## Overview

Keeping up with AI news can mean going through multiple websites and articles every day. AI Pulse automates this process and delivers a short newsletter containing the most relevant AI stories.

The pipeline runs automatically and handles the process from collecting articles to generating the final newsletter.

## Workflow

```text
AI News Sources
      ↓
RSS Feed Collection
      ↓
Cleaning & Filtering
      ↓
Article Processing
      ↓
Gemini Analysis & Ranking
      ↓
Top 5 Stories
      ↓
HTML Newsletter
      ↓
Email Delivery
```

## Features

* Collects AI news from multiple RSS feeds
* Filters recent articles
* Removes duplicate content
* Uses Gemini to evaluate article importance
* Selects the top 5 stories
* Generates a formatted HTML newsletter
* Sends the newsletter through Gmail
* Runs automatically using n8n

## Tech Stack

* **n8n** - Workflow automation
* **Google Gemini** - AI-based article analysis
* **RSS Feeds** - News collection
* **Gmail** - Newsletter delivery
* **JavaScript** - Data processing and transformation

## Sources

The current workflow collects articles from:

* Google AI
* OpenAI
* Hugging Face
