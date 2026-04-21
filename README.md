♻️ # NextUse — EcoBot

EcoBot is the AI-powered recycling assistant built into the NextUse application. It guides users to recycle better by answering waste disposal questions through natural, everyday conversation — telling you exactly which bin an item belongs in, how to prepare it, and why it matters.

# What the Project Does
NextUse is an application built with a single major purpose — to provide a meaningful solution to UN Sustainable Development Goal 13: Climate Action. One of the ways NextUse works toward this is through EcoBot, its intelligent recycling assistant.
EcoBot lives inside the NextUse application and acts as a knowledgeable guide for waste disposal. Instead of guessing which bin to use or searching through confusing leaflets, users simply describe an item in plain English and EcoBot responds instantly with clear, accurate guidance.
It covers four core areas:

Waste sorting — identifies the correct bin: recycling, compost, general waste, or hazardous
Preparation advice — tells you how to clean, flatten, or separate items before disposal
Recycling education — explains plastic codes, recycling symbols, and contamination risks
Eco-friendly tips — suggests sustainable habits and alternatives to single-use products

Every conversation is saved locally so users can refer back to past guidance. EcoBot also remembers what was said earlier in the same session, so follow-up questions feel natural and effortless.

# Why the Project Is Useful
Climate change is one of the most urgent challenges of our time, and how we manage waste plays a direct role in it. Landfills produce methane — a greenhouse gas far more potent than CO₂. When recyclable materials end up in the wrong bin, they go to landfill, contributing to emissions that drive climate change.
The problem isn't that people don't care — it's that recycling rules are complex, inconsistent, and hard to remember. This confusion leads to recyclable materials being thrown away incorrectly, and entire batches of recycling being contaminated and lost.
EcoBot — as part of the NextUse application — directly tackles this by making correct recycling behaviour the easiest option. Users get instant, personalised guidance without needing to search anything. Every correctly sorted item is a small but real contribution to reducing the climate impact of waste.
NextUse is built to contribute to UN SDG 13 — Climate Action by empowering everyday people to make better environmental decisions, one recycling question at a time.

# How Users Can Get Started
Requirements
Before you begin, make sure you have the following:

Node.js version 18 or higher
A free Groq API Key — takes under 2 minutes to create

Installation
1. Clone the repository
bashgit clone https://github.com/bawo7/NextUse-Ecobot.git
cd NextUse-Ecobot
2. Install dependencies
bashnpm install
3. Add your API key
Create a .env file in the root folder and add the following line:
envGROQ_API_KEY=your_api_key_here
Replace your_api_key_here with the key from your Groq account. Never share this key or upload it to GitHub.
4. Run EcoBot
bashnode index.js
EcoBot will start and you can begin chatting straight away.
Example
🤖 EcoBot: Hi! I'm EcoBot, NextUse's recycling assistant. What would you 
            like help disposing of today?

👤 You: Can I recycle a plastic bag?

🤖 EcoBot: Plastic bags should NOT go in your home recycling bin — they jam
            sorting machines at recycling facilities. Instead, take them to a
            dedicated plastic bag drop-off point, usually found at most
            supermarkets. Better yet, switch to a reusable bag to avoid
            the problem entirely!


Made with 💚 for a cleaner planet · NextUse Capstone Project 2026 · UN SDG 13 — Climate Action
