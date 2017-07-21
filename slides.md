# Development team structure

---

## Notes on terminology

- *BAU* - Business as usual
- *Prod support* - Developer activities required for BAU
- *Critical path* - The sequencing and delivery timeframes for work
- *LOB* - Line of business 

---

## What are the goals of this proposed change

- So that we can better plan and execute
- To protect our critical path from BAU
- To provide structure to our project work
- To actively involve cross-LOB units in development projects

---

### So that we can better plan and execute

Projects have a lifcycle, with stakeholders and specific accountability

We need to be better at knowing who can make decisions, who must be consulted, who is accountable for each part of the project and who will do what work

--

### To protect our critical path from BAU

We are highly reactive as a team, responding to prod support issues with the highest urgency, which is often appropriate. However, this means that our critical path is neglected, and strategic projects do not get completed.

--

### To provide formal structure to our project work

Our informal project structure has been identified as a major obstacle to quality and timeliness of our current project work.

--

### To actively involve cross-LOB units in development projects


Understanding the needs and goals of different areas of the business is important. We can do better with involving Client and Partner Experience in our day to day work.

---

# Two teams
## Two concurrent streams of work

- Tactical
- Strategic

Project cycles will run in 6 week increments.

---

## The Tactical team

This team is the most similar to how we currently work. Tactical projects are those that are needed in the short to immediate term, and include prod support activities.

Tactical projects are shorter cycle, 2-3 weeks at a time

--

### Examples of tactical projects

- Marketing and SEO updates to the public website
- Bugfixes
- Incremental improvements to the UI (#quickwins)
- Postgres upgrade

The Tactical team are altruists. Their main job is to help the business operate smoothly.

--

## The Strategic team

This team is protected as much as possible from BAU, and represents the work that is on the critical path.

Strategic projects are no longer than 6 weeks

--

### Examples of strategic projects

- OpenAPI modules
- React MVC replacement for Struts/Tiles
- Looker reporting

The strategic team work mostly in the areas of major improvements, refactoring, and new build.

---

## So, which team am I on?

It will vary depending on many factors such as

- Subject matter expertise
- How long you have been in a particular team
- Staffing requirements


--

## Personal preference is a factor

If you are interested in a particular project, or you would prefer not to work on one let your team lead know

Team leads don't have to be the same people for a project every time

It's okay to have preferences, and over time we should all do the things we like, as well as the things we must do for the team

---

## Roles

Within each team

- Product owner: Person who directs the team to produce the agreed solution, and is the representative of the business and clients
-  Team Lead: Person who is responsible for the technical delivery, including co-ordinating the other developers
-  Developers: Persons responsible for architecture and delivery of individual components

--

Cross-team roles

- Product Manager: Person who has sign-off for the product. Generally a person from the leadership team, who is responsible for the overall strategic content of the product as a whole. They have direct oversight of the Product Owner
- Technical Architect: The back end lead (or delegate) who is responsible for the solution architecture as it fits within the larger product roadmap

--

Cross-team roles (continued)

- User Experience Developer: The front end lead (or delegate) who is responsible for the user experience as it fits within the overall interaction designs
- Additional Stakeholders: Interested parties such as Client Experience, Partner Manager, as required (varies depending on project)
- User Acceptance Team: Additional Stakeholders plus the Tester and Business Analyst, who perform testing to support final sign-off

---

## Formalised, scheduled meetings

A meeting has a purpose.

--

## Typical project kick-off meeting

- Product Manager
- Product Owner
- Developers
- Additional Stakeholders
- User Experience Developer
- Technical Architect

--

## Daily Project Stand-Up

(Replaces current stand-up)

- Product Owner
- Developers
- BA & Test team (Optional)
- Additional Stakeholders (Optional)
- Other team (Optional)

--

## Showcase (End-Of Cycle)

(Replaces current ad-hoc presentations)

- Product Manager (Presents the work)
- Product Owner
- Developers
- BA & Test
- Additional Stakeholders (optional)

A showcase is where we demonstrate to the rest of the business all of the work that has been completed during a cycle.

--

## Retrospective (End-Of Cycle)

- Product Manager
- Product Owner
- Developers
- BA & Test
- Additional Stakeholders (optional)

The retrospective is an analysis of what did and did not work during a project cycle.

--

## Retrospective (End-Of Cycle) - continued

We should embrace the notion of iterative improvement. This is the forum to raise possible changes or process 'experiments', which can be condcuted during the next cycle. Previously agreed and trialled processes should be reviewed at the end of the retrospective.

--

## Retrospective (End-Of Cycle) - continued

This should be about not just what went wrong, but also about also what went well. It is about **what can we do better** - not a sledging match; but people should be comfortable raising and receiving any feedback. It is a critical opportunity for growth.

--

## Weekly Technical Catch-Up

(current practice)

This is when the front-end or back-end team meets in full to discuss all projects, work, blockers and upcoming work. Option to share any cool or interesting technology.

This is an opportunity for each team to ensure they are aware of what everyone else is working on at a detailed technical level, as well as understand what major work is scheduled.

--

## Weekly Dev Leads Meeting

(current practice)

The CTO meets with the Dev Leads plus BA to ensure that there is transparency on upcoming priorities and projects.

This is also where the Leads communicate concerns upwards

---

## First Steps

Where should we begin?

--

### Tactical

Finish outstanding Chargify migration work

--

### Strategic

Two critical projects:

- On-boarding (Solotel) - Better TaxFileNumber support, Checklist detail enforcement, and Super details.
- Deloitte Enhancements - Enabling integration with System Sign-On, Customisation, Theming, and other work.
