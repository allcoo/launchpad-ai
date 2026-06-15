 Launchpad AI

 Turning Overwhelm Into Action, One Step at a Time

 Overview

Launchpad AI is an executive-function support agent built in Azure AI Foundry. The project is designed to help users overcome overwhelm, procrastination, task initiation challenges, and unclear starting points by transforming large goals into actionable next steps.

Rather than functioning as a traditional productivity application that simply stores tasks, Launchpad AI acts as an AI-powered coach that helps users identify barriers, create realistic plans, begin focused work sessions, and recover progress after interruptions.

The prototype was developed for the Microsoft Agents League Hackathon Reasoning Agents track.



 Problem Statement

Many people know what they need to do but struggle to get started.

Common barriers include:

* Overwhelm
* Procrastination
* Analysis paralysis
* Perfectionism
* Unclear starting points
* Difficulty resuming work after interruptions

Existing productivity tools are effective at organizing information, but they often fail to help users take the first step.

Launchpad AI was created to bridge the gap between intention and action.

---

 Solution

Launchpad AI helps users:

1. Identify their primary barrier.
2. Understand why the barrier is creating friction.
3. Break goals into manageable milestones.
4. Identify the smallest actionable next step.
5. Begin short focused work sessions.
6. Create progress summaries for future recovery.

The goal is to reduce cognitive load and make meaningful progress easier to achieve.

---

 Architecture

The MVP is implemented as a single Azure AI Foundry agent using structured role orchestration.

The agent simulates a multi-agent workflow through specialized reasoning roles.

 Executive Function Agent

Identifies barriers such as:

* Overwhelm
* Distraction
* Perfectionism
* Ambiguity
* Time blindness
* Restart friction

 Learning Path Agent

Determines what the user is trying to learn or accomplish.

 Study Plan Agent

Breaks goals into realistic milestones and action plans.

 Focus Coach Agent

Provides the smallest possible next step and recommends focused work sessions.

 Progress Recovery Agent

Creates summaries that help users resume progress after interruptions.

---

 Microsoft Technologies Used

* Azure AI Foundry
* GPT-4.1-mini
* Azure AI Search
* Foundry Knowledge Base
* Foundry IQ Retrieval
* Azure Free Subscription

---

 Knowledge Sources

The prototype includes synthetic knowledge documents used to support retrieval and grounding.

 Executive Function Guide

Contains information related to:

* Task initiation
* Overwhelm
* Productivity barriers
* Focus strategies

 Security+ Study Guide

Contains information related to:

* Security+ learning domains
* Study scheduling
* Certification preparation

---

 Example Workflow

 User Input

"I need to study for Security+ but I keep getting overwhelmed. I don't know where to start and I keep putting it off."

 Launchpad AI

* Identifies overwhelm as the primary barrier.
* Explains why the barrier is creating friction.
* Breaks the goal into milestones.
* Recommends a focused study session.
* Provides a realistic next action.
* Creates a progress summary.

The same workflow can be applied to:

* Certifications
* College coursework
* Job applications
* Household organization
* Personal projects
* Homelab builds
* Creative work

---

 Future Improvements

Future versions of Launchpad AI will include:

* True multi-agent orchestration
* Persistent memory
* User profiles
* Long-term progress tracking
* Adaptive coaching
* Microsoft 365 integration
* Calendar and task synchronization
* Personalized learning recommendations

---

 Responsible AI

Launchpad AI is not intended to diagnose, treat, or replace professional medical or mental health services.

The system provides productivity and executive-function support through planning, task decomposition, and focus coaching.

All demonstration data used in this project is synthetic and contains no real customer, employee, or medical information.

---

 Author

Robert Couch

Microsoft Agents League Hackathon Submission
