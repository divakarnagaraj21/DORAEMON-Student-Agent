# DORAEMON: AI Personal Counselor & Growth Companion

## Overview
**DORAEMON** is an AI-powered personal companion for students that improves productivity, emotional well-being, and spiritual growth. It integrates to-do management, mood-based recommendations, meditation guidance, and spirituality support tailored to the user's religion.

Students can manage daily tasks, track moods, get personalized suggestions for self-growth, and engage in mindfulness and spiritual practices — all while keeping their data private.

---

## Features

- **To-Do List Management:** Add, track, and complete daily tasks; visualize task status.  
- **Mood-Based Recommendations:** AI suggests activities based on your current mood.  
- **Meditation & Mindfulness:** Daily meditation recommendations to reduce stress.  
- **Spiritual Guidance:** Guidance from Hinduism, Christianity, Islam, or Buddhism.  
- **Logging & Visualization:** Logs moods and tasks daily; visualizes trends over time.

---

## Architecture

DORAEMON is a multi-agent system:

- **ToDoAgent:** Manages tasks.  
- **MoodAgent:** Suggests activities based on mood.  
- **SpiritualAgent:** Provides spiritual guidance.  
- **DORAEMON Orchestrator:** Integrates all agents for daily sessions.

All data is stored locally in memory, with visualizations using `matplotlib`.

---

## Installation

```bash
git clone https://github.com/yourusername/DORAEMON-Student-Agent.git
pip install matplotlib
python DORAEMON_Student_Agent.py
