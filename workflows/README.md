# AutoViral Engine Workflows

This directory contains the exported n8n workflows used by AutoViral Engine.

## Overview

AutoViral Engine is an AI-powered social media video production system that transforms a single idea into a fully rendered, ready-to-publish video through autonomous workflow orchestration.

The workflow automates the complete content creation pipeline, including:

- AI caption generation
- Script generation
- Voiceover creation
- AI image generation
- Image-to-video conversion
- Caption synchronization
- Video rendering
- Asset management
- Production tracking

---

## Workflow Architecture

Input Idea
↓
AI Caption Generation
↓
Script Generation
↓
Parallel Processing
├── Voice Generation
└── Visual Generation
↓
Media Synchronization
↓
Video Rendering
↓
Final Video Output

---

## Technologies Used

### Automation Platform

- n8n

### AI Models & Services

- OpenAI
- ElevenLabs
- PiAPI
- Flux
- Kling AI

### Video Production

- Creatomate

### Storage & Tracking

- Google Drive
- Google Sheets

---

## Features

### Content Generation

- AI-generated viral captions
- Automated script writing
- Prompt-based content creation
- Multi-stage content refinement

### Voice Production

- AI voice generation
- Natural narration creation
- Automated audio processing

### Visual Production

- AI image generation
- First-person POV image creation
- Image-to-video generation
- Automated visual asset creation

### Production Pipeline

- Parallel execution workflows
- Automated processing
- Status tracking
- Retry mechanisms
- Cost monitoring
- Scalable architecture

### Rendering

- Automated video assembly
- Caption synchronization
- Audio synchronization
- Final video rendering

---

## Required Services

Before importing the workflow, create accounts and obtain API credentials for the following services.

### OpenAI

Purpose:

- Caption generation
- Script generation
- Content enhancement

Required:

- OpenAI API Key

---

### ElevenLabs

Purpose:

- AI voice generation
- Narration creation

Required:

- ElevenLabs API Key

---

### PiAPI

Purpose:

- AI image generation access

Required:

- PiAPI API Key

---

### Flux

Purpose:

- AI image creation

Required:

- Flux model access

---

### Kling AI

Purpose:

- Image-to-video conversion

Required:

- Kling API access

---

### Creatomate

Purpose:

- Video rendering
- Video assembly

Required:

- Creatomate API Key

---

### Google Drive

Purpose:

- Asset storage
- Media management

Required:

- Google OAuth Credentials

---

### Google Sheets

Purpose:

- Production tracking
- Status management
- Cost tracking

Required:

- Google OAuth Credentials

---

## Installation

### Step 1

Install n8n.

### Step 2

Download the workflow JSON file from this repository.

### Step 3

Open n8n.

### Step 4

Import the workflow.

Workflow → Import from File

### Step 5

Configure all credentials.

Replace every placeholder credential with your own API keys.

### Step 6

Update Google Drive folders.

Configure:

- Output folder
- Asset folder
- Render folder

### Step 7

Update Google Sheets configuration.

Configure:

- Spreadsheet ID
- Sheet names
- Tracking columns

### Step 8

Test the workflow using a sample video idea.

---

## Required Credentials Checklist

Before running the workflow ensure the following credentials are configured:

- OpenAI API Key
- ElevenLabs API Key
- PiAPI API Key
- Kling AI Access
- Creatomate API Key
- Google Drive OAuth
- Google Sheets OAuth

---

## Example Input

Video Idea:

How AI Automation Can Replace Manual Content Production

Environment Prompt:

Modern technology workspace with futuristic AI systems

Production Status:

Ready

---

## Example Output

The workflow automatically generates:

- Viral caption
- Full narration script
- AI voiceover
- AI-generated images
- Animated video clips
- Synced captions
- Final rendered social media video

---

## Important Notes

This workflow does not include API keys or private credentials.

You must configure your own accounts and credentials before running the workflow.

Some services may require paid subscriptions depending on usage volume.

---

## Author

Suraj Rathod

Computer Engineering Student | AI & Automation Enthusiast

GitHub:
https://github.com/Surajrathod07

LinkedIn:
Connect with me for collaboration, improvements, and automation discussions.

---

## License

This project is released under the MIT License.
