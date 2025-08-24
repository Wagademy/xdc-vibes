# XDC Vibe Coding Bootcamp

Welcome to the XDC Vibe Coding Bootcamp! This bootcamp is designed to take you from idea to a deployed dApp on the XDC Network. Over three days, you will learn how to build with AI agents and stablecoin payments.

If you are interested in participating in this bootcamp, please register on the [Luma page](https://lu.ma/xdc-vibes).

## Bootcamp Schedule

*   **Stage 1: Vibe.** (August 27, 2025 @ 6PM EDT): [Register Here](https://lu.ma/xdc-vibe)
*   **Stage 2: Craft.** (August 28, 2025 @ 6PM EDT): [Register Here](https://lu.ma/xdc-craft)
*   **Stage 3: Deploy.** (August 29, 2025 @ 6PM EDT): [Register Here](https://lu.ma/xdc-deploy)
*   **Project Submission Deadline:** September 01, 2025 @ 12AM EDT: [Submit Here](https://forms.gle/gPcamFZP4jQknxRaA)
*   **Pitch Day:** September 04, 2025 @ 6PM EDT: [Register Here](https://lu.ma/xdc-vibe-pitch)

## What You Will Learn

*   Setting up the environment for Vibe Coding and blockchain development
*   The core concepts of deploying a smart contract on XDC Network
*   AI-powered development
*   Using a self-custodial crypto wallet with the XDC Network
*   Launching a dApp to handle token transactions

## Lesson Plan

### Day 1: Vibe - Building a Landing Page

*   **Learning Objectives:**
    *   Understand the basics of a landing page and its purpose.
    *   Learn how to use v0.app to quickly generate landing page designs.
    *   Successfully create a simple landing page for a sample idea using v0.app.
*   **Activities:**
    *   Introduction to Landing Pages (15 minutes)
    *   Exploring v0.app (15 minutes)
    *   Hands-on Landing Page Creation (40 minutes)
    *   Publishing the website live
    *   Q&A and Next Steps (20 minutes)
*   **Homework:**
    *   Create a landing page for your own sample idea using an AI design tool.
    *   Take care of the Pre-reqs for the next session.

### Day 2: Craft - Scaffold-ETH Setup & XDC Integration

*   **Learning Objectives:**
    *   Gain an understanding of Scaffold-ETH for rapid dApp development.
    *   Learn to use the Scaffold-ETH starter kit for any EVM compatible chain.
    *   Understand how to configure XDC Network integrations within Scaffold-ETH.
*   **Activities:**
    *   Review of Day 1 & Q&A (5 minutes)
    *   Introduction to Scaffold-ETH (30 minutes)
    *   Configuring XDC Network Integrations (15 minutes)
    *   Getting started with the XDC Network (30 minutes)
*   **Homework:**
    *   Get XDC testnet tokens.
    *   Deploy the test Smart Contract.
    *   Study the interactions in the “Debug” page.

### Day 3: Deploy - Building and Launching a dApp

*   **Learning Objectives:**
    *   Implement payments for the launchpad smart contract.
    *   Implement a page to buy the token in the launchpad with USDC.e.
*   **Activities:**
    *   Explaining the ERC20 smart contract (30 minutes)
    *   Implementing the “buy tokens” in the landing page (30 minutes)
    *   Deploying the app with Vercel (10 minutes)
    *   Q&A Session (10 minutes)
    *   Prep to deploy in mainnet and submission (10 minutes)
*   **Homework:**
    *   Deploy the launchpad project to mainnet.
    *   Build your final project.

## Project Submission and Pitch Day

*   **Judging Criteria:**
    *   Participate in the 3 Stages (LuMa registered).
    *   Submit by September 01, 2025 @ 12 AM EDT.
    *   Post your project on X and tag: @xdc_community, @ventureminer, @cracked_labs.
    *   Meets Project Criteria:
        *   Unique idea (focus on Stablecoins, DeFi, or Payments get judging preference).
        *   Created during this bootcamp.
        *   Solves a real-world problem.
        *   Integrates XDC Network, smart contracts, oracle, other.
        *   Project is Deployed on mainnet.

*   **Prizes:**
    *   1st: $500 USD
    *   2nd: $300 USD
    *   3rd: $200 USD

*Awards are paid out in $XDC (*equivalent $USD).*

> To participate, submit your project [by filling this form](https://forms.gle/gPcamFZP4jQknxRaA) before **September 01, 2025 @ 12 AM EDT**.

## Pre-read Materials

*   **XDC Chain Docs:** Introduction documentation - [http://docs.xdc.network/xdcchain/](http://docs.xdc.network/xdcchain/)
*   **Quick Tools Guide:** Tools for starters - [https://xinfin.org/quick-tools-guide](https://xinfin.org/quick-tools-guide)
*   **Apothem RPC:** Testnet network configuration - [https://docs.xdc.network/xdcchain/developers/apothemrpc/](https://docs.xdc.network/xdcchain/developers/apothemrpc/)

## Environment Setup

This guide will help you set up the necessary tools for the bootcamp. Please follow the instructions for your operating system.

### 1. Terminal (Command Line)

The terminal is a tool that allows you to interact with your computer using text commands. It's an essential tool for developers.

*   **Windows:** You can use PowerShell or the Command Prompt, which come pre-installed. For a better experience, we recommend installing the [Windows Terminal](https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701) from the Microsoft Store.
*   **macOS:** The Terminal app is located in the `Utilities` folder within your `Applications` folder.
*   **Linux:** You can usually open the terminal by pressing `Ctrl+Alt+T` or by searching for "Terminal" in your applications.

### 2. Basic Navigation Commands

Here are a few basic commands to help you navigate your file system in the terminal:

*   `cd <folder_name>`: Change directory (e.g., `cd Documents`).
*   `mkdir <folder_name>`: Create a new folder (e.g., `mkdir my-project`).
*   `ls` (macOS/Linux) or `dir` (Windows): List the files and folders in the current directory.

### 3. Install Git

Git is a version control system that helps you track changes in your code.

*   **Windows:** Download and install Git from [git-scm.com/download/win](https://git-scm.com/download/win).
*   **macOS:** The easiest way to install Git is to install the Xcode Command Line Tools. Open your terminal and run `git --version`. If you don't have it, it will prompt you to install it.
*   **Linux:** You can install Git using your distribution's package manager. For example, on Debian/Ubuntu, run `sudo apt install git-all`.

### 4. Install Node.js and npm

Node.js is a JavaScript runtime, and npm is the Node.js package manager. You'll need these to run your dApp.

1.  Go to the [Node.js download page](https://nodejs.org/en/download/).
2.  Download the **LTS (Long-Term Support)** version for your operating system.
3.  Run the installer and follow the on-screen instructions.
4.  To verify the installation, open your terminal and run the following commands:
    ```bash
    node -v
    npm -v
    ```

### 5. Enable Corepack for Yarn

Yarn is another package manager that we'll use. Corepack is a tool that comes with Node.js to manage package managers.

1.  Open your terminal and run the following command to enable Corepack:
    ```bash
    corepack enable
    ```

Now you're all set up and ready for the bootcamp!

## Instructor

**Matheus Pagani**, CEO of [Venture Miner](https://ventureminer.com), brings over a decade of experience in AI, blockchain, and innovation, with a strong background in guiding thousands of developers through specialized bootcamps.


## Contact

If you have any questions, feel free to join our [Telegram Channel](https://t.me/vmineracademy) for community support and troubleshooting.