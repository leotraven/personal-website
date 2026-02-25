---
author: Leo Traven
pubDatetime: 2026-02-25T18:22:00Z
modDatetime: 2026-02-25T18:22:00Z
title: Becoming a manager of agents
slug: becoming-a-manager-of-agents # seen in the url
featured: false
draft: false
tags:
  - ai
  - agents
description: Although being a developer, I find myself acting more and more like a manager.
---

<!-- Situation -> Complication -> Question -> Answer -->

### TL;DR:
- Software engineering once was about writing code manually
- Nowadays, agents can serve on behalf of software engineers
- The role of software engineers changes from manual building to managing agents, which drastically increases their leverage
- Strategy and quality gates are more important than ever
- You still have to understand what you build to make good decisions


### The end of manual syntax
When I pivoted to software engineering in 2022, I spent a lot of time learning Python.
The job was about writing code manually, line by line.
Sometimes, this involved searching for errors in the code for several hours.

Since then, AI agents gradually became more powerful.
They consist of generative AI models coupled with tools that enable them to interact with their environment.
Given the right context, they can work on their own in the digital space.
Based on instructions and work contexts, they choose tools to be executed.
For example, a tool might allow them to edit a file.
The AI model can say which file it wants to edit, which parts of the file it wants deleted and what it wants to be added.
This is especially helpful for coding, where you have repositories consisting of many files that each are full of code.
You typically store code in one file, and reference it in another one.
This way, you can use different areas of a repository to serve different purposes.

Understanding how code works can be hard.
This is especially the case if you did not write the code yourself.
In the beginning of 2025, I was surprised when an agent could solve a coding problem at first try.
Now, I'm disappointed when it can't.
In most cases, it is not only faster to let agents write code for you, but the quality is often higher than what I could have produced.

<!-- ### What do you even need developers for? -->

### The role of software engineers is shifting from manual building to managing agents

I find myself outsourcing more and more work to agents.
My focus is not on creating code anymore, but on reviewing it.
Essentially, the coding layer is abstracted away.
As it's easier and easier to produce code, the value of each unit of code diminishes.
If I want a hyper-personalized app just for myself, it's now easier than ever to get it.
If I realize that I am not satisfied with a solution to a coding problem, I just throw it away and start from scratch again.

As each developer has an increasingly big lever to make changes, it is crucial for teams to define common strategies.
This can contain architecture decisions, but also code quality standards and development methodologies.
As AI agents increase development speed enormously, the direction of development is more important than ever.
If you go into the wrong direction, speed does not help you.
To make sure I am on the right track, I find myself aligning with colleagues more and more often.

To control agents, it's all about setting the right guardrails.
If newly generated code does not pass the bar for security, it should be declined.
You can also build loops of agents controlling each other.
One agent can generate code, while the other one ensures its quality and security.
By closing these loops, developers can focus on giving strategic directions.

I find myself constantly evaluating agent outputs against the target architecture of the system I want to build.
To do so, I have to understand what my agents do and what this means for my system.
Then I have to refine.
As it turns out, software engineers are still programming.
The syntax has just changed to natural language.


<!-- - Skills are changing
- Software engineers are still coding - but in natural language
- Role of developers changes to project managers
- it's all about closing loops and managing context


What are caveats?
- If you do not know the direction, every street is correct???
- it's important to enforce quality gates -->

