# UnWrapped: Spotify Wrapped (CS 2340 Team Project)

A full-stack Django web app that connects to a user's Spotify account and generates a personalized "Wrapped" slideshow of their listening stats, with LLM-powered insights and holiday-themed versions.

**Team:** Aditi Koratpallikar, Aarush Kachhawa, Pranav Kadekodi, Anya Khosla, Atharva Khandelwal

## Tech Stack
- Python
- Django
- Spotify Web API
- OpenAI API
- SQ
- HTML/CSS

## Features
- **Spotify integration:** OAuth login with token refresh, top artists and tracks across short, medium, and long time ranges, and recently played history
- **Wrapped slides:** top artists and songs, most popular artists, seasonal listening mood, "night owl" listening-time analysis, and ad-time estimates
- **LLM insights:** OpenAI-generated insights based on listening habits
- **Holiday themes:** full Halloween and Christmas versions of the Wrapped experience, plus dark mode
- **Accounts:** registration, login, password reset, profile, past Wraps, and account deletion

## My Contributions
- Built the account flows: login and registration UI (from our Figma designs), password reset, profile, and account deletion
- Built the theming system: all Halloween and Christmas templates and nav bars, and dark mode across every theme, using Django template inheritance
- Wired up the Django views and URL routing for these pages
- Resolved recurring merge conflicts between holiday-theme branches by restructuring shared template logic
