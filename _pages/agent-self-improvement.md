---
layout: archive
title: "Agent Self-Improvement"
permalink: /projects/agent-self-improvement/
author_profile: true
---

<p><img src="/files/projects/agent-self-improvement-banner.png" alt="Agent Self-Improvement banner"></p>

Project
======

* [GitHub repository](https://github.com/Chenwei-1999/agent-self-improvement)

Agent Self-Improvement is a portable agent skill for turning real conversation history into better agent behavior. It is designed for SKILL.md-compatible agents, including Codex, Claude Code, Gemini CLI, and generic agents that support filesystem-installed skills.

Why It Exists
======

Most agent self-improvement drifts into vague advice or hand-picked examples. This project keeps the workflow grounded in actual conversation history: it extracts compact cards from agent sessions, lets low-cost read-only scout agents scan many shards, and keeps final judgment with the main agent.

What It Does
======

* Reads Codex sessions, Claude projects, Gemini exports, and generic transcript folders.
* Produces compact conversation-card shards plus a manifest for verification.
* Uses role-based scouts for broad coverage and a main synthesizer for final rules.
* Defaults to scope-safe updates for the agent itself; project, memory, and global findings stay report-only unless explicitly requested.
* Includes an installer for Codex, Claude Code, Gemini CLI, generic agents, and custom skill directories.

Install
======

Give this GitHub link to a local coding agent:

```text
Install this skill: https://github.com/Chenwei-1999/agent-self-improvement
```
