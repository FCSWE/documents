# Furry Convention Software Engineers - Kick-off Meeting Agenda

**Objective:** Establish the mission statement for developing open, reliable, and scalable convention software; discuss future communication and collaboration options.

**Moderator:** Raymond Feesh **Duration:** 1.5 hours **Location:** Remote via Telegram

**Date 1:** Saturday, 2025-03-01 CET 20:00 ([UTC 19:00](https://www.worldtimebuddy.com/?qm=1&lid=8,205,3469058,100,12,13,30,22&h=12&date=2025-3-1&sln=20-21.5&hf=1)) **Meeting Minutes:** Smiles **Time Keeper:** Tea

**Date 2:** Saturday, 2025-03-08 CET 20:00 ([UTC 19:00](https://www.worldtimebuddy.com/?qm=1&lid=8,205,3469058,100,12,13,30,22&h=12&date=2025-3-8&sln=20-21.5&hf=1)) **Meeting Minutes:** Zynth **Time Keeper:** tba (volunteer wanted)

## 1. Welcome, Background & Context (10 min)

*   Brief introductions of the conversation starters
    
*   Overview of the initiative and why we’re here
    
*   Recap of prior discussions (panel insights, existing challenges)
    
*   Brief summary of the key issues in convention software development:
    
    *   What core functionalities must be covered by “Convention Software”? (e.g., registration, scheduling, logistics)
        
    *   Existing software solutions used by different cons (survey results, insights)
        
    *   Addressing scalability & flexibility for small vs. large events
        

## 2. Open Discussion: Project Objectives (40 min)

*   **Defining a Mission Statement**: What are we trying to achieve?
    
    *   What should be standardized across conventions?
        
    *   How do we balance **flexibility vs. interoperability**?
        
*   Agreeing on a **high-level vision** for the project
    
*   **Naming**: Survey results, brief discussion
    

## 3. Communication, Collaboration Model (20 min)

*   **Collaboration model**: Open-source contribution, governance
    
*   **Transition from Telegram to GitHub Discussions**:
    
    *   Structure & moderation
        
    *   How we ensure participation & continuity
        
*   **Workgroup formation:**
    
    *   How should teams be structured? (By feature, by expertise, by con size?)
        
    *   Who will coordinate each team?
        
    *   Defining initial focus areas (e.g., Registration, APIs, Logistics, Extensibility)
        
*   How do we ensure cross-team collaboration and alignment? Who is keeping track of the project objectives as a whole?
    

## 4. Next Steps & Action Items (15 min)

*   **Task Assignments:**
    
    *   Who is gathering requirements?
        
    *   Who is analyzing existing software?
        
    *   Who is setting up GitHub, documentation & guidelines?
        
*   Planning the next meeting & key milestones
    

## 5. Open Q&A & Closing (5 min)

*   Final thoughts and additional points
    
*   Wrap-up and next steps
    

# Minutes (Saturday, 1st of March)

## Introduction

**Raymond**: Why are we here? We (NFC) noticed a pattern that convention software doesn't always work as well as it could or should. The idea is to start a conversation about helping each other because it seems like conventions generally don't collaborate unless there are staffers who are working more than one event. It feels like every new event has to reinvent the wheel unless they have a contact from an established event helping them with things like registration software, managing dealers, etc. Even big cons struggle sometimes, so there may be an opportunity to reduce duplication of effort in various parts of event running.

After the NFC panel, we (NFC) figured that we (collectively as a worldwide community) could document standards, pain points, things to watch out for, and pitfalls to avoid, so that conventions can benefit from each others' experience.

This initiative is currently indeterminate in scope, but just connecting people is already helping.

As an example of a pain point, at NFC, there was an issue with mobile app login not working. There must be a better way: common ways to do things like presenting the schedule. We don't want to have to have huge IT departments working on the same things in different ways at each event.

Raymond has experience organizing across organizations. (Example: UK Furmeet cross-organisation moderation)

Obviously we can't force people to do things, but we can make guidelines and recommendations, and people can make their own decisions. (Consent and organizational sovereignty.)

## Discussion of objectives

The initial conversation at NFC and in the group concluded that we want this to mostly be high level: documentation, guidelines, reports, standards. For example: scheduling schema / API, possibly even a unified application for all convention schedules in the future.

**Petokikka/Question**: What should a hypothetical unified software have in terms of features?

**Raymond/Answer**: No specifics yet; the goal is to focus on guidelines for now so that people can use those for future interoperability.

**Petokikka/Question**: What kind of guidelines?

**Raymond/Answer**: API standards for e.g. scheduling, dealers, to enable future collaboration on actual software. Another option is to survey existing solutions; evaluate what works, doesn't work, and/or used to work; then understand how things changed over time and document those architecture decisions.

Another example of where our scope could be: a Swagger showing the request paths, queries, bodies, expected response space.

Of course, we can't force people to use our schema or guidelines, but we can establish the means for collaborating to encourage people to work with us instead of having to roll their own everything.

**Stytch/Question 1**: Do we want to limit scope to fur cons, or allow more general use e.g. an anime con?

**Stytch/Question 2**: Could our MVP just be a demo of the schema / API / data structures / interactions?

**Raymond/Answer 1**: If other cons can find use, then absolutely, with the caveat that fur cons tend to be nonprofit and others tend to be for-profit, which might result in different requirements.

**Raymond/Answer 2**: Yes, a working example should be an eventual goal; docs first, software later.

**Stytch/Comment**: On the topic of being less specific to fur cons, if we define things, nomenclature and processes should be approachable to non-furs.

**Raymond/Answer**: It would be funny to see a fur reference in the credits; point noted.

**Rusty/Question**: Data protection such as GDPR / CCPA requirements?

**Raymond/Answer**: Yes, as developers we have a duty to comply with all applicable regulations.

**Rusty**: Data protection requirements vary based on context and circumstances; we should be cognizant of those.

Raymond: Yes. (Personally favors starting at the strict end to be safe.)

Rusty: Data protection requirements will develop as we grow technically and legally. (Raymond +1)

**Khaleta/Comment**: It would be nice to have public commitments to use these standards from various events.**Tea:** Divide our goals into three main questions: What is our vision? What is our strategy? What organization structure do we need? It might not be realistic to come in saying that we're going to fix everything unilaterally. Is frontend part of the vision? Figuring out where we differ or can't reuse solutions is also a key task.

*   Missing Part -
    

**Raymond**: An ideal goal should be for all of us to generate less code \[with duplicate functionality\] over time.

**Jumpy**: Short term visions: collaborate on solution and API designs; Eurofurence has some business solutions; it might also be helpful to publicize components that other events can use for various functions. (ed. note: second page of the spreadsheet should be a good start.)

**smiles/Comment**: It would be nice to start by talking to the participating conventions who we would like to eventually be using our work, to figure out what they need and define the scope of our problem space.

Nican may write up his thoughts afterward; he is still compiling them.

**Raymond**: Yes, we would like to collect "why this is the way it is" (Architecture Decision Record) summaries from people and/or events and review them to understand the problem space.

**Raymond**: Please feel free to use the chat and whiteboard to share ideas and discuss.

**Rakan**: Establishing standards should be a high priority. Deeper collaboration can be up to individual organizations and developers to decide for themselves.

**Raymond**: Again, we cannot "enforce" that people do anything; we can only encourage people to adopt consistent guidelines (hopefully the ones that we are going to develop) for better quality of life.

**Petokikka/Comment**: Examples of how to use our deliverables would be helpful.

Raymond/Answer: \[Good point.\] No standards coming out of this group yet; the hope is that people will want the things this group will make. One benefit is that we can design our "standards" release process to not charge licensing fees.

## Communication and collaboration model

What are people's preferred way to communicate? How do you want to work on this problem space?

Option: Discord

Option: GitHub discussions (to keep things closer to the eventual code). Pro: discussions can be public vs. in discord or Telegram where everything gets lost in private chat history. This provides transparency into why decisions are made.

Do we want to establish teams / channels immediately, or let things organize themselves around what people are using? What should be our focus areas? How about organizing for gathering requirements from stakeholders? How can we ensure the group's alignment and keep momentum?

**Nican/Comment**: Volunteer organizations are hard because there are no commitments to finish things. He's tried all the various things (Slack, Discord, Telegram, etc.) but it's not really a tech problem so much as a social problem. Quality of code, and finding the right times where developers and users can troubleshoot together, are hard.

**Raymond**: (Affirmation) ConCat is a valuable source of experience. Again, there's no way to force anything, all of this has to be on a consent basis.

**Nican**: Test coverage is important. People don't realize the economic reality of wanting an open governance model, but having that come into conflict with how tough it is to work on these projects on the side of day jobs, etc.

**Raymond/Idea**: If a con needs a feature, perhaps bounty it? For example, free reg for people who deliver the feature work? That raises a complication: Suppose one event works on a feature that benefits another event; what consideration attaches to that work? Another model we could consider is the Red Hat structure: the nonprofit owns the IP and development work, and income comes from a sibling organization that provides support?

People seem generally on board with GitHub discussions.

**Khaleta/Comment**: A more asynchronous / less dynamic / easier to filter communication medium would be nice.**Raymond**: Do we know any topics that we can establish immediately, or can we let a starter discussion identify the topics to branch off?

**Rusty**: We need to understand our requirements and the problem space first. (Nican +1)

**Stytch**: What is the relationship between this week's results and next week's meeting?

**Raymond**: The hope is that we won't have too much overlap in who's attending each meeting. We can reuse some discussion points from today, then identify specific actions and processes from there. If we see something that's more or less unanimous today, then we could act on that now. The second meeting is mainly for people to be able to attend whichever one fits their availability better.

## Next steps

It may not be possible to assign anything at this time.

**smiles:** We could start conversations with our respective participating events to find out their requirements.

**Tea:** Consider picking a representative sample of big and small cons to find out where the requirements do and don't overlap, then compile a requirements document and put up a Request For Comments to a larger sample of events.

**Nican:** Perhaps we can have the big preexisting solutions demo to each other to share ideas.

Tea: Would like to get more experience with existing registration solutions; will sync with Nican separately.

## Organization name

*   Open discussion for other suggestions -
    

## Next steps

Raymond will:

\- Set up a poll for voting on the suggested names in the whiteboard.

\- Compile a document with representative sample of events (big, small, invite-only, et al) for discussions

Tea & Nican will:

*   Start conversation with existing solutions for demos or architecture talks
