# Amazon Bedrock AgentCore Browser Tool

## Overview

Amazon Bedrock AgentCore Browser Tool provides AI agents with a secure, fully managed way to interact with websites just like humans do. It allows agents to navigate web pages, fill out forms, and complete complex tasks without requiring developers to write and maintain custom automation scripts.

## How it works

A browser tool sandbox is a secure execution environment that enables AI agents to safely interact with web browsers. When a user makes a request, the Large Language Model (LLM) selects appropriate tools and translates commands. These commands are executed within a controlled sandbox environment containing a headless browser and hosted library server (using tools like Playwright). The sandbox provides isolation and security by containing web interactions within a restricted space, preventing unauthorized system access. The agent receives feedback through screenshots and can perform automated tasks while maintaining system security. This setup enables safe web automation for AI agents

![architecture local](../02-Agent-Core-browser-tool/images/browser-tool.png)

## Key Features

### Secure, Managed Web Interaction

Provides AI agents with a secure, fully managed way to interact with websites just like humans do, allowing navigation, form filling, and complex task completion without requiring custom automation scripts.

### Enterprise Security Features

Provides VM-level isolation with 1:1 mapping between user session and browser session, offering enterprise-grade security. Each browser session runs in an isolated sandbox environment to meet enterprise security needs

### Model-Agnostic Integration

Supports various AI models and frameworks while providing natural language abstractions for browser actions through tools like interact(), parse(), and discover(), making it particularly suitable for enterprise environments. The tool can execute browser commands from any library and supports various automation frameworks like Playwright and Puppeteer.

### Integration

Amazon Bedrock AgentCore Browser Tool integrates with other Amazon Bedrock AgentCore capabilities through a unified SDK, including:

- Amazon Bedrock AgentCore Runtime
- Amazon Bedrock AgentCore Identity
- Amazon Bedrock AgentCore Memory
- Amazon Bedrock AgentCore Observability

This integration aims to simplify the development process and provide a comprehensive platform for building, deploying, and managing AI agents, with powerful capabilities to perform browser based tasks.

### Use Cases

The Amazon Bedrock AgentCore Browser Tool is suitable for a wide range of applications, including:

- Web Navigation & Interaction
- Workflow Automation including filling forms

## Tutorials overview

In these tutorials we will cover the following functionality:

- [Getting Started with Bedrock AgentCore Browser Tool and NovaAct](01-browser-with-NovaAct/01_getting_started-agentcore-browser-tool-with-nova-act.ipynb)
- [Amazon Bedrock AgentCore Browser Tool Live View and Nova Act](01-browser-with-NovaAct/02_agentcore-browser-tool-live-view-with-nova-act.ipynb)
- [Getting Started with Bedrock AgentCore Browser Tool and Browser use](02-browser-with-browserUse/getting_started-agentcore-browser-tool-with-browser-use.ipynb)
- [Amazon Bedrock AgentCore Browser Tool Live View and Browser Use](02-browser-with-browserUse/agentcore-browser-tool-live-view-with-browser-use.ipynb)
