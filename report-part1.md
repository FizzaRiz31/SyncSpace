# SyncSpace

## Team Summary
|Company Name|Synclabs|
|------------|-------------------|
|Product Name| SyncSpace|
|Member #1| Vincent|
|Member #2| Fizza|
|Member #3| Lasya|
|Member #4|  Mike|
|Member #5|  Alejandro|

## Product Description

> You will invent a product. Your product can be a completely new idea–-entirely of your own invention. Or, your product can be a spin-off of, or competitor to, an existing product. You can leverage the ideas/projects that came from the “Pick a Model” activity. The primary requirement is that your product is complex enough to comprise multiple systems ([Software Subsystems in Modular Design](https://en.wikipedia.org/wiki/Modular_programming)). This means that the product should likely have a client and server architecture ([Client-Server Architecture](https://en.wikipedia.org/wiki/Client%E2%80%93server_model)) and perhaps services provided by third parties (e.g. [Google Authentication](https://en.wikipedia.org/wiki/Google_Authenticator), [Supabase or Firebase](https://supabase.com/alternatives/supabase-vs-firebase), or other [AWS](https://aws.amazon.com/)/[Azure cloud services](https://azure.microsoft.com/en-us/products)). At this time you won’t be detailing the architecture of your product, but it is a good idea to get some level of understanding of all the systems & components at play.

> Note: You are given some creative license in this assignment to make up stuff and _handwave_ when necessary--to overly simplify and make assumptions so that you can be unblocked. However, you should be specific and as realistic as possible.

### Product Overview
Our product is a collaboration platform designed specifically for university students working in groups. Think of it as a “discord for students,” combining all essential tools needed for teamwork all in one organized space. Within the app, students can communicate easily, take shared notes through integrated Notion or Google docs features and to keep track of all group members and resources in one place. To make scheduling simpler, the platform includes a shared calendar that shows when everyone’s schedules and when everyone is available, helping groups find the best times to meet. It also supports accessibility features such as color-blind mode and dark/light themes, ensuring that the app is inclusive and comfortable for all users.

We believe this product fits the assignment perfectly because it shows how a system can integrate multiple technologies and workflows into a cohesive experience. It requires considering both user needs and system-level design; combining communication tools, productivity features, scheduling, and accessibility in a single platform. Adding an AI-powered note-taking assistant and built-in Pomodoro timer demonstrates how software design can enhance both collaboration and focus. This makes the project a good example of a well-rounded, systems-level concept suitable for exploring Scrum-based development and management processes.

### Customer Description
Our main customers are college students who work together on group projects, study sessions, or club activities. They often have to switch between different apps to chat, share notes, and plan meetings, so our platform gives them one organized place to manage everything easily.

We also see professors and teaching assistants as potential users, since they can use the platform to check in on group progress and support collaboration. Over time, universities could adopt it across campus to make teamwork more efficient and accessible for everyone.

### Success Metrics
**Reliability**: The service must have an over 99.5% uptime with little to no interruption in service at almost any point. And messages and other features persist at a satisfactory rate (over 98% success rate within a second). And this would be testable by simply viewing the service log and addressing any issues as well as verifying message latency.

**Availability**: The service must be accessible at any time by all of the intended audience (students) even at times of high load. To test this, performance will be measured by the at least 1000 simultaneous test users within a university to see how the service performs.

**Scalability**: As the user base grows as more universities get added to this service, how does performance get impacted? The codebase should be able to support the rising amount of usage. To test this, increase the amount of test users to 10,000 within different instances for colleges. 

**Useability**: The service must be intuitive and easy to use with minimal tutorials required. It’s easy and simple to understand. Making sure to score higher than an 80% on the student usability scale (SUS). To test this, get feedback from test users. 

**Accessibility**: People of all kinds should be able to use this service. Dark mode, light mode, colorblind mode, are all features that will help with accessibility. As well as keybind mapping to optimize and reduce keyboard and mouse inputs as an advanced feature. We should ideally meet the Web Content Accessibility Guidelines (WCAG). Testable with manual testing and feedback.

**Maintainability**: The codebase should be easy to maintain and do maintenance on as well as be clean enough to add additional features for many years to come. With tests included, good readability and good programming practices. We also must make sure code coverage is >= 80%. Testable by version control history and code reviews. 

**Security**: The ability to properly encrypt and store student information and secure sign ins is imperative. Additionally, proper safety measures should be implemented for the users using the service such as a reporting feature. Testable by thorough testing, ensuring no security breaches and known vulnerabilities, and properly penetration tested and analyzed. 

### Monetization
Our revenue will mostly come from subscription services which allow for additional benefits to our features such as larger file attachments, higher quality streaming and more AI integrated features. Our revenue will also come from cosmetic features such as allowing GIF profile pictures and customizable profiles. As well as seeking sponsorships from universities and other companies.

No advertised features will be taken away from our users ensuring a positive reputation and a freemium model. Any features not specified in the paragraph above will not be paywalled.


### Hardware Needed
The final product will be run on cloud infrastructure. Many servers will be bought/rented for the application and database side of the service. Messages, application data, user data, videos, images, file attachments, and places to store backups will all be accounted for all on the cloud.

Ideally, our service will be accessible to almost all modern systems and will be optimized on even lower end devices including PC and mobile devices without issue.
  

### Team Size
The development lifecycle starts with a team of the five original group members. Additional employees can be hired depending on the workload, or when additional features and services get created to assist the product. An example of such a feature can be the help desk which relates to product support. If work on localization is planned, additional team members familiar with specific languages need to be hired to work on that. It’s a similar case with design and development and when more manpower is needed to keep up with the work in that specific area, the team size can increase to accommodate.

Team size can decrease after the release when the product enters the maintainability state and the workload decreases, and the team can be dissolved when the product stops being maintained. 

### External Resources
Integrating various tools like a calendar, google docs and  work tracking tools like virtual kanban boards would be important for the functionality of the product. The product can also connect with existing tools like google calendar instead of having integration, allowing users to import information to and from those other tools.

Due to the needs for in app subscriptions, some sort of payment processor like paypal or stripe will need to be integrated into the product.

In a similar way, getting access to a video and voice communication service provider to set up online chat rooms for students requires licensing from a third party like zoom.

Additional external resources like a third party security firm to handle security monitoring and analysis and to create a security policy for the team could be possible. A security policy would be necessary due to the product dealing with sensitive user information like emails and phone numbers which would need to be protected.

If necessary, considerations could also be made for renting a physical space to conduct in-person work on the product.


### Product Support

The main product support would be a help desk, a separate website created to handle user questions and bug tickets, which can be sorted and responded to by team members that work on customer support. This allows users to search their questions before creating posts to see if the problem was already answered prior, saving time and resources.

Additionally, on initial startup the product can have a “tutorial” mode that teaches users on how to use the product, guiding them through the UI and various tools.

Patch notes for updates should be made public for users to notify them on various issues and bug fixes and should include guidelines to support and make user interaction with the product more positive.

Describe what product support will look like for your product. How will people get help when they need it? Consider: custom built help file, community supported websites, AI text-based help, call center with human beings.

## Requirements Gathering

At SyncLabs, requirements gathering is a structured, iterative process designed to capture the needs of students, faculty, and university stakeholders while minimizing misalignment risks.
1. Brainstorming and Ideation: The team conducts internal sessions to identify core features, constraints, and integration needs (e.g., Google Docs, Calendar APIs).
2. User Interviews and Surveys: Semi-structured interviews and surveys with students gather insights on collaboration habits, pain points, and desired features.
3. Observation and Focus Groups: We observe real student group workflows and run mock focus groups with wireframes to refine UI/UX, accessibility, and functionality.
4. JAD Workshops: Joint Application Design sessions with developers, designers, and student representatives help define requirements, resolve conflicts, and prioritize features based on impact and feasibility.
5. Documentation and User Stories: Requirements are captured as User Stories in a shared spreadsheet, prioritized by business value, feasibility, and usability. Examples include: 
“As a student, I want a shared calendar showing team availability so scheduling is easier.”
“As a visually impaired student, I want adjustable color schemes so I can navigate comfortably.”
6. Iterative Refinement: Requirements are continuously updated based on prototype testing and early user feedback, ensuring alignment with real user needs.


## Risks

**Risk 1**: Peak Load during Assignment Deadlines

Why: Students have extreme usage patterns of very little activity for weeks, then huge simultaneous use 48-72 hours before major deadlines. Unlike corporate applications, which have relatively consistent traffic, this creates unpredictable 10x+ spikes during midterms and finals in our system. If we crash or slow down during these critical windows, students lose trust permanently and go back to fragmented tools.

Success Metrics:
The platform handles 10x normal load without performance degradation.
Response time does not exceed 2 seconds during peak usage
Zero downtime during identified peak periods
Successfully support 500+ concurrent users per group workspace

Processes:
Design elastic cloud architecture using auto scaling infrastructure that dynamically provisions resources.
Integrate academic calendar data to proactively scale infrastructure a week before known deadline periods
Build Progressive Web App that would allow working offline, without constant connection to a server

**Risk 2**: Real-Time Synchronization Conflicts
Why: When many students edit shared documents or calendars simultaneously, data conflicts and lost work are common. Students work chaotically during deadline crunches, a situation in which conflicts are much more likely than in professional use cases. If we lose someone's work, they will instantly stop using our platform and never come back.

Success Metrics:
No data loss incidents during collaborative editing sessions.
The conflict resolution occurs within 500ms after its detection.
95% of conflicts resolved automatically with no user intervention
4.5/5 user satisfaction score for features related to collaboration

Processes:
Real time collaboration can be implemented using Operational Transformation or CRDT algorithms
Automated nightly tests simulating 50+ concurrent users editing the same document
Clear, non technical user notifications when manual conflict resolution is required
Store 30 day version history of all documents created collaboratively and allow easy rollback

**Risk 3**: Third Party Integration Failures
Why: Third Party services such as notion, Google Docs, and calendar APIs form the backbone of core functionality on the platform. When any of them changes its API or goes down, our app breaks. And students rely on us during critical deadlines. If their integrations fail at 2 am when they're finishing a project, they’ll switch to the familiar separate tools permanently.

Success Metrics:
All integrations maintain 99.5% uptime.
API breaking changes detected and resolved within 48 hours.
Integration failures occur in no more than 2% of active user sessions.

Processes:
Abstraction layers between our code and third party APIs insulate changes.
Automated nightly testing of all third party API endpoints to detect breaking changes as early as possible.
Implement degraded functionality with cached data; allow the application to be accessed when offline.
Subscribe to the newsletters of vendor developers and keep the communication channels open for early warnings.
Quarterly integration reviews to assess health and identify back up providers.

## SDLC

Our company has made the decision to move forward with our project using the Kanban SDLC. We have created an example Kanban board to keep track of our progress and to keep our priorities straight.

![Kanban Board](Kanban%20board.png)

Our board dictates four main steps with the fifth column to dictate what feature has been completed. We will take our user stories and put them into our backlog column as a feature to implement as a task.
  
Any task in the Backlog column represents a feature or user story that has been identified but has not yet been refined or assigned for work. From there, tasks are pulled into the Breakdown column when the team is ready to analyze and decompose them into actionable subtasks. During this stage, each task moves through the TODO, Doing, and Done sub-columns as the decomposition work progresses. Done in this column is defined as a task which has been completely decomposed to solid actionable tasks.

Once fully broken down, tasks enter the Implementation column, where developers actively work on coding or building the feature. Again, the task moves through TODO → Doing → Done, reflecting its progress within this stage. WIP limits in Implementation ensure that each developer focuses on a manageable number of tasks at a time, maintaining efficiency and avoiding bottlenecks. Done in this column is defined as the feature being fully developed, integrated and passes initial developer tests on functionality.

After implementation, tasks advance to the Validation column, which handles testing, quality assurance, and review. The TODO, Doing, Done sub-columns in Validation track which tasks are ready for testing, actively being tested, or have passed QA. Any issues found during Validation may cause tasks to temporarily move back to Implementation to be addressed. Done in this column is defined as a feature that has been rigorously tested and has fully gone through Q/A with all issues found being fixed or addressed.
Finally, once a task has successfully passed validation, it moves into the Done column. This column serves as a record of completed features and gives the team a visual representation of overall project progress.

The gradient on the left represents that the higher a task is on the board, the bigger of a priority it is to get done. Prioritization will happen in daily standup meetings where we gather around our board and check in on progress. The main purpose of this meeting is to get a quick status report on what people have been working on and reprioritization of the board. This meeting is meant to be quick and people will then go their separate ways until the next meeting.

If any issues were to be found, the WIP limits will let us know. Our developers can only have so many tasks being done at the same time before they hit the WIP limit and any bottlenecks will be quickly identified as new tasks will not be coming through. And these issues can be assessed as a group through swarming.

---

> **IMPORTANT**: Don't for get to read about the **Product Backlog** requirement.
>
> You will create a spreadsheet and submit the spreadsheet.
