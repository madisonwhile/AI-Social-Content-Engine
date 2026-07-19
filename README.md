# AI Social Content Engine

## Overview

The AI Social Content Engine is a multi-agent AI system that generates platform-specific social media image and short-form video prompts from a brand brief.

Users provide information about a brand, product images, and optional creative references. The system then develops a social media strategy before generating AI-ready prompts for platforms such as TikTok, Instagram Reels and YouTube Shorts.

Rather than relying on a single prompt, the system separates the creative process into specialised AI agents, each responsible for a different stage of content production.

---

## The Problem

Creating engaging social media content requires more than producing attractive visuals.

Different platforms have different audiences, trends and creative styles, while brands need to maintain a consistent identity across every piece of content.

I wanted to explore whether AI could move beyond simply generating prompts and instead assist with the creative thinking that happens before content is produced.

---

## Features

- Multi-agent architecture
- Brand strategy generation
- Product analysis
- Platform-specific image prompts
- Platform-specific video prompts
- Storyboard generation
- Image-to-video workflow
- Download prompts individually or as a ZIP
- Flask web application

---

## Tech Stack

- Python
- Flask
- Anthropic API
- Railway
- Gunicorn
- Polling architecture

---

## How It Works

1. User submits a brand brief.
2. Uploads product images.
3. Optionally uploads moodboards and previous social content.
4. AI develops a brand and social media strategy.
5. Products are analysed individually.
6. Specialised agents generate image and video prompts.
7. Prompts are available for download and can be used with AI generation tools.

---

## What I Learned

This project taught me that successful AI creative systems rely on much more than prompt engineering.

Some of the biggest discoveries included:

- Giving AI clear creative roles produces stronger outputs than one large prompt.
- Reference images preserve product accuracy far better than text descriptions.
- Authenticity is more important than perfection when generating social content.
- Small prompt design changes can dramatically improve AI-generated video quality.

Perhaps the biggest lesson was that building creative AI systems is just as much about designing workflows as it is about designing prompts.

---

## Future Improvements

Some ideas I'd like to explore in future versions include:

- Persistent brand memory
- Campaign history
- Caption and voiceover generation
- Trend research
- Performance analysis
- Publishing calendar
- Creative feedback agent
- Social media dashboard

---

## Screenshots

Project screenshots, workflow diagrams and example outputs can be found in the Assets folder.

> **Note:** Brands shown in this repository (such as Poppi and Aritzia) were used solely as public case studies to evaluate the system's performance. This project is an independent technical exploration and is not affiliated with or endorsed by these brands.
