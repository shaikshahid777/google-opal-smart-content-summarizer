# Workflow Documentation

## Goal

Build a Smart Content Summarizer in Google Opal that helps a user quickly understand long-form content.

## Tripartite Flow

```text
User Input → Generate → Output
```

### User Input

The user provides either:

- A YouTube video URL
- A PDF document

### Generate — Logic & Reasoning

Gemini processes the supplied content and generates a clear, concise summary focused on the key ideas.

### Output — Presentation

The generated summary is rendered as a readable webpage so the user can quickly review the result.

## Design Principle

Each node has one clear responsibility: ingest content, reason over the content, or present the result. The workflow demonstrates how user data flows through AI reasoning into a final application output.
