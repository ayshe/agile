# Development Team Structure

---

## Notes on Terminology

- *BAU* - Business as Usual
- *Prod Support* - Developer activities required for BAU
- *Critical Path* - Sequencing and delivery time frames
- *LOB* - Line of Business 

---

## Goals Of This Proposed Change

- Improve project execution and planning
- Protect our critical path from BAU
- Provide structure to our project work
- Actively involve other LOBs in projects

---

### Improve Project Execution and Planning

Projects have a life cycle, with stakeholders and specific accountabilities

We need to be better at identifying who:

- Can make decisions
- Must be consulted
- Is responsible for different parts of the project
- Will do what work

--

### Protect Our Critical Path From BAU


As a team, we are highly reactive, responding to prod support issues with the highest urgency, which is often appropriate. However, this means that our critical path is neglected, and strategic projects do not get completed.

--

### Provide Structure To Our Project Work

Our informal project structure has been identified as a major obstacle to quality and timeliness of our current project work.

--

### Actively Involve Other LOBs In Projects

Understanding the needs and goals of different business areas is important. We should actively involve other areas, such as Client and Partner Experience.

---

## Two Parallel Streams Of Work

Two parallel teams, running in cycles of up to 6 weeks.

- Tactical
- Strategic

---

## The Tactical Team

The most similar to how we currently work.

Tactical projects are ones needed in the short to immediate term, and includes production support activities.

Tactical projects run in shorter cycles of 2-3 weeks.

--

### Examples Of Tactical Projects

- Marketing and SEO updates to the public website
- Bugfixes
- Incremental improvements to the UI (#quickwins)
- Postgres upgrade

The Tactical team are Boy Scouts. Their main focus is helping the business operate smoothly.

--

## The Strategic Team

This team is protected as much as possible from BAU, a work that is on the critical path.

Strategic projects are no longer than 6 weeks

--

### Examples Of Strategic Projects

- OpenAPI modules
- React MVC replacement for Struts/Tiles
- Looker reporting

The strategic team work mostly in the areas of major improvements, refactoring, and new build.

---

## Roles (Per Team)

<dl>
  <dt>Product Owner</dt>
  <dd>Directs the team to produce the agreed solution, and is the representative of the business and clients
  </dd>

  <dt>Team Lead</dt>
  <dd>Responsible for the technical delivery, including co-ordinating other developers</dd>

  <dt>Developers</dt>
  <dd>Responsible for architecture and delivery of individual components</dd>
</dl>

--

### Cross-team roles

<dl>
<dt>Product Manager</dt>
<dd> Person who has sign-off for the product. Generally a person from the leadership team, who is responsible for the overall strategic content of the product as a whole. They have direct oversight of the Product Owner</dd>

<dt>Technical Architect</dt>
<dd> The back end lead (or delegate) who is responsible for the solution architecture as it fits within the larger product roadmap</dd>
</dl>

--

### Cross-team roles (continued)

<dl>
<dt>User Experience Developer</dt>
<dd> The front end lead (or delegate) who is responsible for the user experience as it fits within the overall interaction designs</dd>

<dt>Additional Stakeholders</dt>
<dd> Interested parties such as Client Experience, Partner Manager, as required (varies depending on project)</dd>

<dt>User Acceptance Team</dt>
<dd> Additional Stakeholders plus the Tester and Business Analyst, who perform testing to support final sign-off</dd>
</dl>

---

## Formalised, Scheduled Meetings

A meeting has a purpose.

--

## Typical Project Kick-Off Meeting

- Product Manager
- Product Owner
- Developers
- Additional Stakeholders
- User Experience Developer
- Technical Architect

--

## Daily Project Stand-Up

- Product Owner
- Developers
- BA & Test Team (Optional)
- Additional Stakeholders (Optional)
- Other Stream (Optional)

--

## Showcase (End-Of Cycle)

(Replaces current ad-hoc presentations)

- Product Manager (Presents the work)
- Product Owner
- Developers
- BA & Test
- Additional Stakeholders (optional)

A demonstration to the rest of the business all of the work that has been completed during a cycle.

--

## Retrospective (End-Of Cycle)

- Product Manager
- Product Owner
- Developers
- BA & Test
- Additional Stakeholders (optional)

An analysis of what did and didn't work during a cycle.

--

## Retrospective (End-Of Cycle) - Continued

We should embrace iterative improvement. This is the place propose changes or process 'experiments', which can be conducted during the next cycle.

Implemented changes are reviewed in the next retrospective.

--

## Retrospective (End-Of Cycle) - Continued

This is about not just what went wrong, but also about also what went well.

It is about **what can we do better** and provides a critical opportunity for growth. It is not about pointing fingers or sledging.

--

## Weekly Technical Catch-Up

(Current Practice)

This is when the front-end or back-end team meets in full to discuss all projects, work, blockers and upcoming work. Option to share any cool or interesting technology.

This is an opportunity for each team to ensure they are aware of what everyone else is working on at a detailed technical level, as well as understand what major work is scheduled.

--

## Weekly Dev Leads Meeting

(Current Practice)

The CTO meets with the Dev Leads plus BA to ensure that there is transparency on upcoming priorities and projects.

This is also where the Leads communicate concerns upwards

---

## First Steps

Where should we begin?

--

### Tactical

Finish remaining Chargify Migration work

--

### Strategic

Deloitte Enhancements:
- Enabling integration with System Sign-On
- Customisation
- Theming, and other work.
