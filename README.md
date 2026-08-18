# Google Opal - Smart Content Summarizer

## Module 1: The Foundations of Vibe-Coding

### Learner

Shaik Mohammad Shaheed

## Assignment

**Build Your First Opal Workflow: Smart Content Summarizer**

This beginner-friendly Google Opal mini-app accepts long-form content through a YouTube video URL or PDF document, uses Gemini to generate a clear and concise summary highlighting key ideas, and presents the result in a readable webpage.

## Core Architecture

The workflow follows the required tripartite structure:

```text
User Input → Generate → Output
```

### 1. User Input

- Video URL input for a YouTube video link
- Document File input for a PDF document

### 2. Generate

The Generate Summary step uses Gemini to process the supplied content and produce a concise summary with the main ideas and important points.

### 3. Output

The Render Webpage step presents the generated summary in a clean, readable format.

## Workflow Test

A public YouTube video was used to test the workflow. The app successfully generated a structured webpage summary titled **The 5:1 Ratio**.

The output included:

1. The 5:1 Ratio
2. Negativity Bias
3. Conflict Management
4. Predictive Power

## Evidence

### Loom Walkthrough

https://www.loom.com/share/82b717d6fc524d89ac80ae6bcac73bee

### Assessment PDF

The submitted assessment PDF documents the workflow architecture, implementation, test run, output evidence, learning outcomes, and conclusion.

## Repository Structure

```text
google-opal-smart-content-summarizer/
├── README.md
├── workflow.md
├── test_results.md
└── assessment_summary.md
```

## Completion Status

**Completed** — Smart Content Summarizer built and successfully tested in Google Opal.
