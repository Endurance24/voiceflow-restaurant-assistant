# voiceflow-restaurant-assistant
AI Restaurant Voice Assistant | Voiceflow • Airtable • Conversational AI • Restaurant Automation
# AI Restaurant Voice Assistant

An AI voice assistant built in Voiceflow to handle restaurant customer calls — answering questions, taking reservations, and saving customer details automatically.

## Problem

A restaurant owner was spending too much time on the phone. Every call meant answering the same questions or booking a table by hand. That time added up, and it pulled the owner away from running the restaurant.

## What It Does

- Answers common restaurant questions using a menu/FAQ knowledge base
- Takes reservations through a natural conversation
- Saves customer details (name, phone number, reservation info) automatically, with no manual entry

## Tech Stack

- **Voiceflow** – conversation flow and AI assistant logic
- **Airtable** – stores reservations and customer information
- **n8n** *(planned)* – automated follow-ups like confirmations and staff notifications
- **WhatsApp** *(planned)* – customer messaging channel
- **Phone integration** *(planned)* – real voice calls

## Status

This is a working prototype. The conversation flow, Airtable integration, and knowledge base are built and tested. WhatsApp, phone integration, and n8n workflows are planned next steps, not yet implemented.

## What I Learned

The hardest part was designing a conversation flow that felt natural, not scripted. Customers don't ask questions in a straight line — someone might ask three things before booking, or change their mind mid-conversation. I had to map out these paths and test them so the assistant could handle them without breaking. Structuring the Airtable database also took real thought, so every reservation saved in a consistent format no matter how the conversation got there.

## Next Steps

- Connect WhatsApp and a phone system so customers can actually use the assistant
- Build n8n workflows for automated follow-ups
- Test with real users and measure response accuracy and reservation completion rate

## Author

Built by Endurance Alexander. I build AI automation systems using Voiceflow, n8n, Airtable, APIs, and Python. Email me to discuss your automation project.
