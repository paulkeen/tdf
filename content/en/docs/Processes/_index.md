---
title: "Process"
linkTitle: "Processes"
weight: 3
description: >
  
---

## Concept to Code

The Software Development Lifecycle (SDLC) goes through four major
phases; stack ranking major projects, roadmaps by Streams, Epic
breakdowns and finally writing code against User Storyies

The SDLC is a subset of the PLMP which looks additional beyond scoping
and delivery to macro view on markets, competition and post-delivery
activity such as financials and benefits realisation

![](/img/media/image2.png)

### Portfolio Hierarchy

There are a number of levels to breakdown business goals into Streams
and Projects of work that get ultimately shipped to our Customers. We
have defined each phase.

| **Item**     | **Definition**                                                                                                                                                                                                                                         |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Stream       | Focus on a single, impactful stream of work. It can be a single product or service, a single set of features, a single user journey, or a single user persona.                                                                                         |
| Capabilities | The scope of a complete function that delivers a defined outcome for an audience. E.g. Business User at Tyro can identify and cohort customers by their current product holding across all products offered.                                           |
| Milestones   | An independently usable and valuable quantum of work. A subset of the full capability goal. A Business user can cohort lending customers by loan active, has had a loan, never had a loan, loan ineligible                                             |
| Requirements | A self-contained ruleset for a specific scenario underneath the milestone (nothing released by itself at this level)                                                                                                                                   |
| Epics        | Series of work goals needed to satisfy a requirement. Can be tech or product (I think of it as milestones to a requirement.                                                                                                                            |
| User Stories | Detailed level breakdown of the work beneath the Epics. e.g.  how do you create and individually test the actual Role Based Access rules per type of user, data element and intended permission level.                                                 |
| Spike        | A Spike is a timebox investigation of a requirement to help understand the solution approach and provide an accurate estimate. The outcome of a Spike should be User Stories with Story Points                                                         |
| Bug          | A bug a malfunction of the system, an error, flaw, or a default in the system, that causes an incorrect result. Bugs should only be created after a story is marked as Done. Any bugs found in during development should remain inside the User Story. |

Some projects can run over multiple Streams, some Streams have multiple
projects. Similarly, an Epic can run within a Stream or multiple
Streams. Due to Story Points being calculated at the granular level, a
summary of effort (Points) and costs can be calculated at the Stream,
Project, Capability, Squad or Epic level.

To avoid confusion, think of an Epic has a single row. A Pivot Table can
be used in Monday (or Excel) to provide the reporting view needed.

![](/img/media/image3.png)

#### Monday and Jira integration

Monday is Tyro's Product portfolio tool. Monday tracks KPIs, Projects,
Streams, capacity and project financials amongst many other things. The
tool should be considered the source of truth from a business tracking
perspective.

Jira tracks Epics, Spikes, Bugs, Quality and other technical activity.
Tyro also uses Jira for many other use cases but considered outside of
the TDF.

Monday and Jira have a two-way synchronisation at the Epic ID level.
Stream, Squads (Jira Project) and Epic Name are also synchronised. Story
Point data is summarised at the Epic level and shared with Monday.

![](/img/media/image4.png)

