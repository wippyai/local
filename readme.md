# Wippy Local

<p align="center">
    <a href="https://wippy.ai" target="_blank">
        <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://github.com/wippyai/.github/blob/main/logo/wippy-text-dark.svg?raw=true">
            <img width="30%" align="center" src="https://github.com/wippyai/.github/blob/main/logo/wippy-text-light.svg?raw=true" alt="Wippy logo">
        </picture>
    </a>
</p>

<div align="center">

[![Latest Release](https://img.shields.io/github/v/release/wippyai/portable?style=for-the-badge)][releases]
[![Downloads](https://img.shields.io/github/downloads/wippyai/portable/total?style=for-the-badge)][releases]

</div>

Wippy Local is a desktop application that brings AI agent collaboration securely to your computer. Run multi-agent AI workflows locally with full privacy and control over your data. The platform evolves with your needs - agents can enhance capabilities and create new tools with your approval, building a personalized AI environment that grows more powerful over time.

<div align="center">
<a href="https://github.com/wippyai/portable/releases">
<img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge&logo=download&logoColor=white" alt="Download Latest Release">
</a>
</div>

## Screenshots

<img width="2878" height="1895" alt="image" src="https://github.com/user-attachments/assets/d2edd8c2-8110-4df5-a5c4-39a1dbcde2fa" />
<img width="2786" height="1384" alt="image" src="https://github.com/user-attachments/assets/f0583d7d-9ede-4bf8-900d-26101812e301" />

## Installation

### Requirements

- **Windows**: Modern Windows versions
- **macOS**: Recent macOS versions  
- **AI API Keys**: [OpenRouter](https://openrouter.ai/) key required, OpenAI key optional (necessary for knowledge base embeddings)

### Quick Start

1. **Download** the latest release for your platform from the [releases page][releases]
2. **Install and Run** the application
3. **Configure** your API keys when prompted - see the built-in tutorials for detailed setup instructions

**Linux builds** are coming in future releases.

### How to get your OpenRouter API key

1. Sign in at openrouter.ai
2. Open Account → API Keys
3. Click Create API Key, give it a name, and optionally set a credit limit

> Wippy is provider-agnostic. Use OpenRouter if you like, or plug in Anthropic, OpenAI, or local models. You can change providers per environment or workflow.

## Features

Wippy provides a complete AI agent platform designed for personal and professional use:

**AI Agent Framework**
- Multi-agent coordination with specialized roles
- Intelligent task delegation between agents  
- Persistent conversation sessions with context preservation
- Dynamic agent selection based on task requirements

**Knowledge Management**
- Local knowledge bases for document storage and retrieval
- File upload and processing (PDF, Word, images, text)
- Searchable content accessible to authorized agents
- Cross-session information persistence

**Project Organization** 
- Structured workflows for complex tasks
- Project templates with coordinated agent teams
- Session continuity across multiple work periods
- Progress tracking and milestone management

**System Integration**
- External service connections and API integrations
- OAuth and credential management
- Plugin architecture for extensibility
- Real-time data synchronization

**Extensible Architecture**
- Plugin system for adding new capabilities
- Integration with external services and APIs
- Custom tool creation and workflow automation
- Controlled system enhancement with user approval

**Local Operation**
- Complete privacy - all data stays on your machine
- No internet required except for AI model access
- Local SQLite database for data storage
- Offline knowledge base operations

## Frequently Asked Questions

### What is Wippy?

Wippy is an integrated application platform where you can change and replace approximately 99% of the codebase from inside Wippy itself at runtime. It's a complete application operating system designed for AI agents to live, develop, and improve within a unified system.

### Can Wippy work completely locally?

Yes, Wippy can work completely locally on your machine. When working locally, Wippy does not collect any information or statistics from your installation. All your data remains on your computer.

### Do I need to know programming to use Wippy?

You don't need to be a programmer to work with Wippy, but having a structured approach is helpful. Wippy is designed to be accessible to non-technical users through its AI agent interface.

### How do I start using Wippy effectively?

Start small with simple tasks. Begin by exploring the interface and uploading your first file or creating a basic project. Don't try to handle complex projects all at once - use an iterative approach starting with a research phase and testing connections step by step.

### What file types does Wippy support?

Wippy supports documents (PDF, Word, PowerPoint), images (JPG, PNG, GIF), and text files. In this alpha version, document processing happens through our cloud service, but the content is not retained after processing - everything is stored locally.

### Can Wippy integrate with external services?

Wippy connects to LLM model providers based on your configuration and can integrate with anything that has an API or create APIs for other platforms to connect to it. We will provide modules for Discord, Slack, and other integrations in future releases.

### Is Wippy scalable for team use?

While this build is intended for personal use on your personal machine, the same agent architecture is used in production for multiple organizations. If you're interested in team-based or commercial use of Wippy, please contact [Spiral Scout](https://spiralscout.com).

### What makes Wippy different from other AI frameworks?

Wippy is not just an application framework - it's a fully integrated application operating system designed for agents to live, develop, and improve within a unified system. All of this runs within a single binary. The closest comparison would be a mix between BabyAGI and Erlang OTP, specifically designed for AI agents with a governance pipeline on top.

### Will Wippy receive updates?

On every application start, we check for recent modular updates and install them for you. We don't update your application state or custom builds - those remain yours.

## Issues and Support

For bug reports and feature requests, visit the [issues page](https://github.com/wippyai/portable/issues).

## License

Wippy Local is released under the [Apache 2.0 License](LICENSE).

## Maintained By

Wippy is maintained by [Spiral Scout](https://spiralscout.com).

[releases]: https://github.com/wippyai/portable/releases
