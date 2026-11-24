# Docketly: Attorney Workload & Deadline Calendar

**A workload dashboard that shows capacity per attorney alongside hearings, filings and statute deadlines on one shared calendar.**

![Legal](https://img.shields.io/badge/Legal-167dfe?style=flat-square) ![Legal workload dashboard](https://img.shields.io/badge/Legal%20workload%20dashboard-9533fa?style=flat-square) ![React](https://img.shields.io/badge/React-231f20?style=flat-square) ![Node.js](https://img.shields.io/badge/Node.js-231f20?style=flat-square) ![Python](https://img.shields.io/badge/Python-231f20?style=flat-square) ![Case management API](https://img.shields.io/badge/Case%20management%20API-231f20?style=flat-square) ![Google Calendar](https://img.shields.io/badge/Google%20Calendar-231f20?style=flat-square) ![n8n](https://img.shields.io/badge/n8n-231f20?style=flat-square)

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

React · Node.js · Python · Case management API · Google Calendar · n8n · Supabase

## Demo

A working version of the dashboard UI with **sample data** is in [`demo/index.html`](demo/index.html). Download it and open it in a browser; it has no build step.

## Privacy

Client names and records are confidential. Every screen in this repository uses sample data, and source code that belongs to the client is not published.

## Links

- Case study on Lexvaxa: https://lexvaxa.com/work/attorney-workload-deadline-calendar
- Built by **Ch Muhammad Samiullah** ([GitHub](https://github.com/samiullah156-creator)) at [Lexvaxa](https://lexvaxa.com)
