# Ateneu – Productivity app for macOS

Hi! 👋  

These screenshots are part of **Ateneu**, a macOS productivity app I’m developing as my Final Degree Project in Computer Engineering at La Salle Campus Barcelona.

The goal is to bring together emails, calendar, tasks, reminders, and an AI assistant into a single app, so I don’t have to juggle multiple tools every morning just to know what my day looks like.

> The code is currently in a **private repository** because it’s directly tied to my FYP submission.  
> If you’d like to talk about the project, its architecture, or macOS + SwiftUI + SwiftData + local LLMs, feel free to contact me.
> The designs are 100% made by me, no AI, I love design, and the code I had some AI help as I started this project with barely no Swift or SwiftUI knowledge.
> I had a Swift class at university and then took a Coursera Meta course about Swift development.

---

## Dashboard

<img width="1512" height="982" alt="Initial window - light-1" src="https://github.com/user-attachments/assets/4c2cb5b8-fe7b-4209-98da-12df00dd92c2" />

The dashboard gives a quick summary of:
- Today’s emails (with important vs spam, and inline preview)
- Today’s events (morning/afternoon breakdown)
- Today’s tasks and reminders
- Current weather in different locations

<img width="1512" height="982" alt="Initial window - light-2" src="https://github.com/user-attachments/assets/a6a4406e-9a2c-4fb8-8f9e-604215d34aed" />

There’s also a timetable‑style view for classes/blocks and a lighter “Good evening / Good morning” summary of your day.

---

## Chat & AI assistant

<img width="1512" height="982" alt="Initial window - light-4" src="https://github.com/user-attachments/assets/3b532ab5-deda-4ab4-885e-a35d0f96fc1b" />

Ateneu includes a chat interface with a **local Llama model** (no direct internet access, knowledge up to ~2024).  

<img width="1512" height="982" alt="Subinitial window" src="https://github.com/user-attachments/assets/de143a9a-0414-4864-9d6b-b1abb53e7043" />

From natural language like *“Tomorrow I am going to play tennis at 8pm”*, the app:
- Creates a calendar event (with category, date, and time)
- Creates a matching task/reminder

<img width="1512" height="982" alt="Files - light" src="https://github.com/user-attachments/assets/0b65f532-6257-454a-ad04-ddb0ea6e374e" />

There’s also support for working alongside text documents (e.g. “Improve the second paragraph”), plus a **chat history** view with named sessions so you can revisit previous conversations.

---

## Calendar

<img width="1512" height="982" alt="Calendar - light" src="https://github.com/user-attachments/assets/c6b09fb4-60de-4da0-80dc-b6ba2b8f4124" />

Custom calendar with:
- Year and month views
- Weekends highlighted
- Multiple colour‑coded calendars (Padel games, Travel, Dog care, etc.)

<img width="1512" height="982" alt="Calendar - light-1" src="https://github.com/user-attachments/assets/95fa8f82-36c7-4020-941c-5783a7b3c2ff" />

Events are displayed using the same colour scheme as the calendar list on the side.

<img width="1512" height="982" alt="Calendar - dark-1" src="https://github.com/user-attachments/assets/07d188aa-7a12-4fa2-83bf-3f6e2ef8a03d" />

Dark mode version using the same structure, but adapted to the rest of the app’s appearance.

---

## Reminders & tasks

<img width="1512" height="982" alt="Initial files page - light-2" src="https://github.com/user-attachments/assets/eaed48cb-364b-4ef0-84f0-f388678fbeb7" />

A simple reminders view where I can:
- See tasks grouped by date (Today, specific days)
- Keep some tasks “No deadline”
- Track both university work (e.g. *Study ITsec*, *Work in TFG*) and personal stuff (e.g. *Go inspect path to San Juan*)

---

## Settings – General & Appearance

<img width="741" height="603" alt="Group 61" src="https://github.com/user-attachments/assets/3ad87d70-e840-4db6-8be9-a01583c2bfb9" />

From here you can:
- Set your name / greeting
- Tune the **assistant’s behaviour** (Polite, Playful, Sarcastic, Warm) with an example sentence

<img width="740" height="559" alt="Group 63" src="https://github.com/user-attachments/assets/51e92ae3-affd-4120-b364-5715313c5cf0" />
<img width="741" height="559" alt="Group 62" src="https://github.com/user-attachments/assets/d2752d9e-63cc-48ec-ac80-43a9b646f996" />


Appearance tab:
- Switch between light / dark mode
- Configure **calendar colours** and how they map to different tags (e.g. “Travel” in multiple palettes)

---

## Mail integration

<img width="740" height="559" alt="Group 58" src="https://github.com/user-attachments/assets/c70f624f-aba3-41f4-abee-e371c6d7d902" />
<img width="741" height="559" alt="Group 57" src="https://github.com/user-attachments/assets/72f2afe9-d86b-429c-a8c3-ceefa4270ea6" />

Mail settings:
- Support for multiple Gmail and Outlook accounts
- Each account in its own card (Personal, Work, etc.)
- Used by the dashboard to show today’s emails and highlight important ones

![Mail – select account type](settings-select-provider.png)

Provider selector when adding a new account (Gmail / Outlook).

---

## Project status

Ateneu is **work in progress**. I’m still:
- Refining the architecture (towards a cleaner MVVM in SwiftUI)
- Extending AI capabilities (editing/deleting events and tasks, querying all internal data)
- Polishing the UX and transitions across dashboard, calendar, chat, and reminders

👉 The repository where I’m developing this is **private** for now because it’s part of my Final Degree Project.  
If you’d like to:
- Discuss the implementation (SwiftUI + SwiftData)
- Talk about integrating a local LLM into a productivity app
- Give feedback on UX or architecture

please **reach out to me here on GitHub or contact me directly**. I’m happy to talk about the project and its internals.
