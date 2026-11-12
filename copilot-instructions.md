# Lexie Reward Tracker - Project Context

## Project Goal

Build a mobile-first web application for my 6-year-old daughter, Lexie.

The application is a reward system that converts positive behaviours into YouTube screen time.

The application is hosted on GitHub Pages and should remain simple to deploy.

Current architecture:

- Single-page web application
- Single HTML file deployment preferred
- Runs on GitHub Pages
- Mobile-first design
- Designed primarily for iPhone use
- No backend
- Data stored locally using browser localStorage

---

## Theme

Inspired by the energy and style of K-Pop Demon Hunters.

Do NOT use copyrighted characters, names, artwork, or trademarks.

Create original equivalents that capture the same feel:

- Bright colours
- Pop-star aesthetics
- Magical guardians
- Monster hunting themes
- Character progression
- Collectables
- Achievements

Target audience:

- 6 year old child
- Easy to understand
- Highly visual
- Exciting and rewarding

---

## Current Functionality (Version 1)

Existing application allows:

- Earn points from tasks
- Convert points into YouTube minutes
- Store points in localStorage
- Display current points
- Display available YouTube minutes

Current tasks include:

- Taking medicine
- Taking vitamins
- Brushing teeth
- Using the toilet
- Good bedtime
- Good listening

Points currently persist between sessions through localStorage.

Application is already deployed through GitHub Pages.

---

## Product Vision

Turn the reward tracker into a game.

The app should feel more like an adventure than a checklist.

Positive behaviours should provide:

- Points
- XP
- Progress
- Levels
- Unlockables
- Achievements

---

## Proposed Version 2 Features

### Daily Task System

Each task can only be completed once per day.

Examples:

- Take Medicine
- Take Vitamins
- Brush Teeth Morning
- Brush Teeth Evening
- Toilet Success
- Good Bedtime
- Good Listening

Automatically reset available tasks each day.

---

### YouTube Time Bank

Store YouTube minutes as a balance.

Example:

Current Balance:
75 minutes

Allow parent to deduct time:

- Watch 15 minutes
- Watch 30 minutes
- Watch 60 minutes

Balance should never go below zero.

---

### Level System

Example progression:

Level 1: Rookie Hunter
Level 2: Melody Guardian
Level 3: Demon Chaser
Level 4: Superstar Hunter
Level 5: Legendary Guardian

Levels are earned through total lifetime XP.

---

### Streak System

Track consecutive days of activity.

Examples:

- Medicine streak
- Teeth brushing streak
- Overall daily streak

Provide bonus rewards for streak milestones.

---

### Achievement System

Examples:

- First Mission Complete
- Medicine Master
- Tooth Defender
- Bedtime Champion
- 7 Day Streak
- 30 Day Streak
- Legendary Hunter

Achievements should remain permanently unlocked.

---

### Unlockables

The child should unlock companions and cosmetic items.

Examples:

- Magical Tiger
- Pop Fox
- Moon Dragon
- Guardian Cat

Unlockables are collected permanently.

---

### Parent Controls

Include a protected parent area.

Features:

- Adjust points
- Adjust YouTube balance
- Reset week
- Reset streak
- Add custom tasks

Protect using a configurable PIN.

---

## Technical Requirements

### Platform

- HTML
- CSS
- Vanilla JavaScript

Avoid frameworks unless absolutely necessary.

---

### Storage

Use localStorage.

Store all player data in a single structured object.

Example:

{
  "points": 120,
  "youtubeMinutes": 90,
  "xp": 250,
  "level": 3,
  "streak": 5,
  "achievements": [],
  "pets": [],
  "completedTasksToday": []
}

---

### UI Requirements

Must work well on:

- iPhone Safari
- Android Chrome
- GitHub Pages hosting

Mobile-first design.

Large buttons.

Bright colours.

Clear progress indicators.

Suitable for a young child.

---

## Development Principles

1. Make every action feel rewarding.
2. Reward consistency over perfection.
3. Minimise reading requirements.
4. Prefer icons and visuals.
5. Store all progress locally.
6. Keep deployment simple.
7. Do not require a backend service.
8. Maintain GitHub Pages compatibility.
9. Favour a single-file deployment when possible.
10. Design for future expansion.
