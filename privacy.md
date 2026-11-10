---
title: Proword Plugin — Privacy Policy
permalink: /privacy/
---

# Proword Plugin — Privacy Policy

**Effective date:** 10 November 2026

This policy covers the **Proword plugin** for ChatGPT and other AI assistants that support the Model Context
Protocol (MCP), served from `https://api.proword.app/mcp` (the "Plugin"). The Proword iOS and Android apps
have their own privacy policies at [proword.app/privacy](https://proword.app/privacy).

## Summary

- The Plugin has **no accounts and no sign-in**.
- We do **not** receive your conversation, name, email address or chat history.
- Our server receives only what is needed to answer a request, and keeps technical logs for **up to 30 days**.
- We do **not** sell, rent or share data for advertising, and we do not use it to train AI models.

## What data we receive

When your AI assistant uses the Plugin, it sends our server a request. We receive:

| Data | Example | Why |
|---|---|---|
| Tool request parameters | CEFR level, the language you are learning, your native language, number of words, a word you asked to look up | To return the right words, quiz or lookup result |
| Technical data | IP address of the requesting service, date and time, requested URL, response status, user agent | Security, abuse prevention, rate limiting and troubleshooting |

When the Plugin shows a quiz or word card, the widget loads word images from `https://api.proword.app/images/`.
Those image requests are part of the technical data above.

We do **not** ask for, and do not knowingly receive, personal information such as your name, email address,
location, contacts, payment details or the text of your conversation. Requests usually reach us from the AI
provider's servers, so the IP address we see is typically the provider's, not yours.

## How we use it

Only to operate the Plugin: answer requests, keep the service secure and available, enforce rate limits and
fix errors. We do not build user profiles, track you across services, show advertising or use the data to
train AI models.

## Retention

- **Request parameters** are used to answer the request and are not stored in a database.
- **Server logs** (technical data and, in some cases, request parameters) are deleted automatically within
  **30 days**.
- **Rate-limiting counters** are kept in memory for about one minute.

## Sharing

We do not sell or rent data. Data is processed only by:

- **Our hosting provider** (Hostiq.ua, Ukraine), which runs the server on our behalf.
- **Authorities**, if required by law.

## Your AI assistant provider

Your conversation is handled by the provider of your AI assistant (for example OpenAI for ChatGPT or Anthropic
for Claude) under its own privacy policy. That provider decides what it sends to the Plugin. We do not control
and are not responsible for its handling of your data.

## Your choices and rights

- You can stop using the Plugin at any time by disconnecting or disabling it in your AI assistant.
- Because we do not identify users, we usually cannot link logs to a specific person. If you believe we hold
  data about you, contact us and we will help, including by deleting it where possible.
- Depending on where you live (for example under the GDPR), you may have rights to access, correct, delete or
  object to the processing of your personal data, and to complain to a data protection authority.

## Children

The Plugin is intended for general audiences learning vocabulary. We do not knowingly collect personal
information from children. Use of AI assistants is subject to their providers' age requirements.

## Security

Traffic to the Plugin is encrypted with HTTPS. Access to the server and its logs is restricted to the operator.

## Changes

We will update this page when the Plugin's data handling changes, and change the effective date above.

## Contact

Oleksii Mykhalchuk — [support@oleksi.dev](mailto:support@oleksi.dev)
