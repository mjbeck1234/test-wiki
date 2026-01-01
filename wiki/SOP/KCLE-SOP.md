---
title: KCLE Standard Operating Procedures (TEST)
category: SOPs
visibility: members, staff
published: true
---

> **TEST CONTENT ONLY** — Not real-world, not VATSIM-official.  
> Use this page to validate the GitHub-backed wiki rendering, navigation, and permissions.

# KCLE Standard Operating Procedures (TEST)

## 1. Purpose
This document defines **test procedures** for KCLE operations on the Virtual Cleveland ARTCC website.  
It is intended to exercise the wiki system (formatting, tables, lists, code blocks, etc.).

---

## 2. Positions and Responsibilities
| Position | Scope (Test) | Notes |
|---|---|---|
| CLE_DEL | Clearances | Issues IFR clearances and PDC-like routes (test) |
| CLE_GND | Surface movement | Coordinates taxi routes and ramp flow (test) |
| CLE_TWR | Runway operations | Manages departures/arrivals and runway crossings (test) |
| CLE_APP | Terminal sequencing | Controls arrival/departure flows (test) |

### 2.1 Primary Goals
- Keep taxi instructions short and unambiguous
- Maintain predictable runway usage by flow
- Use standardized phraseology (test examples only)

---

## 3. Runway Configuration (TEST)
### 3.1 Default Flow Preference
- **West flow** (preferred): *Runway 24/24L/24R* (test)
- **East flow** (alternate): *Runway 6/6L/6R* (test)

> This is **not** authoritative. Use your real facility SOP elsewhere.

### 3.2 Runway Change Guidance
Consider switching flow when:
- Tailwind component exceeds your test threshold (e.g., 8 kt)
- Arrival spacing becomes unstable due to crosswind variability
- Significant convective weather impacts departures

---

## 4. Taxi (TEST)
### 4.1 Standard Taxi Principles
- Provide **runway**, **taxi route**, and **hold short** instructions
- Use progressive taxi only when needed (busy times)

### 4.2 Example Taxi Routes (Fake)
- **Ramp → RWY 24R**: “Taxi via A, B, hold short 24R”  
- **Ramp → RWY 6L**: “Taxi via C, D, hold short 6L”

---

## 5. Departure Procedures (TEST)
### 5.1 Common “SID-like” Routing (Fake)
Use these to test route display formatting:

- **DETROIT (DTW)**: `CLE..DJB..DTW`  
- **PITTSBURGH (PIT)**: `CLE..AOO..PIT`  
- **CHICAGO (ORD)**: `CLE..DJU..ORD`  

### 5.2 Release / Coordination (Test)
- If a departure is rerouted, annotate the strip and advise next position.
- If the runway changes, ensure the clearance matches the expected flow.

---

## 6. Arrival Procedures (TEST)
### 6.1 General Sequencing
- Keep arrivals on a simple downwind/base/final pattern (test)
- Maintain stable spacing on final

### 6.2 “STAR-like” Examples (Fake)
- **From the East**: `JHW..ELZ..CLE`  
- **From the South**: `AOO..AIR..CLE`

---

## 7. Weather and Braking Action (TEST)
### 7.1 When to Issue Weather Callouts
- Significant wind shift
- Rapidly changing visibility/ceiling
- LLWS or convective activity within 10 NM (test)

### 7.2 Sample Braking Action Report Format
> “Braking action reported **good** by a B738 at time 2135Z.”

---

## 8. Ground Stop / Flow (TEST)
### 8.1 Trigger Conditions (Fake)
Initiate a “test flow restriction” when:
- Arrival bank exceeds 15 inbound in 30 minutes
- Departure queue exceeds 12
- Runway reduced to single arrival/departure

### 8.2 Mitigation Actions
- Meter releases
- Use a single runway for departures temporarily
- Hold aircraft at ramps if needed (test)

---

## 9. Frequencies (TEST)
> These are placeholder values.

- **DEL**: 120.100  
- **GND**: 121.900  
- **TWR**: 118.700  
- **APP**: 124.200  

---

## 10. Phraseology Examples (TEST)
- “CLE Tower, **Runway 24R**, cleared for takeoff.”
- “Taxi to Runway 24R via A, B, **hold short Runway 24R**.”
- “Maintain 3,000, fly heading 270, vectors for sequence.”

---

## 11. Notes for Web Testing
### 11.1 Markdown Features Used
- Frontmatter
- Tables
- Blockquotes
- Lists
- Inline code: `CLE..DJB..DTW`

### 11.2 Code Block Test
```txt
ROUTE TEST:
CLE DCT DJB DCT DTW

NOTES:
- This is a test-only SOP page.
- Verify rendering + permissions.
