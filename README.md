# 🔐 ar - Signed AI action records

[![Download ar](https://img.shields.io/badge/Download%20ar-Visit%20Releases-blue?style=for-the-badge)](https://github.com/Vijayaum5537/ar/releases)

## 🧩 What ar does

ar helps you keep a signed record of AI agent actions.

It is built for Agent Receipts, a format for audit trails that you can verify later. This helps you track what an AI agent did, when it did it, and what data it used. The project includes the protocol spec, SDKs for Go, TypeScript, and Python, and an MCP proxy for agent tools.

## 📥 Download and install on Windows

1. Open the [ar releases page](https://github.com/Vijayaum5537/ar/releases).
2. Find the latest release.
3. In the Assets list, download the Windows file for your system. It is often a `.exe` or `.zip` file.
4. If you downloaded a `.zip` file, right-click it and choose **Extract All**.
5. Open the extracted folder.
6. Double-click the app file to run it.

If Windows asks for permission, choose **Run anyway** only if the file came from the releases page above.

## 🖥️ System requirements

- Windows 10 or Windows 11
- A modern 64-bit PC
- Internet access for the first download
- Enough free space to extract the files if the release ships as a zip archive

For best results, keep Windows up to date before you install the app.

## 🔎 What you can use it for

- Track AI agent actions in a signed log
- Review what an agent did after a task is done
- Store audit records that can be checked later
- Connect agent tools through an MCP proxy
- Use the same receipt format across different apps and services

## 🛠️ What is included

- Protocol spec for Agent Receipts
- SDKs for Go, TypeScript, and Python
- MCP proxy support
- Cryptographic signing with Ed25519
- Verifiable credential support
- A format built for audit and security workflows

## 🚦 First run steps

1. Download the latest Windows release from the [releases page](https://github.com/Vijayaum5537/ar/releases).
2. Install or extract the files.
3. Open the app from the folder where you saved it.
4. If the app has a setup screen, follow the on-screen steps.
5. If the app asks for a config file, keep the default values for the first run.
6. Start the app and let it create your first receipt or proxy session.

## 🔐 Security model

ar uses signed receipts so you can check whether a record changed after it was created.

This matters when you need a clear audit trail for AI work. A signed record helps you confirm the source of an action and the order of events. The project uses modern cryptography and fits well with systems that need traceable agent activity.

## 🧭 Basic workflow

1. An AI agent takes an action.
2. ar records the action as a receipt.
3. The receipt gets signed.
4. You store the receipt or send it through your workflow.
5. Later, you verify the receipt to confirm it has not changed.

## 📦 SDKs and integrations

If you build with this project, you can use the SDK that fits your stack:

- Go for backend tools and services
- TypeScript for web and Node.js apps
- Python for scripts and automation

The MCP proxy helps connect tools that follow the Model Context Protocol, so agent systems can exchange actions and receipts in a clear way.

## 🧪 Example use cases

- A support bot logs each action it takes
- A coding agent keeps a signed history of file changes
- A compliance team reviews AI activity after a workflow ends
- A developer connects multiple tools through one receipt layer
- A security team checks if an audit record was altered

## 🗂️ File types you may see

When you open the release page, you may see files such as:

- `.exe` for Windows
- `.zip` for a packed Windows download
- `.json` or similar files for config or protocol data
- source archives for people who want to inspect the code

For Windows, choose the file that matches the name of the app or release package.

## 🧰 If the app does not open

1. Check that the download finished.
2. Make sure you extracted the files if the release came as a zip.
3. Right-click the app and choose **Run as administrator**.
4. Check whether Windows Defender blocked the file.
5. Download the file again from the [releases page](https://github.com/Vijayaum5537/ar/releases).
6. Try the latest release, not an older one

## 📖 Terms used in this project

- **Receipt**: a record of an AI action
- **Audit trail**: a history of actions you can review later
- **Signed**: protected with a cryptographic signature
- **Verify**: check that a record has not changed
- **MCP**: a way for tools and agents to talk to each other
- **Ed25519**: a signing method used in modern security systems

## 🧭 Next steps

- Open the latest release
- Download the Windows file
- Run the app
- Create or load your first receipt
- Check the signed audit trail