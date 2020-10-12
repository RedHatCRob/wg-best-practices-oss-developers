# Best Practices for Open Source developers Working Group - Meeting Minutes

<details>
 <summary>Regular meeting - October 12th, 2020</summary>
 
 ## Intro
 *  
 
 ## Quick status on in-flight projects
 ### Fundamentals course
 
 
 ### SKF
 
  
 
 ## CII Best Practices badge project: which working group of the OSSF?
 
 
 
 ## Inventory project:  
 
  
 
 ## Other subjects
  

</details>


<details>
 <summary>Regular meeting - September 28th, 2020</summary>
 
 ## Intro
 * Rob Cuddy, from HCL Technologies
 
 ## Quick status on in-flight projects
 ### Fundamentals course
 Things are on track. Content is frozen, conversion to EDX is in progress.
 ETA is still end of October, it would be awesome, though November is more realistic.
 We should have the sign up by the end of October.
 
 **Early access possible?**
 
 Certainly possible, David will ask: Yes, beta access 1w before the release.
 
 **Cost?**
 
 Free for taking the course. Fee for the certification? David will ask
 
 ### SKF
 
 * UI: All the pages done.
 * TODO: Design patterns
 * TODO: CodeQL queries - Xavier to touch base with Glenn / Riccardo 
 
 ## CII Best Practices badge project: which working group of the OSSF?
 
 See https://github.com/ossf/wg-best-practices-oss-developers/issues/23
 
 It doesn't easily fit into just one group. Focused on measuring projects, which fits perhaps better into the "Security threat" group. There should be one home, as a working group, but it's important to set up a collaboration between the 2 groups. Whichever WG is the home, both groups should be involved.

* Crob: feels strongly that it should be part of this group, to focus all developer-focused activities in one group.
* Bjorn agrees with Crob. It's def about the best practices. Fair point that the name confusion couldbe a problem if the CII Best Practices goes into another group than the Best Practices WG
* Dave + Pavel + Rob Cuddy votes for this group
* Xavier: Not a strong opinion but thinks it should belong to the other group. This WG is focused on the individual, that other is focused on the projects.
* Rob: Anything that can bring visibility on best practices to individuals is valuable

David will bring that to the other WG, and eventually bring it to the TAC
 
 ## Organization: Nominate new lead / co-lead?
 CRob is volunteeering
 
 ## Inventory project: Should we start?
 
 https://github.com/ossf/wg-best-practices-oss-developers/blob/main/docs/inventory.md
 
 * CRob: This group should have these resources. The integration part will def be more challenging and could come in a later phase.
 * Rob: Connection to other tooling and categorization make a big difference. About ranking: loves that it comes from the actual user's perspective. 
 * When the inventory integrates with SAST tools within the IDE, do you get remediation advices associated? Depends on the tool itself, but yes. 
 * SKF intended also to consume the inventory. In the meantime, SKF can add other sources, waiting for the inventory to be live.
 
 ## Other subjects
 * Xavier's zoom virtual background is from [Miyazakis's Spirited away](https://en.wikipedia.org/wiki/Spirited_Away), awesome movie highly recommended by this group.

</details>

<details>
 <summary>Regular meeting - September 14th, 2020</summary>

 ## Introduction of newcomers
 
 ## OWASP SKF Demo
 Glenn made a demo of the Security Knowledge Framework. Comments and questions:
 * The framework is open to external contributions. One can create new design patterns and enrich the framework
 * **Can the entries be mapped to other requirements than ASVS / MASVS?** This working group intended to also deliver a unified requirements definition (The *Inventory* project). Once done, this unified list would have been used for the mapping. This project has been paused because of lack of resources.
 * Demo of the upcoming version available at https://beta.securityknowledgeframework.org/. Credentials are the same as for the current demo version
 * **Do you have plans to add compliance requirements (e.g. NIST)** No plan, but the platform makes it easy to add requirements, and we want people to contribute.
 * **Concrete next steps**: 
  * Login with ID providers (GitHub, GitLab, Google, Facebook, Twitter ...)
  * Infrastructure for public instance
    * Remarks: this is not blocking the next release. We can release it with the current local deployment solution
 * For the OSSF public announcement: Announce release, and announce plan to provide a public, community-powered instance.
    
 
 ## (Discussion of) proposal from David A. Wheeler
   David A. Wheeler made the following proposal:
   
   The OpenSSF is expected to have a press release at the end of October.
   It would be very good to have a few concrete results to announce then.
   If we want to meet that deadline, some things must happen quickly!
   
   Several people have reviewed the course “Fundamentals of Developing Secure Software”,
   with generally very positive comments. I have tried to respond to all
   feedback (e.g., there's more about privacy, CORS, etc.).
   If this course is to be released by the end of October,
   the course content has to be frozen Sep 15, and this WG needs to
   approve it as an OpenSSF result within a few days (final approval must
   be known by the end of September, and the TAC and GB may need/want to weigh in).
   
   On 2020-09-11 Glenn Ten Cate & David A. Wheeler spent considerable time discussing
   OWASP SKF & the "Fundamentals..." course. They are very different;
   the "Fundamentals" course covers basic fundamentals, while OWASP SKF includes
   mechanisms to identify requirements & a set of labs. We discussed options for
   integrating them more closely in the future, and have some ideas for doing that
   long-term, but it would be risky to try to integrate them into a single
   by the end of October. However, Glenn Ten Cate believes they can have a useful
   capability by the end of October. Both agreed that the SKF labs, for example,
   are an excellent complement to the "Fundamentals" material.

   I propose that:
   * This WG vote whether or not to approve releasing the
     “Fundamentals of Developing Secure Software” course as an OpenSSF course.
     The vote can be electronic; if desired here's a Doodle poll to do it:
     <https://doodle.com/poll/wkwgpzmbhmmgdy3f> . I propose a deadline of
     2020-09-17 23:00 Eastern Time (this upcoming Thursday).
     
   I also propose that:
   * The OWASP SKF work be encouraged to be developed so that there will be
     a releasable version at the end of October (e.g., with enough
     labs that people can clearly see its utility).  The WG would vote later
     (say in early October) on whether or not it's ready at that time.
     Of course this work could continue to be refined after that time.

## Actions
- [ ] All: Vote on the course
- [ ] Glenn: Cost estimation for the SKF public infra

</details>
   
<details>
 <summary>Regular meeting - August 31th, 2020</summary>
 
 ## Round table
 We welcomed new members and made a quick round of introductions
 Attendees: Bjoern Kimminich, Crob, Dave Russo, David Wheeler, Glenn Ten Cate, Riccardo Ten Cate, Dan Lorenc, Pavel Malinov, Xavier René-Corail 
 
 ## Presentation of the working group
 - Overview of the mission
 - Overview of the 3 initial projects, and status
   - Inventory and community paused
   - Learning platform
   
 ## Presentation of the learning platform / SKF
 Glenn and Riccardo presented the learning platform, the vision around it, the current status and the upcoming planned features.
 We decided to run a 30min demo and Q&A during next meeting
 
 ## CII Best practices badge
 David gave a presentation of the [CII Best practices badge](https://github.com/coreinfrastructure/best-practices-badge/blob/master/doc/cii-bp-badge-intro.pptx)
 
 ## Course draft
 David is working on a course to be published on edx. Freeze date is middle of next month. Should be ready for Nov 3rd for an announcement of new releases from the OSSF. 
 Feedback welcome, send him an email to get access. 
 
 ## Actions
 - Glenn / Riccardo: Prepare a demo + walk through SKF (please no demo while driving the car Glenn)
 - Glenn / David: Think about how the edx course (or similar others) can be "integrated" into the learning platform, contribute to the learning path, etc.
 - All: reflect about the CII best practices badge and how it could help our projects. It was not originally in our vision to score the projects, but a badge could obviously contribute to the community effort. Another idea could be that the criteria could link to the respective entries in the learning platform?
 - All: propose other ideas for next meeting's agenda

</details>

<details>
 <summary>Regular meeting - August 17th, 2020</summary>

## What happened since last meeting?
 - Demo of the new SKF, with UI improvements. 
    - On track to release a MVP end of this month

![New UI](./img/New-SKF-UI.png)

 - Request for resources for the SKF cloud formally [documented](https://docs.google.com/spreadsheets/d/18hkrbXcDMpbrzAyFJCqXm0jKG9mZ4bQchf1RP9pCBOQ/edit#gid=361723822)
   - 120 dev hours for SKF
   - 180 dev hours for SKF-Labs
   - 8h / week for operations
 - 2 candidates reached out to join the working group - intro discussions planned

## Coming next
 - API endpoint that can be called for example from GitHub to get the learner achievement and display something on the GitHub profile
 - Better structure the Juice shop labs: limit to the ones that have a tutorial
    - Adding tutorials to the ones without was discussed, but in some case it doesn't make sense, and there are not so many where it would make sense
 - Add the possibility for the learner to contribute to the labs by opening a PR on the community instance

## Questions
 - For the TAC: 
    - Resources (see above)
    - Cloud provider preference for the hosting? 
    - Should the project move under the OSSF GitHub org or can it stay under Glenn's personal ownership?
        - OWASP didn't previously force it to be under OWASP
    - So far SKF is an [OWASP project](https://owasp.org/www-project-security-knowledge-framework/). How will the OSSF promotion happen?
        - Logo, text on the SKF page?
        - Referencing the SKF project on the OSSF page?

## Actions
 - [x] Raise these questions to the TAC (Maya) https://github.com/ossf/tac/issues/19
</details>

<details>
 <summary>Regular meeting - August 3rd, 2020</summary>

## What happened since last meeting?
### Organization
- Migration of the old OSSC repo to the new OSSF repo
- Who is the next group leader? 
  - Elie originally volunteered but is no longer available
  - Rotating leader?

### Learning platform
- Good progress on the UI revamping: 99% of the UI is ready
- The API work is started
- Still on track for end of August
- There is already a placeholder for the CodeQL section of the labs

## Concerns / discussions
- When the project is not originated by the OSSF, but is an existing project that the OSSF contributes to, promotes ... will there be an ownership / license transfer of this project?
- Decide the preference for the deployment of the learning platform: k8s? on what cloud service?

## Actions
- [ ] Glenn: Prepare demo of the learning platform for next call
- [ ] Xavier: Invite members to the org and give appropriate permissions to the repo
- [ ] Glenn: Draft a plan for explaining resources needs (development and operations)
- [ ] Xavier: Raise the deployment question to the TAC 
- [ ] Xavier: Keep the lead of the group for the coming weeks, until a better solution is found
</details>

<details>
 <summary>Regular meeting - June 1st, 2020</summary>
## What happened since last meeting?
**From last meeting**
- Glenn / Riccardo: Implementation of the Webhook solution in SKF, to see what is missing, what is working
- Sara: work on a list of tools easy to use for open source developers
- Xavier: Ping the GitHub learning lab team for a follow-up of the SKF discussion
  - They are ready to resume the discussions. Next steps: Xavier sets up a meeting.
</details>

<details>
 <summary>Regular meeting - May 18th, 2020</summary>


## What happened since last meeting?
- Glenn and Riccardo: Working on integrating SKF with Identity providers ==> possibility to sign up with GitHub.
- Progress on the Inventory format
- Learning Platform: Demo of a webhook for exercise providers to notify the learning platform that the learner has completed an exercise

## Concerns / discussions

### Learning Platform
* ❓ Decision on [Solution webhook](https://github.com/Open-Source-Security-Coalition/Best-Practices-for-OS-Developers/blob/master/learning-platform.md#solution-webhook) payload specification of the Learning Platform
  * ℹ️ Show/demo [implementation of webhook call in OWASP Juice Shop](https://github.com/bkimminich/pwning-juice-shop/blob/develop/appendix/integration.md#challenge-solution-webhook) for MVP
  * ❓ Discuss [MVP implementation idea on OWASP SKF side](https://github.com/Open-Source-Security-Coalition/Best-Practices-for-OS-Developers/issues/3) for MVP
  
**Decision for next steps:** Finish the MVP (sign-up with GitHub, webhook callback, and perhaps integration with GitHub user profile) before making a full demo to the other working groups.

### List of tools to re-use for the inventory
* Sara just received the SANS-curated list of tools for security and forwarded it, as it could serve as input within the inventory. 
  * Seems to us very Network-oriented, and perhaps not for the Open Source developers who are learning how to write secure code
  * But they can be interesting to put in the inventory anyway as ways to test that your application is secure 
* F5 is also preparing a list of tools
* OSS User stories for implementation of ASVS requirements https://twitter.com/madplatt/status/1259874312846282754


## Actions
- Glenn / Riccardo: Implementation of the Webhook solution in SKF, to see what is missing, what is working
- Sara: work on a list of tools easy to use for open source developers
- Xavier: Ping the GitHub learning lab team for a follow-up of the SKF discussion
</details>

<details>
  <summary>Regular meeting - May 4th, 2020</summary>

## What happened since last meeting?
- **Elie:** Deeper discussions wrt Inventory. Possibility to merge with a current OWASP project "Integration Standards". 2 meetings (on functional requirements, and on technical archi). First MVP could come in 1 month  / 2 months.
- **Bjorn:** Proposal of payload that could be sent from an exercise to the learning platform, for the central progress tracking. Request for feedback sent. With the goal of get to a unified payload.
- **Xavier / Riccardo / Glenn:** Preliminary discussions with GitHub Learning Lab - They'll get back to us

## Concerns / discussions
- Discuss with other working groups.
- Sara / F5 willing to contribute to some projects. For example pulling vuln data and mapping to the inventory.
- What is the status on funding? We need money to fund projects, but also to hire people (community manager, operations for the learning platform ...)
- If we have this money right now, would it help progress on the learning platform?
  - Yes, we could definitely hire 1-2 more developers to build the features
- Community framework could also benefit from money?
  - We need to first build the 2 other projects 
  - Also, we could leverage on the existing communities (SKF...) to build our community

## Actions
- [ ] Come up with a concrete list of questions to ask the other working groups
- [ ] Elie / Sara to have a call on the inventory to define collaboration opportunities
- [ ] Sara to sync with Hauwa about funding status
</details>

<details>
  <summary>Regular meeting - April 21, 2020</summary>

## What happened since the last meeting? 

* Xavier: Started filling this repository and organizing. 
  * ATTENTION POINT: The OKRs we discussed together were until June 2020. In order to put OKRs for end of 2020, I just extrapolated the ones we had, but we need to revisit them together to make sure we all agree with them
  * There is also a [project board](https://github.com/Open-Source-Security-Coalition/Best-Practices-for-OS-Developers/projects/1) where we can all track tasks and progress. You can either create a card on the fly, or create an issue and reference it in the project board.
* Xavier: :snail: I am late on setting up discussions with the GitHub Learning Lab team re: the integration in SKF.

## Discussion items
### OKRs
As indicated above, Xavier took the liberty to extend the OKRs to the end of the year. Let's review them

### SKF Checklist
Discussion around the [SKF checklist feature](https://www.youtube.com/watch?v=D5ExXEr-x-U) and its integration with GitHub projects

### Inventory User Stories
Discuss the User stories proposed by Elie

## Concerns 

* **Working group leadership**. With the current COVID-19 situation, we are all struggling to sustain our normal productivity level, and it can be difficult to work on this group in addition to our normal duties. I recommend a more flexible approach than relying on a unique "leader / co-pilot" pair, for example at each meeting, the members who feel comfortable to lead the group during the 2 coming weeks volunteer. 
- On the other hand, the group is acually delivering, and working well. Others are more interested in content, not in admin stuff. Proposal: Xavier and Elie are pilot / co-pilot for the time being.


## Actions
- Everyone: Flesh the OKRs with more concrete success measures
- Elie / Riccardo: Flesh the inventory user stories
- Elie: Give details about the Requirement id project and how it helps the inventory project
- Xavier: Set-up meeting with GH Learning Lab for the integration into SKF
- Xavier: (Once the inventory user stories are more detailed) Set up a meeting with the relevant GH experts to discuss chatbot integration


## Next meeting?
- Not possible at this time for Sara. Can we move it 1h later? Or same hour on Wednesday?
  - Decision: Go back to Mondays
</details>

<details>
  <summary>Regular meeting - April 06, 2020</summary>

## What happened since the last meeting? 

*   Xavier: Raised to the steering committee the concerns that we discussed last week. No solution yet, but just the acknowledgement that it’s being worked on
    *   Neutrality wrt commercial tools: This is currently being worked on by the steering committee. They intend to write bylaws for the coalition.
    *   We need contributors to develop, maintain and operate the learning platform.
        *   The committee is also working on funding (which would allow us to hire)
        *   Several members would like to allocate collaborators to work for the coalition
*   Xavier: didn’t have time to work on the group collaboration tools as promised but a GitHub organisation has been created for the coalition, and for next meeting we’ll have a repo where we can store all our docs, and a board to follow-up on our tasks. 
*   Riccardo: Integration of OWASP Juice Shop into SKF
    *   With SKF we basically have the MVP we want
    *   We have a demo of integrating a new course platform
    *   **Next:** Try to integrate the GitHub learning platform into SKF
*   Bjorn:
    *   Learning path demo in Juice shop - levels are unblocked one after the other
    *   **Idea**: link the badges / progress report to projects / users on GitHub
        *   Add a disclaimer that these badges just mean that you spent time on learning security, that you are “aware”, not that your project is more secure than another, or that you’re an expert. 

## Concerns 

*   Do we have enough people / time in this working group to achieve our objectives?  

## Actions

*   Setup the Inventory user stories - _Elie_
    *   _[https://docs.google.com/document/d/1GndQuUOUAARc7RmAH0oXmbcLb1vZw2g8cAznICAK3oc/edit#heading=h.tqyztji4w9if](https://docs.google.com/document/d/1GndQuUOUAARc7RmAH0oXmbcLb1vZw2g8cAznICAK3oc/edit#heading=h.tqyztji4w9if)_
*   Understand other WG’s needs to be tackled in the Learning Platform and Inventory
*   Assess what is missing in the community as information and knowledge, which shouldn’t be a deliverable for next meeting (this is a goal by itself)
*   Meeting between GH and SKF in order to identify how the integration could be done -_ Xavier, Riccardo_
*   Discuss possible metrics to be linked to users in the learning platform - _Team_


## Next meeting?

*   Some members from other working groups would like to contribute to this one too, and all meetings are at the same time. Can we find a slot on Tuesdays? 
    *   Tuesday same time works for everyone
</details>

<details>
  <summary>Regular meeting - March 23, 2020</summary>

## What happened since the last meeting?

*   Xavier: Alignment with the Tooling Working Group
    *   In our inventory project, there will be resources but also potentially tools. Once we start building this inventory, we’ll make sure to also get inputs from the Tooling WG.
    *   As part of our learning platform, we value the tools that automatically run checks of the secure code practices in the Pull Requests, as they provide a “learning on the job” approach. This is a criteria that the Tooling WG will take into account when they create their tools inventory and decide which one to focus on.
*   Björn: Learning Platform Ideas
    *   see [https://docs.google.com/document/d/1KQ8bT87A0X2wJ9GNwSOz7nJwSK70symA4hs-nFLw8dE/edit](https://docs.google.com/document/d/1KQ8bT87A0X2wJ9GNwSOz7nJwSK70symA4hs-nFLw8dE/edit)
    *   Who will build the platform?
        *   Take advantage of existing platforms?
            *   Plug-in the existing courses (Juice, SKF labs, GitHub Learning Lab ...)
        *   But it’s gonna be really hard to incorporate any course into an existing platform - It needs changing the API of the existing ones to match the contract that we need for the courses we want to plug in
        *   Building the platform ourselves from scratch give us flexibility
    *   Riccardo can contribute on the platform with the experience of SKF (reusable knowledge about deployment of the courses into Kubernetes cluster)
        *   Not reuse the complete platform, but the core functionality can be reused. Good starting point for the platform.
    *   **We need a dedicated development / ops resource to build and maintain this platform**
        *   Open source projects with enough contributors. 
        *   The coalition companies could take up the challenge to contribute and maintain this project
        *   We should also reach out to the open source community
        *   Start with a core (from coalition companies) and then reach out to the community 
        *   Or we get funds and hire 
        *   And who will be the owner organisation of the project?
    *   Liked the badge system, gives incentives to learner
        *   Post MVP: integrate learning badges with security assessment badges on projects committed (something to signify learning vs real world application)
*   Elie: Vulnerability Disclosure Cheat Sheet - Shared with the Vulnerability Disclosure WG, waiting for feedback from their side.


## Concerns



*   Involvement of “Companies” - Why commercial product focus and not Open Source?
    *   Commercial products can work against us
    *   We don’t want to compete with other companies, who will see us as a threat 
    *   Best case is that we can instead give visibility to these other companies if we integrate their tools into our offer
    *   It would be easier if we focus on the open source projects - There are many of them
    *   If we focus only on the integration of existing courses, then we won’t be seen as competition. 
    *   No commercial should be interested in building a meta-platform integrating the courses of their competitors, so the threat is not that big.
    *   The platform must not be an OWASP project, and serve as a lead generator
    *   It makes sense to start with only open source projects as part of the courses we plug in
*   Neutrality of this working group - Leftover from last meeting
    *   We don’t want to push forward or resell any type of product
    *   At best open source, at least free for open source projects
    *   Being discussed in Steering committee 

## Actions

*   Setup the collaboration environment (Drive Folder, Trello Board, anything else?) - _Xavier, Elie_
*   Brainstorm the possible learning platform architecture
*   Adapt the Learning platform stories and MVP to address the feedback and concerns discussed above (integration of only open source courses, start with integration of existing courses, ...)
*   User stories for inventory
*   Reach out plan (through students, social media, etc.)

## Next meeting?

*   2 weeks, this slot or 1h later
</details>

<details>
  <summary>Regular meeting - March 09, 2020</summary>

## Intro

*   Welcome our newcomers - introductions
*   FYI: the WG group leads will be convened towards the end of the week or early next week to share readouts from initial meetings, progress, and areas for improvement
*   Anything else to add to the agenda?

## Working group story 

I tried to recap the discussions from the kickoff meeting into a story that we could easily communicate to others, and to the outside world as part of the future coalition website. I would love your feedback to make it final. 

[Powerpoint pres](https://github.com/Open-Source-Security-Coalition/Best-Practices-for-OS-Developers/blob/master/docs/Best-Practices-for-Open-Source-Developers-Story.pptx)

Feedback:

*   How do we make this widely distributed? → The community project: Highlight this a bit more in the message
*   This is more than the next awesome list, there is the community aspect and the learning path aspects

## Needs

_Discuss needs for each project (People, money, other working groups ...)_

*   General
    *   ...
*   Inventory
    *   **Community feedback and validation**
        *   What is the inventory? Aggregation or references? 
        *   How do we make sure that it’s accepted by the community
    *   **Prioritization criteria definition**
    *   **Stepping back from the existing and create our own inventory with the  important categories**
    *   **Strong domain that others can reference**
    *   **UX, Design and Marketing**
*   Community
    *   Community manager
    *   Weekly content: technical writers
    *   Community strategy
        *   Increasing the overlap of existing communities (sec, dev)
        *   Identify champions  
*   Learning platform
    *   Alignment with Tooling working group to provide enforcement at the level of Pull Requests
    *   Make sure to be integrated into the workflow people already have (IDE, Source control)
    *   The rules should be available in one place as testing data for the tools
    *   Different options for different learners (exercises, videos …)

## What companies should we invite?

Parties that I think should somewhat be involved:

1. Atlassian: https://www.atlassian.com/software-development
2. Portswigger
3. Redhat - They have blogs and documents everywhere
4. Unity: https://github.com/UnityTech/unity-ssdlc
5. Cisco
6. Veracode
7. Checkmarx
8. SecureCodeWarrior
9. Manicode
10. Security Journey

## What project(s) should we focus on?

*   Inventory should start first -- Prioritize the content and tackle them step by step (agile?)
    *   Learning platform can go hand in hand
    *   Community should come later, once we have some material - But community strategy needs to start now

## Define OKRs 

_What are our OKRs (end of June)?_

*   MVP of the inventory 
    *   One collection of existing - prioritized
    *   Gap analysis
*   Community strategy is proposed
*   Scoreboard
*   Learning paths are proposed
    *   One full example is ready

## Concerns

*   Neutrality of this working group - Leave for next meeting

## Actions 

*   Define how this group is going to work together - _Xavier RC, Elie S_
*   Define key players for the needs of this project - Everyone
*   Create user stories for Inventory
*   Create user stories for Learning Platform - _Björn, Glenn & Riccardo_
*   Initiate conversation with the tooling WG and the Security of open source projects WG, at this stage to give them a heads-up about our on-going discussions and future needs. - _Xavier RC_ 
*   Inventory of existing communities and of their strategies (e.g. OWASP, GitHub)

## Next meeting? 

*   In 2 weeks - Monday 23, March
</details>

<details>
  <summary>Coalition Kick-off meeting - Best practices for Open Source developers - February 26, 2020</summary>

## Background

For each working group you’re interested in, consider these questions in advance of the meeting. Please come to the meeting prepared to discuss with your respective working groups. 

During the meeting,  please use this as a tool to jumpstart your discussion and keep notes so that remote participants have visibility into discussions. This shared document lives in the Open Source Security Coalition Google drive for each working group. 

Please note that at the end of this exercise, we will ask each working group to determine a group lead along with a designated co-pilot to help support the lead. Working groups can choose to rotate the group lead and co-pilot roles on a quarterly basis.


## Working Group Members

*   Sara Boddy; F5 Labs [s.boddy@f5.com](mailto:s.boddy@f5.com) 
*   Mary Gardner; F5, CISO (to join periodically) 
*   Elie Saad [eliesaad7@gmail.com](mailto:eliesaad7@gmail.com) -- OWASP
*   Xavier Rene-Corail xcorail@github.com
*   Jennifer Fernick (to join future meetings) [jennifer.fernick@nccgroup.com](mailto:jennifer.fernick@nccgroup.com)
*   Maya Kaczorowski (please add me to future meetings) [mayakacz@github.com](mailto:mayakacz@github.com) 

## Questions 

*   What should be the overall objective for this working group? In other words, think of the objective as what do you hope this group will accomplish? Provide three specific objectives for this working group.   What problem is this working group trying to solve? 
    *   Research to figure out what are the worst issues and write best practices for recommendations
        *   Find the BHAGs + low hanging fruit, prioritize
    *   Resources already available, but how to approach the OS developers? The problem is with the delivery of these resources to the developers
    *   Secure coding and awareness training 
        *   Find luminaries in the community
            *   Give them a voice 
            *   Let’s bring in Manicode 
        *   Continual update process to best practices
            *   Where is this content going to live? 
        *   Others who are doing this @elie
            *   Various OWASP projects
            *   Unity
            *   NCC
    *   **Enforcement?**
        *   Validation / testing tools ran on pull request?  
            *   **Recommended Tools:**
            *   
            *   Incentive / Gamification ideas (focused on learning)
        *   Insecure flags on webpage?
    *   JF: I would be interested in contributing to guidance documents and ideally integrating these with some kind of tooling (such as your mention of validation upon a PR) 
    *   JF: I think it can also be valuable to make recommendations on libraries to depend upon (and which are unvalidated/can pose upstream risk) - especially cryptographically 
*   What type of project work would help support this group’s objective? Provide three project ideas. 
    *   _Gamify, badging systems?_
        *   _Needs a complete community strategy_
            *   _Sara@F5 going to grab format from F5 DevCentral badging and VIP system_
        *   _Our companies’ marketing resources should help _
        *   Release schedule badges - code that’s updated is good!!! 
        *   Code signing?
    *   _Run continuously in the PRs the security checks → allow developers to learn by example; regularly as well (weekly, monthly) to showcase the security level of the project._
    *   _Learning platform to walk developers through secure code_
        *   E.g. _[https://trendmicro.github.io/SecureCodingDojo/codereview101/](https://trendmicro.github.io/SecureCodingDojo/codereview101/)_
        *   
    *   _We need to go through the existing documents and knowledge and figure out how we combine that_
    *   _We should talk to the tooling working group in order to use these tools in our enforcement / learning process_
    *   _How do we bring attention? _
    *   _Reach out to companies that are already working on building these resources, and merge into one_
*   Think about the objectives the group identified above. Illustrate each objective with a concrete outcome or key result.
    *   **_Inventory open source security problems (discovery and analysis), tools training that exists, etc. by June?_**
        *   _[Trend Micro Secure Coding Dojo](https://owasp.trendmicro.com/public/index.html) _
    *   _Best practices, recommended tools, etc. _
        *   _Inventory, know what people are using?_
            *   _Community source this_
        *   _By expertise level - something for newbies!_
        *   _Get involved in early EDU, Girls Who Code, STEM schools, UW Cyber School? _
    *   _Community & Gamification - **what by June?**_
        *   Best practices for gamification and community within the open source community - what will work?!
            *   Security score
            *   Integration with enterprise tools
            *   Managed/updated/not a garage project
            *   Trusted Dev? Community voted expert?
            *   Level of Expertise
            *   VIP Program? (what value do they get out of this? Recognition value) 
        *   What tech do we need? Community platform? Auth? How much open source vs 
            *   Ops requirements and staff? Investment?  
    *   _Enforcement_
        *   Tooling? “learning by example” process
        *   Influence the tooling WG to include the requirements re: learning process
            *   Feedback loops?
*   Is there anything else to address? 
*   Who is your group leader? Who will serve as co-pilot? 
    *   Leader: Mary Gardner
    *   CoPilot: Sara Boddy   
        *   Best practices and testing: Elie Saad
        *   Community and gamification: Sara Boddy
    *     		
*   When will this working group meet next? Please aim for dates within the next week. 
    *   Ops board? Kanban board. Trello?
        *   Mary has resource that might help manage us (scrum master)
    *   Sprint? Meet Monthly? (Sprinting might be too much structure for the OpenSource community)
    *   **Always meet 1 week before steering committee.**  

## Notes

Pull Request Template:

[ ] Parametrized query

[ ] Proper input sanitization occured

Etc.

For requirements: ASVS -> Applications in general; MASVS -> Mobile

For threat modeling: PyTM, ThreatSpec

For code best practices: Proactive Controls, CheatSheet Series

For testing: WSTG -> Web; MSTG -> Mobile

*   Community manager for animating the OS maintainers community should be dedicated
    *   By June we’ll have the plan and strategy ready by June, and then we’ll derive the needs in terms of money, people, etc.
*   Guidance for owners of packages, different from a standard contributor
    *   Different according to the packages (those who are used in prod)
    *   → these are different personas in the community strategy
</details>
