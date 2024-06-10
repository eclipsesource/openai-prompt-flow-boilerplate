# OpenAI Prompt Flow Boilerplate (Node.js)

This repository serves as a basic Node.js boilerplate for experimenting with or starting to implement a prompt flow using OpenAI. It's a great starting point for developers looking to test and automate certain tasks using OpenAI's language models.

## Setup

Before you start, you need to add a `.env` file at the root of the project. This file should contain your [OpenAI API key](https://platform.openai.com/docs/quickstart/account-setup):

```env
OPENAI_API_KEY=<your_openai_api_key>
```

Replace `<your_openai_api_key>` with your actual OpenAI API key.

## Building the Project

To build the project, you need to install the dependencies first. Run the following command:

```sh
npm install
```

After the dependencies are installed, you can build the project using:

```sh
npm run build
```

## Debugging

This project comes with a pre-configured debug configuration in the [`.vscode/launch.json`](.vscode/launch.json) file. This allows you to start a debugging session right from your Visual Studio Code.

Before launching the debugger, make sure you have built the project using `npm run build`. The debugger will launch the program defined in `${workspaceFolder}/src/index.ts`.

The `preLaunchTask` named "Build" refers to a task defined in the [`.vscode/tasks.json`](.vscode/tasks.json) file, which runs the `build` script before launching the debugger.
