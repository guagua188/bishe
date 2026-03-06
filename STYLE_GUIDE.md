# App Design Style Guide

## Project Overview
This is a mobile companion app for a desktop printing and cutting machine.  
Users control machine status, monitor jobs, and manage settings through this app.

---

## Design Philosophy
- **Minimalist & Clean**: Inspired by Apple's design language — clear hierarchy, generous whitespace, purposeful elements only
- **Professional & Trustworthy**: The UI should feel precise and reliable, matching the quality of the physical machine
- **Functional First**: Every screen should communicate machine status clearly at a glance

---

## Color System

### Background Colors
- Primary Background: `#FFFFFF` (pure white)
- Secondary Background: `#F2F2F7` (Apple system gray 6 — used for grouped sections)
- Tertiary Background: `#FFFFFF` (cards, sheets)

### Text Colors
- Primary Text: `#000000`
- Secondary Text: `#3C3C43` at 60% opacity
- Tertiary Text: `#3C3C43` at 30% opacity

### Accent Color — Blue
- Primary Blue: `#007AFF` (Apple system blue — use for buttons, links, active states)
- Light Blue: `#E8F1FF` (use for selected states, tag backgrounds)
- Dark Blue: `#0055B3` (use for pressed states)

### Status Colors
- Success / Running: `#34C759` (green)
- Warning / Paused: `#FF9500` (orange)
- Error / Offline: `#FF3B30` (red)
- Idle: `#8E8E93` (gray)

---

## Typography

### Font
- Use **SF Pro** (iOS system font) or fallback to **Inter**
- Do NOT use decorative fonts

### Scale
- Large Title: 34px, Bold — page titles
- Title 1: 28px, Bold
- Title 2: 22px, Bold
- Headline: 17px, Semibold — section headers, card titles
- Body: 17px, Regular — main content
- Callout: 16px, Regular
- Subhead: 15px, Regular
- Footnote: 13px, Regular — labels, captions
- Caption: 12px, Regular — timestamps, metadata

---

## Spacing & Layout

- Base unit: **8px**
- Content margin (screen edges): **16px**
- Card padding: **16px**
- Section spacing: **24px**
- Element spacing within a card: **8px or 12px**

---

## Corner Radius
- Cards / Sheets: **16px**
- Buttons (full width): **14px**
- Buttons (small/inline): **10px**
- Tags / Chips: **8px**
- Icons: **12px**

---

## Component Guidelines

### Cards
- White background, `#F2F2F7` page background
- Subtle shadow: `0px 2px 8px rgba(0,0,0,0.08)`
- No heavy borders — use shadow for elevation

### Buttons
- Primary: Blue `#007AFF` fill, white text, full-width, 50px height
- Secondary: `#F2F2F7` fill, black text
- Destructive: Red `#FF3B30` text on transparent background
- Disabled: 30% opacity

### Status Indicators
- Use colored dots (8px circle) + label text to show machine status
- Always show status prominently at the top of the main screen

### Icons
- Use SF Symbols style (outlined, simple line icons)
- Icon size: 24px standard, 20px in lists, 28px in tab bars

### Navigation
- Tab bar at the bottom (iOS style)
- Top navigation bar with large title style on main screens

---

## Tone & Feel
- No gradients (use flat color only)
- No drop shadows heavier than `rgba(0,0,0,0.10)`
- Animations should feel fast and snappy (under 300ms)
- Illustrations: minimal, line-based, monochrome or single accent color

---

## Key Screens (for reference when generating designs)
1. **Home / Dashboard** — Machine status overview, current job progress
2. **Job Queue** — List of print/cut tasks, status per job
3. **Controls** — Start, pause, stop machine; adjust settings
4. **Settings** — Machine configuration, connectivity, notifications
5. **Notifications / Alerts** — Error alerts, job completion notices
