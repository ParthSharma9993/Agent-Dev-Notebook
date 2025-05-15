# 🧠 Agent Development Kit (ADK) Playground

Welcome to my **Agent Development Kit (ADK) Playground** — a learning-focused repository built using **Python**, where I explore and implement various types of AI agents.

This repository is designed as a practical guide and sandbox for understanding how different agent architectures work. From sequential to parallel agents, and from callback-based logic to multi-agent collaboration, this project showcases both foundational and experimental agent designs.

---

## 📚 Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
- [Agent Types Implemented](#agent-types-implemented)
  - [Sequential Agent](#1-sequential-agent)
  - [Callbacks Agent](#2-callbacks-agent)
  - [Tools Agent](#3-tools-agent)
  - [Multi-Agent System](#4-multi-agent-system)
  - [Parallel Agent](#5-parallel-agent)
  - [LiteLLM Agent](#6-litellm-agent)
  - [Loop Agent](#7-loop-agent)
  - [Stateful Multi-Agent](#8-stateful-multi-agent)
- [Dependencies](#dependencies)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [License](#license)
- [Author](#author)

---

## 🧩 Overview

This repository contains working examples and experimentation around intelligent agents using a modular and extensible approach. The goal is to understand agent reasoning, control flow, communication, and integration with tools and APIs.

These agents are implemented using **Python** and integrate concepts such as:
- Sequential task execution
- Event-driven callbacks
- Tool-enhanced reasoning
- State sharing and memory
- Concurrency and parallelism
- Multi-agent orchestration
- Lightweight integration with LiteLLM

---

## 🚀 Getting Started

To clone and run this project:

```bash
git clone https://github.com/<your-username>/adk-agent-lab.git
cd adk-agent-lab
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
