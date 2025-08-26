---
title: Docker Agent Builder
description: Create, manage, and share AI agents with Docker Agent Builder.
keywords: ai agents, agent builder, marketplace, chat sessions
params:
  sidebar:
    badge:
      color: blue
      text: Beta
    group: AI
weight: 20
---

Docker Agent Builder is a comprehensive platform to create, manage, and
share AI agents. Build custom AI agents, discover community-created agents,
and manage interactive chat sessions with an intuitive interface.

## Prerequisites

Before you use Docker Agent Builder, make sure you have the following:

- **Docker Desktop**. Install Docker Desktop and sign in to your Docker account.
- **API keys**. Both OpenAI and Anthropic API keys are required.

  - **OpenAI API key**. Go to
     [OpenAI API Keys](https://platform.openai.com/settings/organization/api-keys)
     to create your key.
  - **Anthropic API key**. Go to
     [Anthropic Console](https://console.anthropic.com/settings/keys) to create
     your key.

- Add both API keys to your shell configuration file:

   ```bash
   export OPENAI_API_KEY=<your_openai_key>
   export ANTHROPIC_API_KEY=<your_anthropic_key>
   ```

## Get started with Docker Agent Builder

The application has these sections:

- **Agents**: Create and manage your custom AI agents
- **Sessions**: View and manage your active conversations with agents
- **Marketplace**: Discover and download AI agents from the community
- **Settings**: Configure your application preferences

## Use the agent marketplace

The **Marketplace** section lets you discover and download AI agents
created by the community. Features include:

- Browse available agents from the community.
- Search for agents by name or description.
- Pull agents directly from Docker Hub.
- View agent descriptions and capabilities.

### Find agents in the marketplace

1. Select **Marketplace** in the sidebar.
1. Browse the available agents or use search:
   - Use the **Pull an agent from Docker Hub** search bar to import specific
     agents.
   - Use the **Search marketplace agents by name or description** field to find
     relevant agents.
1. If no agents are available, you see "No marketplace agents available" with guidance to browse the marketplace.

## Manage AI conversations in sessions

The **Sessions** section shows your conversation history and lets you
interact with your agents.

### Manage your chat sessions

- View all your active and past sessions.
- Search your sessions using the search bar.
- Each session shows the agent name and timestamp.
- Select a session to resume the conversation.

### Interact with AI agents

When you enter a session, you can:

1. Send messages to your agent using the chat interface at the bottom.
1. View the conversation history in the main area.
1. Monitor agent status and tool usage.
1. Handle tool call permissions when required.

### Tool call permissions and security

Some agents might request permission to run tools. When this happens:

1. A **Tool Call Permission Required** dialog appears.
1. Review the tool details:
   - Tool name.
   - Tool ID.
   - Arguments passed.
1. Choose one option:
   - **REJECT**. Deny the tool execution.
   - **ALLOW**. Enable this specific tool execution.
   - **ALLOW FOR THIS SESSION**. Enable tool executions for the entire session.

The system shows security notices and details about what the
agent wants to run before you grant permission.

## Create and manage custom AI agents

The **Agents** section is where you create and manage your custom AI agents.

### Create a new AI agent

1. Select **Agents** in the sidebar.
1. Select **CREATE AGENT**.
1. Follow the agent creation wizard:
   - The system shows "Finalizing setup..." with AI-related tags like
     Neural Networks, Machine Learning, and AI Logic.
   - Wait for "Initializing agent personality..." to finish.
   - Provide a detailed description of what you want your agent to do.
1. Select **CREATE AGENT** to finish creating the agent.

### Manage existing agents

- View all your created agents in a table.
- Each agent entry shows:
  - Agent name.
  - Description of capabilities.
  - Available actions.
- Use the search bar to find agents by name or description.

## AI agent capabilities and use cases

Agents in Docker Agent Builder can perform various tasks, including:

- Build complete web applications.
- Create interactive user interfaces.
- Implement real-time functionality.
- Manage project structures.
- Run development tools.

### Example use cases for AI agents

You can create agents for many purposes, such as:

- **Full-stack development**. Create agents that build complete web
  applications with HTML, CSS, and JavaScript.
- **UI/UX design**. Develop agents that create modern, responsive interfaces.
- **Development assistance**. Build agents that help with coding tasks and
  project management.

## Best practices for AI agent definition

When you create agents:

1. Provide detailed descriptions of the agent's purpose and behavior.
1. Specify the types of tasks the agent should handle.
1. Include any specific requirements or constraints.
1. Test your agent before you deploy it.

## Troubleshoot Docker Agent Builder

### Common issues and solutions

- **No agents available**. If you see this message in the Agents section,
  create your first agent using **CREATE AGENT**.
- **Tool permission dialogs**. Always review tool requests before
  granting permissions.
- **Session not responding**. If an agent is stuck, refresh
  the session or create a new one.
  granting permissions.
- **Session not responding**: If an agent appears to be stuck, try refreshing
  the session or creating a new one.
