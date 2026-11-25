<!-- styled:v2 -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1d1726,50:167dfe,100:9533fa&height=180&section=header&text=Docketly%3A%20Attorney%20Workload%20%26%20Deadline%20Calendar&fontSize=25&fontColor=ffffff&fontAlignY=36&desc=Case%20study%20%E2%80%A2%20Legal%20%E2%80%A2%20Legal%20workload%20dashboard&descAlignY=58&descSize=16&animation=fadeIn" width="100%" alt="Docketly: Attorney Workload & Deadline Calendar" />

**A workload dashboard that shows capacity per attorney alongside hearings, filings and statute deadlines on one shared calendar.**

<p>
  <img src="https://img.shields.io/badge/Legal-167dfe?style=flat-square" alt="Legal" />
  <img src="https://img.shields.io/badge/Legal%20workload%20dashboard-9533fa?style=flat-square" alt="Legal workload dashboard" />
  <img src="https://img.shields.io/badge/React-231f20?style=flat-square" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-231f20?style=flat-square" alt="Node.js" />
  <img src="https://img.shields.io/badge/Python-231f20?style=flat-square" alt="Python" />
  <img src="https://img.shields.io/badge/Case%20management%20API-231f20?style=flat-square" alt="Case management API" />
  <img src="https://img.shields.io/badge/Google%20Calendar-231f20?style=flat-square" alt="Google Calendar" />
  <img src="https://img.shields.io/badge/n8n-231f20?style=flat-square" alt="n8n" />
</p>

<p>
  <a href="#overview">Overview</a> ·
  <a href="#key-features">Key features</a> ·
  <a href="#results">Results</a> ·
  <a href="#tech-stack">Tech stack</a>
</p>

</div>

---

![Docketly attorney workload calendar: capacity per attorney, weekly matters and a week view of hearings, filings and deadlines.](assets/cover.webp)

## Overview

Deadlines and caseloads were spread across calendars and the case system, which made it hard to balance work. Lexvaxa built Docketly, a custom dashboard that pulls matters and tasks from the case management system and Google Calendar. It shows open matters, weekly due dates and overdue tasks, caseload and capacity per attorney, matters by stage and a week calendar of every hearing, filing and deadline. Screens shown use sample data, so no client records are exposed.

## The challenge

Without one view of deadlines and caseloads, some attorneys were overloaded while important dates were at risk.

## The solution

n8n syncs matters, tasks and calendar events into Supabase, and a React calendar shows deadlines next to each attorney's capacity.

## Key features

- Capacity and caseload per attorney
- Week calendar of hearings, filings and deadlines
- Open matters, due this week and overdue tasks
- Matters by stage
- Upcoming deadlines list

## Results

- Every deadline is visible and work is shared more evenly across the team

## Tech stack

![React](https://img.shields.io/badge/React-1d1726?style=for-the-badge) ![Node.js](https://img.shields.io/badge/Node.js-1d1726?style=for-the-badge) ![Python](https://img.shields.io/badge/Python-1d1726?style=for-the-badge) ![Case management API](https://img.shields.io/badge/Case%20management%20API-1d1726?style=for-the-badge) ![Google Calendar](https://img.shields.io/badge/Google%20Calendar-1d1726?style=for-the-badge) ![n8n](https://img.shields.io/badge/n8n-1d1726?style=for-the-badge) ![Supabase](https://img.shields.io/badge/Supabase-1d1726?style=for-the-badge)

## Demo

A working version of the dashboard UI with **sample data** is in [`demo/index.html`](demo/index.html). Download it and open it in a browser; it has no build step.

## Privacy

Client names and records are confidential. Every screen in this repository uses sample data, and source code that belongs to the client is not published.

## Links

- Case study on Lexvaxa: https://lexvaxa.com/work/attorney-workload-deadline-calendar

---

<div align="center">

**Built by [Ch Muhammad Samiullah](https://github.com/samiullah156-creator)** · AI Automation Engineer and Full-Stack Developer at [Lexvaxa](https://lexvaxa.com)

<a href="https://github.com/samiullah156-creator"><img src="https://img.shields.io/badge/More%20projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="More projects" /></a>
<a href="https://lexvaxa.com/contact"><img src="https://img.shields.io/badge/Work%20with%20me-167dfe?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Work with me" /></a>
<a href="https://www.linkedin.com/in/sami-lexvaxa/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

<sub>⭐ Star this repo if you found it useful</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:9533fa,50:167dfe,100:1d1726&height=110&section=footer" width="100%" alt="" />
