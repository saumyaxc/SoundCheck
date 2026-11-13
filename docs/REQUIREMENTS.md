# Requirements Document

## 1. Purpose & Problem Statement
As someone who loves going to concerts, I want to make sure that I'm not overpaying for tickets to see my favorite artists. I have run into the issue of either buying the tickets too early or waiting too long for the tickets to get cheaper. In both scenarios, I have ended up buying tickets for more than I had to. With ticket vendor websites today, it's hard to tell when tickets will be at their cheapest. For example, during Bryson Tiller's most recent tour, I bought tickets during presale for about [XX], and the price dropped to [XX] a few months later. SoundCheck would would track prices over time so I can see how they actually behave, and eventually give a signal on when to buy. [Why it cannot be solved today]

## 2. Users & Use Cases 
### Users - TODO
* How often do you buy concert tickets, and for what kinds of shows?
* How much do you care about price versus getting to the show at all?
* How technical are you as a user (you'll tolerate a rough dashboard, which affects requirements)
### Use Cases - TODO
#### User Case 1 - Presale Decision
* **Situation**: A tour is announced and presale is coming up. Should you buy then or wait?
* **What I do in SoundCheck**: the actions
* **What I get (v1)**: what the app shows/tells you
* ***What I get (later)**: what the app will be able to do later.
* **What could go wrong**: one thing

#### User Case 2 - Missed Presale
* **Situation**: You didn't get presale access, so should you buy at general on-sale or wait?
* **What I do in SoundCheck**: the actions
* **What I get (v1)**: what the app shows/tells you
* **What I get (later)**: what the app will be able to do later.* **What could go wrong**: one thing

#### User Case 3 - Watching a Specific Show
* **Situation**: You've picked a show and want an alert when the price drops below a number you choose.
* **What I do in SoundCheck**: the actions
* **What I get (v1)**: what the app shows/tells you
* ***What I get (later)**: what the app will be able to do later.
* **What could go wrong**: one thing

#### User Case 4 - Understanding Patterns
* **Situation**: You look at price history for an event to learn how prices behave over time.
* **What I do in SoundCheck**: the actions
* **What I get (v1)**: what the app shows/tells you
* ***What I get (later)**: what the app will be able to do later.
* **What could go wrong**: one thing

## 3. Goals & Non-Goals
### Goals - TODO
<!-- What must SoundCheck accomplish? Think outcomes, not features. -->
### Non-Goals - TODO
<!-- What are you deliberately NOT doing. (ex: buying tickets, scraping, other users, mobile app), why for each -->

## Functional Requirements - TODO
### 4.1 Event Selection
| ID | Requirement | Priority | Version |
|----|-------------|----------|---------|
| FR-1 | | | |

### 4.2 Price Collection
| ID | Requirement | Priority | Version |
|----|-------------|----------|---------|
| FR-2 | | | |

### 4.3 Data Storage
| ID | Requirement | Priority | Version |
|----|-------------|----------|---------|
| FR-3 | | | |

### 4.4 Dashboard
| ID | Requirement | Priority | Version |
|----|-------------|----------|---------|
| FR-4 | | | |

### 4.5 Alerts
| ID | Requirement | Priority | Version |
|----|-------------|----------|---------|
| FR-5 | | | |

### 4.6 Analysis / Buy-Now-or-Wait-Signal
| ID | Requirement | Priority | Version |
|----|-------------|----------|---------|
| FR-6 | | | |

## 5. Data Requirements - TODO
<!-- What gets recorded per snapshot? How often? How long is it kept? What identifies an event, an artist, a snapshot? -->
- Data to Collect:
- Collection Frequency:
- Retention:

## 6. Non-Functional Requirements - TODO
- **Reliability:** e.g., how many missed polls in a row are acceptable?
- **Quota/rate-limits:** stay under what % of the daily cap?
- **Cost:** monthly ceiling
- **Security:** where API keys live, what's never committed
- **Maintainability:** modularity rules, documentation rules
- **Timekeeping:** all timestamps stored in UTC

## 7. Constraints & External Dependencies - TODO
<!-- Facts found while researching that limit the design. -->
- Ticketmaster Discovery API: <!-- limits, terms, what data it does/doesn't provide -->
- Other Data Sources: <!-- e.g. artist popularity -->
- Legal/Terms: <!-- what I will/won't do -->
- Time/Resources: hours per week, solo developer

## 8. Assumptions & Risks - TODO
| Assumption or Risk | What if it's wrong | Mitigation |
|--------------------|--------------------|------------|
| TODO |  |  |

## 9. Success Criteria & Milestones - TODO
- **M0 (collector running):** done when __. [ ]
- **M1 (dashboard + alerts):** done when __. [ ]
- **M2 (analysis):** done when __. [ ]
- **M3 (buy-now/wait signal):** done when __. [ ]

## 10. Open Questions
- [ ] Does the free API key return price ranges? 
- [ ]

## 11. Glossary - TODO
<!-- Defining terms. -->
- Presale
- On-sale
- Price-snapshot