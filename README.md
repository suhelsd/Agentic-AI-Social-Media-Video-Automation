# 🤖 Agentic AI Social Media Video Automation

An AI-powered workflow automation project that converts a single user prompt into a social-media-ready short video.

## 📌 Project Overview

The Agentic AI Social Media Video Automation system uses multiple AI agents and automation tools to automatically create short-form video content.

The user provides one prompt, such as:

"Create a 60-second Instagram Reel about Artificial Intelligence in Education."

The workflow then processes the request through multiple stages:

User Prompt
↓
n8n Webhook
↓
Planning Agent
↓
Script Agent
↓
Scene Agent
↓
Visual Agent
↓
Visuals
↓
Piper TTS
↓
Whisper Subtitles
↓
FFmpeg
↓
Quality Control
↓
SEO Agent
↓
Schedule
↓
YouTube + Instagram
↓
Email Notification


## 🎯 Objectives

The project demonstrates:

- Workflow automation using n8n
- Running AI models locally using Ollama
- Creating multiple AI agents
- Processing JSON using n8n Code nodes
- Generating scripts automatically
- Converting scripts into scenes
- Preparing visual content
- Generating voiceovers
- Generating subtitles
- Creating videos using FFmpeg
- Performing AI-based quality control
- Generating SEO information
- Scheduling content
- Publishing content through supported APIs
- Sending email notifications


## 🧠 AI Agents

### 1. Planning Agent

Creates the basic content plan from the user's request.

### 2. Script Agent

Converts the content plan into a spoken video script.

### 3. Scene Agent

Divides the script into individual scenes and creates visual descriptions.

### 4. Visual Agent

Creates prompts/instructions for the visuals required for each scene.

### 5. Quality Agent

Checks the generated video and determines whether it passes the required quality checks.

### 6. SEO Agent

Generates:

- Title
- Description
- Keywords
- Tags
- Caption
- Hashtags


## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| n8n | Workflow automation |
| Docker | Running services in containers |
| Ollama | Local AI/LLM |
| Piper TTS | Voice generation |
| Whisper | Speech-to-text and subtitles |
| FFmpeg | Video generation |
| Visual API / licensed visual source | Visual content |
| YouTube API | YouTube publishing |
| Instagram/Meta API | Instagram publishing |
| Email service | Notifications |


## 📂 Project Structure

```text
agentic-social-media-ai/
│
├── docker-compose.yml
│
├── n8n_data/
│
├── output/
│
├── visuals/
│
├── audio/
│
├── subtitles/
│
└── videos/
