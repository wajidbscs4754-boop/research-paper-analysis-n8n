# Research Paper Analysis & Weekly Research Monitor

An AI-powered research automation system built with **n8n, arXiv, OpenRouter, and JavaScript**.

The project automates academic paper discovery, paper-level analysis, research-gap identification, and weekly research monitoring.

---

## 📌 Project Overview

Researchers, students, and technical teams often spend a significant amount of time searching through newly published research papers and trying to understand:

- What has already been researched?
- What are the important findings?
- What methods and datasets are being used?
- What problems are still unresolved?
- What new research opportunities are emerging?
- What changed in the research field this week?

This project uses **n8n workflow automation and LLM-based analysis** to automate these tasks.

The project contains two main workflows:

1. **Research Gap Analyzer**
2. **Weekly Research Monitor**

The original project goal is to combine AI, automation, and academic-paper APIs into a portfolio-ready research automation system.  

---

# 🚀 Features

## 1. Research Gap Analyzer

The Research Gap Analyzer is an on-demand workflow for analyzing a research topic and identifying potential research gaps.

### Workflow

```text
Research Topic
      ↓
Search arXiv
      ↓
Retrieve Research Papers
      ↓
Extract Paper Metadata
      ↓
AI Analysis of Each Paper
      ↓
Compare Papers
      ↓
Identify Common Findings & Limitations
      ↓
Identify Overall Research Gap
      ↓
Generate Proposed Research Direction
      ↓
Generate Research Report
      ↓
HTML Output
