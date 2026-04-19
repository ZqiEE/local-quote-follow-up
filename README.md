[English](./README.md) | [中文](./README.zh-CN.md)

# Local Quote Follow-up

**A local-first lead capture and quote follow-up app for service businesses.**

Find leads. Move them into follow-up. Keep data local.

## What it does

Local Quote Follow-up helps service teams:

- find company websites that look worth contacting
- move selected leads into a local pipeline
- turn them into Customer / Quote / Task records
- keep follow-up and quote progress moving from one workspace

## Why local / private

- Data stays on your machine by default
- External AI APIs are off by default
- The local model runtime is visible inside Settings
- You can inspect the data path, model path, and runtime mode yourself

## Main workflow

1. Search in **Lead Capture**
2. Review which leads are actually worth contacting
3. Click **Move to Follow-up**
4. Let the system create or reuse **Customer / Quote / Task**
5. Continue from **Today Queue**
6. Use **Quick Follow-up** to keep the quote moving
7. Review write-back history in **Timeline**
8. Use **Undo Last AI Update** if needed

## Key features

- ICP-driven lead capture
- Local lead-to-pipeline write-back
- Quote-centered Today Queue
- Quick Follow-up
- Timeline + Undo
- Visible local runtime settings

## Screenshots / demo

Placeholders:

- Today Queue
- Lead Capture
- Move to Follow-up
- Quote Detail + Timeline
- Desktop Settings / local runtime

## Install

### Windows desktop build

1. Download the latest installer from Releases
2. Install the app
3. Open **Local Quote Follow-up**

### Local development

Backend:

```powershell
cd /d F:\vendor_eval\idurar-erp-crm\backend
npm run start
```

Frontend:

```powershell
cd /d F:\vendor_eval\idurar-erp-crm\frontend
npm run dev -- --host 127.0.0.1
```

Open:

```text
http://127.0.0.1:3001
```

## First-run setup

On first launch:

1. Install the local model runtime
2. Install the recommended model
3. Continue into the app

You can inspect:

- data directory
- models directory
- runtime mode
- Ollama path

## Current stage / current limits

Current stage:

- internal testing / small closed beta

Current limits:

- Lead Capture first version is usable, but still needs more real-user validation
- Lead quality is not yet fully production-grade
- Desktop first-run still needs broader install validation
- Low-frequency pages are not fully translated yet

## Roadmap

- validate lead quality with real users
- improve who is actually worth contacting
- improve conversion from lead to follow-up
- improve install trust and onboarding

## Feedback / contact

The most useful feedback is:

- what search input you used
- how many leads came back
- how many you would actually contact
- which leads you moved into follow-up
- what step felt slow, unclear, or not trustworthy

