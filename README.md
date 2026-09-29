# Coop Goblin

A DIY local AI agent for learning how personal agents work—and exploring what an assistant built around my own life and workflow can do.

## Goal

Build an agent I can talk to from my MacBook and, eventually, my phone. It should use models running on hardware I own, remember context I explicitly give it, and help me understand and resume work across projects. CauseTrail is the first project to explore, but Coop Goblin should remain separate from it.

This is also an experiment in going beyond a general chatbot. I want to discover which custom connections, memory, tools, interfaces, and behaviors make an agent uniquely useful to me. Don't assume every feature needs to be built; help me test ideas and keep what proves valuable.

## Why build it?

ChatGPT is like eating at a great restaurant. You can ask for something special, and the kitchen might make it for you. Coop Goblin is me building a kitchen at home. I can change the stove, swap recipes, see exactly what's in the pantry, and still cook when the restaurant's closed.

The point is ownership and control, not a claim that the home kitchen makes better food.

## Pieces to explore

- **Local models:** Run and compare models on my 2023 MacBook Pro with an M2 Max and 32 GB of memory.
- **Agent behavior:** Give Coop Goblin useful tools and rules I can understand and change.
- **Project connections:** Start with selected CauseTrail information, then explore other work and personal contexts.
- **Personal memory:** Save facts, decisions, and preferences I choose in a form I can inspect, edit, and remove.
- **Interfaces:** Start on the Mac; explore useful ways to interact from my phone later.
- **Distinctive ideas:** Experiment with features a generic chat session would struggle to provide, such as project-aware recaps, timely reminders based on my own workflow, and continuity across devices.

## First milestone

Make a small, working experiment that can answer **"Where was I with CauseTrail?"** using a limited set of project information. Keep the first connection read-only. Show which information the answer came from so I can judge whether it's useful.

## Approach

Use one repo for Coop Goblin and keep it separate from the CauseTrail repo. Favor simple, understandable components and document what each one does. Don't assume the final model, framework, phone interface, or dedicated hardware yet; let experiments guide those choices.

## First step for Claude

Help me identify a few genuinely personal capabilities Coop Goblin could offer beyond a standard chatbot. Then choose the smallest practical first milestone to test one of them on my existing MacBook. Explain the proposed components and tradeoffs before implementation, and build and verify that milestone with me.
