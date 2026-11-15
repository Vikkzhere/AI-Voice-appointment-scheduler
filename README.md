# AI Voice Appointment Scheduling System

### ElevenLabs | n8n | Google Gemini | Google Calendar

An AI-powered dental appointment scheduling prototype that integrates conversational AI, workflow automation, and Google Calendar to process patient appointment requests.

## Project Overview

This project explores how AI voice agents and workflow automation can streamline appointment scheduling for dental clinics.

The system uses ElevenLabs Conversational AI to communicate with patients, n8n to orchestrate the workflow, Google Gemini to process appointment information, and Google Calendar as the scheduling integration.

**Project Status:** Prototype under development. End-to-end calendar booking and confirmation are still being tested.

Technologies Used

- **ElevenLabs Conversational AI:** Voice-based patient interaction
- **n8n:** Workflow automation and orchestration
- **Google Gemini:** AI-powered appointment request processing
- **Google Calendar API:** Calendar event creation integration
- **REST API and Webhooks:** Communication between ElevenLabs and n8n
- **JSON:** Structured appointment data exchange

## System Architecture

```text
Patient
   |
   v
ElevenLabs Voice Agent
   |
   v
n8n Webhook (POST)
   |
   v
AI Agent (Google Gemini)
   |
   v
Google Calendar Tool
```

## Implemented Features

- Configured an AI voice receptionist for dental appointment requests.
- Established webhook communication between ElevenLabs and n8n.
- Configured patient information extraction and processing.
- Integrated Google Gemini with the n8n AI Agent.
- Connected Google Calendar as an appointment creation tool.
- Investigated API quota errors and workflow execution issues.

## Appointment Information

The system processes five fields:

1. Patient name
2. Dental service
3. Appointment date
4. Appointment time
5. Phone number

## Future Improvements

- Complete and verify end-to-end appointment booking.
- Check appointment availability before creating events.
- Prevent double bookings.
- Return confirmed booking results to the voice agent.
- Improve error handling and validation.
- Add automated appointment reminders.

## Workflow

The sanitized n8n workflow is available in this repository:

[View n8n Workflow](ai-voice-appointment-scheduler-public.json)

## Privacy and Security

This repository is intended for demonstration and educational purposes. It does not include live API credentials or real patient information.

## Project Type

Personal AI Automation and Digital Transformation Project.
