# meeting-workflow-automation

A productivity system that transforms meeting transcripts into actionable task lists, calendar events, and automated timesheet entries - designed to eliminate administrative overhead and work with ADHD-friendly task structures.

## The Problem

Meeting notes scattered across platforms
Action items lost or forgotten
Manual timesheet entry consuming 2-3 hours weekly
Context switching between note-taking and task management
Traditional task lists overwhelming for ADHD brains

## The Solution
An automated workflow that:

- Captures meeting transcripts (currently via [Tactiq)](https://tactiq.io/)
- Processes transcripts through LLM for summarization and action extraction
- Generates ADHD-optimized task breakdowns
- Creates ICS calendar files for automated scheduling
- Auto-populates timesheet data from calendar entries

## Current Architecture (V1)
Meeting → Tactiq Transcript → Manual Copy/Paste → LLM Processing → 
Structured Outputs (Summaries + Action Items + Project Timeline) → 
ICS File Generation → Calendar Import → Timesheet Auto-fill

## Features

- <strong>Meeting Summarization</strong>: Automatic extraction of key points and decisions
- <strong>Action Item Extraction</strong>: LLM identifies and structures next steps
- <strong>ADHD-Friendly Formatting</strong>: Tasks broken into 2-minute actionable chunks
- <strong>Project Timeline Generation</strong>: Scheduled task lists based on project requirements
- <strong>Calendar Integration</strong>: ICS export for seamless calendar import
- <strong>Timesheet Automation</strong>: Calendar-based auto-population eliminates manual entry
