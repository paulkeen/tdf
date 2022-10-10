---
title: "Principles"
linkTitle: "Principles"
weight: 1
description: >
  Tyro was founded on a strong with a strong engineering culture by former CISCO. Whilst being a technically opinionated, we're have an open, trust by default culture.
---
## General Principles
To get a sense of our philosophy, these are some of our principles both
culturally and technically.

### Ways of Working
-   Flexible working hours (over set working hours).
-   Writing down and recording knowledge (over verbal explanations).
-   Written processes (over on-the-job training).
-   Public sharing of information (over need-to-know access).
-   Open documents by default, editing by anyone (over top-down control
    of documents).
-   Asynchronous communication (over synchronous communication).
-   Use boring, proven technology unless the solution absolutely
    requires otherwise.

### Technical
-   Any reasonably complex manual processes that are executed more than
    twice are candidates for automation (with appropriate documentation)
-   One SOE to rule them all. By making teams own their own SOE (or set
    up their own machines manually because none of the SOEs work),
    we\'re wasting way too much time and effort.
-   All code merged to master must be in a state that can be deployed to
    prod at any time
-   The master build pipeline should deploy to all environments from dev
    through to prod automatically. Progression to each environment
    should only occur once the relevant verification tests have passed.
-   Decouple feature delivery from deployment. Features should be
    enabled or disabled independently from code deployments. Use a
    feature flag system to control access to features and code paths.
-   Observability and operations. Improved runbooks with links to the
    logs and dashboards needed to triage an alert. SLOs for reliability,
    latency. Error budgets
-   Simplify the code. Use platform / sidecars.
-   Don\'t make all teams own code that should be commonly shared
-   Code style. Use the language\'s standard code formatting rules to
    eliminate bike-shedding and simplify PRs.
-   Automated code/spec-driven documentation for all artefacts
-   Data migration and other management tasks should be exposed as
    endpoints that can only be requested by specific internal
    users/groups.
-   Implement a service catalog that provides visibility into available
    services including ownership, documentation, metrics, logs, SLOs,
    management tools, etc.

## Joel Test

What good looks like for Software Engineering is highly subjective.
Legend Joel Spolsky of *Joel on Software* and CEO of Stack Overflow fame
created a blog in 2000 where he created a simple and quick test on what
good looked like at the time.

The *Joel Test* is made up of closed 12-points questions. A score of 12
is perfect. 11 is considered tolerable, and 10 or below is unacceptable.
It\'s a tough test to pass; we use this amongst teams to see the level
of maturity and where to focus our continuous improvement.

This is our modernised version of the *Joel Test* at Tyro.

> 1.  Is security your first-priority?
> 2.  Do you have shared code ownership?
> 3.  Do your repos effectively state their intention?
> 4.  Are your services encapsulated, interfaces documented, and cascading failures understood?
> 5.  Are your XP practices defined, implemented and measured?
> 6.  Do you constructively communicate across Squads and Tribes?
> 7.  Do your observability tools continually know the health of your service?
> 8.  Is your code rigorously reviewed with good intent?
> 9.  Do you clearly understand the customer benefit of the epic?
> 10. Do you have Quality related Coverage planned for all stages of the delivery?
> 11. Are you given the room to Wow the Customer?
> 12. Are you continuously learning?

