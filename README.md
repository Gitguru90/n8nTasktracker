# 🤖 AI Task Tracker & Reminder Agent (n8n)

An AI-powered Project Management Automation built using **n8n**, **OpenAI**, **Google Sheets**, and **Gmail**.

This workflow automatically generates project plans, creates milestones and tasks, assigns owners, tracks project progress, and sends intelligent reminder emails to team members.

## 🚀 Features

- 🧠 AI-generated Project Planning
- 📋 Automatic Milestone Generation
- ✅ Task Creation & Assignment
- 👥 Employee Allocation
- 📊 Google Sheets Integration
- 📅 Progress Tracking
- 📧 Automated Reminder Emails
- 🤖 AI-generated Email Content
- ⚡ End-to-End Workflow Automation

## 🛠️ Tech Stack

- n8n
- OpenAI GPT
- Google Sheets API
- Gmail API
- AI Agent
- Structured Output Parser

---

## 📂 Workflow Overview

### 1️⃣ Task Planner Agent

The planner agent receives a project request and automatically:

- Generates project milestones
- Creates descriptions
- Assigns project owners
- Sets priorities
- Defines start and end dates

All generated information is stored inside Google Sheets.

---

### 2️⃣ Task Generation Agent

The second AI agent creates:

- Individual Tasks
- Task Descriptions
- Assigned Employees
- Dependencies
- Estimated Hours
- Risk Levels
- Next Actions

Each task is stored in the Task Sheet.

---

### 3️⃣ Reminder Agent

The reminder workflow:

- Checks task deadlines
- Filters pending tasks
- Finds assigned employee details
- Generates personalized reminder emails using AI
- Sends emails automatically using Gmail

---

## 📊 Google Sheets Used

- Project Plan
- Tasks Sheet
- Team Members
- Notification
- Task Tracker
- Progress Checker
- Agent Logs
- Prompt

## 📈 Workflow Architecture

Chat Request
↓
Project Planner AI
↓
Generate Milestones
↓
Store in Google Sheets
↓
Generate Tasks
↓
Assign Employees
↓
Track Progress
↓
Reminder Agent
↓
AI Email Generation
↓
Gmail Notification

---

## 🎯 Example Use Case

Input:

> Create a Website Development Project

Output:

- Project Plan
- Milestones
- Tasks
- Employee Assignment
- Deadlines
- Priority
- Reminder Emails

Generated automatically.


## 📁 Repository Structure

```
.
├── Task Tracker Workflow.json
├── Reminder Agent Workflow.json
├── README.md
├── screenshots/


## 📬 Contact

**Kiran Tomar**


