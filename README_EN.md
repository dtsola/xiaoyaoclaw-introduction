# XiaoyaoClaw · Product Introduction

**English** | [简体中文](README.md)

![XiaoyaoClaw](运营文档/产品宣传图.png)

---
## User Community & Feedback Group

Scan the QR code to join the **Xiaoyao AI · XiaoyaoClaw Product Community** — product feedback, usage discussions, and feature suggestions (for users).

![Xiaoyao AI XiaoyaoClaw Product Community](运营文档/小遥Claw产品交流群图.png)

---

## Introduction

**XiaoyaoClaw is a desktop-first, local AI assistant management platform.**

Put an AI assistant on your own computer — one installer, one icon, one QR-code login, and you can deploy the same AI assistant to multiple instant messaging platforms at once: Feishu (Lark), Slack, Discord, WeChat, Telegram, DingTalk, QQ, WeCom (Enterprise WeChat), WhatsApp, and more. It can actually read Feishu spreadsheets, check calendars, create tasks, and write issues — a real AI assistant for your daily work.

### What Makes Us Different

| Other AI assistant tools | XiaoyaoClaw |
|-----------------|-------------|
| Data is uploaded to the cloud and controlled by someone else | **Local-first**: configs, chat history, and API keys all stay on your computer |
| Every platform needs its own login and its own subscription | One app connects 9 major IMs — **one subscription covers them all** |
| Feishu only allows one app; multiple teams mean multiple accounts | **Multiple instances per platform** — run 6 Feishu bots in parallel |
| The AI can only talk, not get things done | Built-in **Skill Center**: the AI reads spreadsheets, checks calendars, creates tasks, writes issues |
| Switching models means editing config files | **Hot-swappable models** — one click in the UI, effective immediately |

![XiaoyaoClaw main UI](产品文档/产品截图/主界面.png)

> The screenshot above is the real, running XiaoyaoClaw main console: on the left is the chat & session navigation (24 skills loaded); the main area shows the current bot status (`xiaoyaoclaw` / `deepseek-v4-flash` / 368 messages today), 1 connected WeChat instance and 6 Feishu instances, plus the recent activity stream.

---

## Why I Can Say All This: I'm the Developer, and a Heavy User

I am both its developer and its user:

- I've been using it **every day throughout development**, for several months straight;
- It went through a one-month private beta — every feature was polished through real usage;
- If you run into any problem, you can **talk to me, the developer, directly** — no support bots, no ticket system. The person on the other end is the one who wrote the code.

### The Fundamental Difference from Big-Tech Apps

Many AI assistant apps on the market are built by big companies imagining what "office workers" need — the developers themselves may never use the product; requirements come from surveys and guesswork. Every feature of XiaoyaoClaw, however, is something I use every day as a real user:

- I know which scenarios are real pain points and which are merely pseudo-needs;
- I know whether a feature works well — not from dashboards and reports, but from whether it feels right in my own hands;
- A different depth of usage makes a different product.

**In one sentence: others build it "for you to use"; I build it "for myself to use — and you're welcome to use it too."**

---

## Who It's For

### 🧑‍💼 Solo Founders / Indie Developers / Entrepreneurs
Core pain points: **customer maintenance & acquisition** (omnichannel support, community operations) + **product building & delivery** (requirement tracking, dev collaboration). They want a single AI assistant connected to every customer channel — Feishu / Slack / WeChat / Discord — while it also helps handle GitHub Issues and PR drafts. Once these **real workflows run smoothly, they settle into reusable, repeatable workflows** you can simply invoke the next time — freeing the saved time for the product itself.

### 🎨 Content Creators / Media Teams
The full pipeline of **topic hunting → content creation → scheduling → multi-platform distribution → data collection**. They want AI collaborating directly inside their creative toolchain, automating the repetitive steps of every stage so people can focus on creating.

### 📊 Product Managers / Internet Operators
Daily work is dominated by **repetitive processes**: drafting PRDs, categorizing user feedback, debating requirement priorities, compiling reports, reviewing campaign data. They want AI to run these inside the Feishu / DingTalk / WeCom they already use, so they can focus on product judgment and strategy.

### 💼 Office Workers / Efficiency-Focused Users
Regular employees who want to speed up both **daily office work** (weekly reports / emails / schedules / tasks / docs) and **daily learning** (research reports / papers / notes). They want AI as an assistant right inside the Feishu / WeChat / DingTalk / WeCom they already use: one-sentence weekly reports, automatic key-point extraction from research reports, cross-IM history search — upgrading everyday **bookmarks, notes, and chat history into a searchable knowledge system** you can actually find things in later. And they don't want to learn yet another new tool just for AI, let alone let company data go into a SaaS.

---

## Use Scenarios

### Scenario 1 · A Solo Company's "Every Customer Channel Open"
An indie developer's customers are scattered across Feishu / WeChat / Slack / Discord. With XiaoyaoClaw, **create one bot, configure an instance for each channel**, and all customer inquiries converge into a single timeline in the main console — no more switching back and forth, nothing gets missed.

### Scenario 2 · A Solo Company's "Dev Collaboration That Never Drops"
You maintain a GitHub repo plus a Feishu work group. The bot enables the **`gh-issues` + `coding-agent` skills** — GitHub Issues roll up into the bot console, the AI drafts PR descriptions, and developers only fill in the implementation points.

### Scenario 3 · A Creator's "From Idea to Distribution in One Flow"
A creative team on a workday. The bot is bound to the creative work group and enables the Feishu collaboration skill set (**Sheets / Calendar / Docs**) — **one sentence of inspiration in the group gets organized into the topic bank in a Feishu sheet, drafting is assisted, first-draft schedules are pushed to the calendar, and post-publish data flows back into the same sheet**. People focus on the creating itself.

### Scenario 4 · A PM / Operator's "Feedback Triage + Docs That Land"
A PM is bombarded daily by user feedback from a dozen groups, and after every campaign still has to write the retrospective and draft the PRD. The bot joins the product feedback groups and enables the **`deep-research` skill** — the AI categorizes and organizes the feedback; after a campaign, the AI drafts the retro doc and pushes it to Feishu; the PRD skeleton is drafted by the AI, and the PM only edits the judgment calls.

### Scenario 5 · An Office Worker's "Chores and Learning, Both Faster"
A regular employee's daily high-frequency routine. The bot binds **Feishu + WeCom + WeChat**:
- **Daily office work**: on the weekend, one sentence and the AI produces the weekly report (summarizing Feishu / emails / group messages); schedule-conflict reminders; search for any historic message across IMs, anytime.
- **Daily learning**: the AI extracts key points from research reports / papers; notes are archived automatically.

---

## Quick Start (WeChat Example)

Just three steps take you from opening the app to chatting with your AI assistant.

### Step 1: Add a Model

In the desktop app, go to **Settings → AI Model Providers**, pick an AI provider and enter its API key. Here we use **DeepSeek** as the example — after filling in the key, switch the default model to `deepseek-v4-flash`:

![Settings - Model settings](产品文档/产品截图/设置-模型设置.png)

### Step 2: Add a WeChat Channel

Back on the home page, create a new instance for "WeChat" in the Channels area; a QR-code connection dialog pops up. Enter the Bot ID (e.g. `xiaoyao` — auto-created if it doesn't exist), then scan the code with WeChat on your phone:

![Channel - Add WeChat instance](产品文档/产品截图/渠道-添加微信实例-01.png)

### Step 3: Chat with Your AI Assistant

Open WeChat on your phone and send a message to the bot you just bound — the AI assistant's reply arrives right in WeChat, introducing itself as "powered by XiaoyaoClaw":

![First conversation](产品文档/产品截图/渠道-添加微信实例-初次对话-02.png)

> ✅ **Your AI assistant is up and running.** Connecting Feishu / Slack / Discord and other channels works exactly the same way: pick a channel → scan → chat.

---

## More Scenarios, One Click to Copy

The 3 steps above only demonstrate the **WeChat** path. XiaoyaoClaw + the Shrimp-Raising Library also ships with **8+ ready-to-use, high-value scenarios** — customer response / dev collaboration / content creation / knowledge building / office speed-up / learning digestion. Pick one to run first, then expand once it runs smoothly.

---

## CTA · Try It Now

Installers for all platforms are distributed via Baidu Netdisk:

- **Link**: <https://pan.baidu.com/s/1H3PrTdp0ShBe7upnAO12mQ>
- **Code**: `7z69`

### Choosing the Right Installer

Open the netdisk and download the file matching your device. File names follow this format:

| Device | File name format | Example |
|------|-----------|------|
| macOS · Apple Silicon (M-series chips) | `XiaoyaoClaw-{version}-arm64.dmg` | `XiaoyaoClaw-1.0.11-arm64.dmg` |
| macOS · Intel chips | `XiaoyaoClaw-{version}-x64.dmg` | `XiaoyaoClaw-1.0.11-x64.dmg` |
| Windows · 10/11 x64 | `XiaoyaoClaw-Setup-{version}.exe` | `XiaoyaoClaw-Setup-1.0.11.exe` |

> 💡 **How to tell which chip your Mac has**: click the  menu at the top-left corner → "About This Mac" → look at the "Chip" line — `Apple M1/M2/M3/...` means Apple Silicon; anything starting with `Intel` is an Intel chip.

### Install & First Login

1. After downloading, **double-click the installer** (`.dmg` on macOS, `.exe` on Windows).
2. On first launch after installation you'll be asked to log in — just register an account (**registration code: xsqexjtdi8, limited to 200 users**)

   **Join the group to claim** 🎁 **the complete "Shrimp-Raising Library" tutorial pack** — the OpenClaw beginner's pitfall guide / what to do after installing / the shrimp-raising playbook, the personal knowledge-base building series (3 parts), and the AI Skills workflow packs (Basic + Enhanced) — 8 items in total:

   ![Shrimp-Raising Library](产品文档/产品截图/xiaoyaoclaw-养虾资料库.png)

   **AI Skills Workflow Pack · Basic** (13 categorized workflow packs):

   ![Skills Basic](产品文档/产品截图/xiaoyaoclaw-养虾资料库-Skills基础版.png)

   **AI Skills Workflow Pack · Enhanced** (7 advanced workflow packs):

   ![Skills Enhanced](产品文档/产品截图/xiaoyaoclaw-养虾资料库-Skills增强版.png)

---
