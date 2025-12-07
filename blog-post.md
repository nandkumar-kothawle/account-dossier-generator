---
title: Making Sense of Years of Training Material — Automatically
author: Nandkumar Kothawle
description: A lightweight automation that scans folders of PDFs, PPTs, spreadsheets, and documents to generate concise training dossiers using AI assistance.
---

## The Problem

Over the years I collected multiple training materials — PDFs, PPT decks, Excel trackers, notes, and reference documents spread across many subfolders. Going through them manually to understand what each folder contained was time-consuming and inefficient.

The Week 2 challenge in AI for Bharat asked us to automate a “boring digital task”. For me, this was the perfect opportunity.

---

## The Solution

I built a simple yet powerful dossier generator using Google Colab. It:

- Scans a Google Drive folder (e.g., “Business Training”)
- Extracts readable content from documents (PDF, DOCX, PPTX, XLSX, TXT)
- Generates a clear, 2–3 sentence summary for each subfolder
- Lists relevant files with inferred statuses (Draft, Final, etc.)
- Produces suggested next actions and a global CSV index

This turned a large, unstructured collection of files into a structured knowledge base.

---

## How Kiro Helped

Kiro accelerated development in several ways:

- Helped design the extraction + summarization pipeline  
- Generated Python scaffolding for the Colab notebook  
- Refined the text summarization heuristics  
- Drafted both README and this blog post  

Kiro simplified the process so that even with limited coding experience, the automation became easy to build.

---

## How to Use It Yourself

1. Open the Colab notebook  
2. Mount Google Drive  
3. Set the `BASE` folder path  
4. Run the cell  
5. Download the generated dossiers and index file  

---

## GitHub Repository

https://github.com/nandkumar-kothawle/account-dossier-generator
