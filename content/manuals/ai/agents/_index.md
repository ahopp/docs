---
title: Docker Agent Builder
description: Create, manage, and share AI agents with Docker Agent Builder. Build custom AI agents, discover community agents, and manage interactive chat sessions.
keywords: ai agents, agent builder, marketplace, chat sessions
params:
  sidebar:
    badge:
      color: blue
      text: Beta
    group: AI
weight: 20
---

Docker Agent Builder is a comprehensive platform for creating, managing, and
sharing AI agents. Build custom AI agents, discover community-created agents,
and manage interactive chat sessions with an intuitive interface.

## Prerequisites

Before using Docker Agent Builder, ensure you have the following requirements:

- **Docker Desktop**: Install Docker Desktop and ensure you're logged in to
  your Docker account.
- **API keys**: Both OpenAI and Anthropic API keys are required.

  - **OpenAI API key**: Visit
     [OpenAI API Keys](https://platform.openai.com/settings/organization/api-keys)
     to create your key.
  - **Anthropic API key**: Visit
     [Anthropic Console](https://console.anthropic.com/settings/keys) to create
     your key.

-  Once you have both API keys, add them to your shell configuration file:

   ```bash
   export OPENAI_API_KEY=your_openai_key_here
   export ANTHROPIC_API_KEY=your_anthropic_key_here
   ```

## Getting started with Docker Agent Builder

The application consists of the following sections:

- **Agents**: Create and manage your custom AI agents
- **Sessions**: View and manage your active conversations with agents
- **Marketplace**: Discover and download AI agents from the community
- **Settings**: Configure your application preferences

## Agent marketplace

The **Marketplace** section enables you to discover and download AI agents
created by the community and offers the following features:

- Browse available agents from the community.
- Search for agents by name or description.
- Pull agents directly from Docker Hub.
- View agent descriptions and capabilities.

### Using the Marketplace to find agents

1. Select **Marketplace** in the sidebar navigation.
1. Browse the available agents or use the search functionality:
   - Use the "Pull an agent from Docker Hub" search bar to import specific
     agents.
   - Use the "Search marketplace agents by name or description" field to find
     relevant agents.
1. When no agents are available, you'll see the message "No marketplace agents
   available" with guidance to browse the marketplace to discover AI agents
   created by the community.

## Sessions: Manage AI conversations

The **Sessions** section displays your conversation history and enables you to
interact with your agents.

### Managing your chat sessions

- View all your active and past sessions.
- Search through your sessions using the search bar.
- Each session shows the agent name and timestamp.
- Select a session to resume the conversation.

### Interacting with AI agents

When you enter a session, you can:

1. Send messages to your agent using the chat interface at the bottom.
1. View the conversation history in the main area.
1. Monitor agent status and tool usage.
1. Handle tool call permissions when required.

### Tool call permissions and security

Some agents might request permission to execute tools. When this happens:

1. A "Tool Call Permission Required" dialog appears.
1. Review the tool details including:
   - Tool name.
   - Tool ID.
   - Arguments being passed.
1. Choose from three options:
   - **REJECT**: Deny the tool execution.
   - **ALLOW**: Allow this specific tool execution.
   - **ALLOW FOR THIS SESSION**: Allow tool executions for the entire session.

The system provides security notices and detailed information about what the
agent wants to execute before you grant permission.

## Agents: Create and manage custom AI agents

The **Agents** section is where you create and manage your custom AI agents.

### Creating a new AI agent

1. Select **Agents** in the sidebar navigation.
1. Select the **CREATE AGENT** button.
1. Follow the agent creation wizard:
   - The system shows "Finalizing setup..." with AI-related tags like
     Neural Networks, Machine Learning, and AI Logic.
   - Wait for "Initializing agent personality..." to complete.
   - Provide a detailed description of what you want your agent to do.
1. Select **CREATE AGENT** to finalize the agent creation.

### Managing existing agents

- View all your created agents in a table format.
- Each agent entry shows:
  - Agent name.
  - Description of capabilities.
  - Available actions.
- Use the search bar to find specific agents by name or description.

## AI agent capabilities and use cases

Agents in Docker Agent Builder can perform various tasks, including:

- Building complete web applications.
- Creating interactive user interfaces.
- Implementing real-time functionality.
- Managing project structures.
- Executing development tools.

### Example use cases for AI agents

The system supports creating agents for various purposes, such as:

- **Full-stack development**: Create agents that can build complete web
  applications with HTML, CSS, and JavaScript.
- **UI/UX design**: Develop agents that create modern, responsive interfaces.
- **Development assistance**: Build agents that help with coding tasks and
  project management.

## Best practices for AI agent definition

When creating agents:

1. Provide detailed descriptions of the agent's purpose and behavior.
1. Specify the types of tasks the agent should handle.
1. Include any specific requirements or constraints.
1. Test your agent thoroughly before deploying.

## Troubleshooting Docker Agent Builder

### Common issues and solutions

- **No agents available**: If you see this message in the Agents section,
  create your first agent using the **CREATE AGENT** button.
- **Tool permission dialogs**: Always review tool requests carefully before
  granting permissions.
- **Session not responding**: If an agent appears to be stuck, try refreshing
  the session or creating a new one.
