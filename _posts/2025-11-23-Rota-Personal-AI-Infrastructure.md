---
layout: post
title: Rota Building My Personal AI Infrastructure
categories: [AI]
tags: [AI, PAI, Rota]
redirect_from:
    - /2025/11/23/
---

# Rota: Building My Personal AI Infrastructure

I began creating Rota right after reading Carl Heath’s post about his setup, which sent me to Daniel Miessler’s blog and YouTube video on Personal AI Infrastructure (PAI). After reading both blog posts and watching Daniel's 1 hour and 13 minutes video 🤯, I concluded one thing: it’s stupid simple.

The basic setup is stupid simple: put a single `AGENTS.md` in your home folder with your core instructions, then point every other `AGENTS.md` at that file. In minutes you have a working assistant that inherits one source of truth. When you need more capabilities, you just make it a little more complex: break it into a file structure with specific markdown files for different assignments.

This is my current PAI file structure that I built during one evening, and I named it Rota:

```text
~/.rota/
├── AGENTS.md
├── memory/
├── projects/
│   ├── AGENTS.md
│   └── General Notes/
│       └── AGENTS.md
└── roles/
```

I even used Rota to partially build this post: it read the relevant `AGENTS.md` files for context and guidance before drafting. The output wasn’t quite worthy of publish. I still need to polish the context files, but I got this blog post done in less than 30 min.

![Rota]({{site.urk}}/assets/images/rota.jpg)

I still lack two major parts: one agent for quality assuring the text and one that will convert it from Obsidian Markdown to Jekyll Markdown (including converting the Obsidian-specific front matter to Jekyll's front matter). But this just shows how stupid simple the setup is. Just start with one AGENTS.md or a small file structure for it, and then build it up as you need it.
## Why the Name Rota

Rota is an old Nordic Valkyrie name, tied to choosing who falls in battle and often translated as “disorder” or “unorganized.” I liked the contrast: a tool that helps me bring order to notes that would otherwise stay messy.
