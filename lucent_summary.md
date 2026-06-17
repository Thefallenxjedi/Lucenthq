# Lucent: Comprehensive Overview

**Lucent** is a product analytics and debugging platform that utilizes AI to watch every session replay, catch bugs, and automatically surface product insights. Its core mission is to help teams understand what is *really* happening in their product without the pain of manually watching session recordings.

---

## The Problem Lucent Solves

With modern AI, code velocity is no longer the primary bottleneck for engineering teams—understanding users and catching bugs in rapidly shipped features is. Traditional methods like relying on error trackers (e.g., Sentry) or manually reviewing occasional session recordings often miss critical UI/UX issues, silent failures, and user friction points. 

Lucent automates session replay review. It acts as an automated tester and dogfooding tool that finds everything from critical production bugs to minor UX paper cuts across different devices and screen sizes.

---

## Core Capabilities

Lucent breaks down its offering into six main pillars:

### 01. Insights
See patterns across all your user sessions instead of reviewing them one by one.
- **Weekly Reports**: Receive automated weekly summaries detailing:
  - Which parts of your app are working well (e.g., high engagement flows).
  - Which parts are problematic (e.g., authentication blocks, onboarding drop-offs).
  - Actionable priorities for your product and engineering teams.

### 02. Detection
Get alerts the moment your users hit issues—before they churn.
- Detects actual bugs and UX friction points automatically.
- **Examples of issues caught**:
  - Infinite page refresh loops.
  - Users unable to upgrade due to hidden validation errors.
  - Forms losing data when the user hits "back" or submitting silently.
  - Users "rage-clicking" disabled buttons or dropdowns closing unexpectedly.

### 03. Debugging
Every detected issue comes with a detailed, automatically generated bug report containing full context so engineers can fix bugs fast.
- **Report Context Includes**:
  - Exact steps to reproduce.
  - Direct link to the session replay.
  - Console logs, network requests, and events.
  - Issue severity (e.g., High, Medium).
  - Number of affected users.
  - Browser and device information (e.g., Safari iOS 17).

### 04. Signals
Monitor specific user behaviors using natural language.
- Describe a signal you want to track (e.g., *"Users who clicked Upgrade to Pro but didn't complete checkout"*).
- Lucent scans past and future sessions to extract all matching session replays.
- Useful for tracking users showing upgrade intent, testing new features, or searching for missing capabilities.

### 05. Impact
Understand the real blast radius of any given issue.
- See a comprehensive list of every single user who hit a specific bug.
- View affected users' emails and when they encountered the issue.
- **Close the loop**: Notify all affected users once you ship the fix to show them you care about their experience.

### 06. Integrations & MCP (Model Context Protocol)
Lucent works where you already work. 
- **Analytics Integrations**: Connect seamlessly with **PostHog**, **Amplitude**, or **Datadog**.
- **Workflow Integrations**: Send bug reports straight to **Slack**, **Gmail**, or **Linear**.
- **MCP Clients**: Query your issues, signals, and insights directly from AI coding assistants and chatbots like **Claude Code**, **Cursor**, **ChatGPT**, and **Windsurf** via MCP.

---

## How Lucent Works Under the Hood

### 1. Record
Lucent captures everything happening in the browser.
- **The SDK**: If you aren't using an existing analytics provider, you can install `@lucenthq/sdk` (a lightweight rrweb-based recorder).
- **What it captures**: DOM mutations, clicks, inputs, console output, and network calls.
- **Privacy First**: By default, the SDK masks all text to ensure sensitive user data is kept private.

### 2. Ingest
Events are batched in the browser and flushed asynchronously to Lucent's ingest API, where sessions are stored immutably.

### 3. Analyze
Lucent evaluates sessions for rage clicks, dead clicks, and navigation friction. It then runs an AI analysis pass over each session to explain *why* a session went sideways and surface the issues that actually matter.

### 4. Act
Review signals in the dashboard, share links with your team, or pipe issues directly into your issue tracker.

---

## Setup & Installation

You can get started with Lucent in under a minute using one of two methods:

- **Option A (No Code)**: Link your existing **PostHog**, **Amplitude**, or **Datadog** account. Lucent starts analyzing your existing replays in 30 seconds with zero code changes required.
- **Option B (SDK Quickstart)**: Drop one line of code (`npx @lucenthq/cli init`) into any web framework to start recording sessions.

> *Lucent offers 400 sessions free to start, with no credit card required.*
