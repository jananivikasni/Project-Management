Campus Beauty Booking Platform
Christy Kwentua, Spring 2026

Introduction
As a college student at the University of Illinois Urbana-Champaign, I have experienced firsthand how difficult it is to find reliable, affordable beauty services near campus. Whether it is getting your hair done before a big event, finding someone for a fresh set of nails, or booking a makeup artist for a special occasion, the process is always the same,  scrolling through Instagram, asking around in group chats, hoping someone can recommend someone trustworthy. There is no centralized place for students to discover, book, and review beauty service providers in their campus community. That is the problem I want to solve.
The Campus Beauty Booking Platform is my proposed solution. The idea is simple: build a platform specifically for UIUC students that makes it easy to find and book beauty services, manage provider availability, and leave feedback that helps the community make better decisions over time. I was drawn to this project because it addresses a real gap I see in my everyday life, and because it gives me the opportunity to apply the project management principles I have been learning throughout this course to something that actually matters to the people around me.
Throughout this paper, I will walk through the vision of the platform, the three project management principles that shape how I plan to build and manage it, the workflow and milestone roadmap I developed during the semester, the technical and community-building details of implementation, and how I plan to sustain the project over time.
Vision Statement
The Campus Beauty Booking Platform is a student-centered digital service that connects UIUC students with local beauty service providers for hair, nails, and makeup appointments. The platform gives students a single, trustworthy place to discover providers, check availability, book appointments, and leave ratings , and gives providers a simple tool to manage their schedules and grow their client base on campus.
The long-term vision is for this platform to become the go-to resource for beauty services at UIUC and eventually scale to other university campuses. But the short-term goal is simpler: build a minimum viable product that solves the core booking problem and get it into the hands of real students as quickly as possible so that real feedback can shape what it becomes.

Project Management Principles
Agile Methodology and Feedback Loops
The most important principle guiding the development of the Campus Beauty Booking Platform is Agile methodology. Agile is an approach that divides work into phases, emphasizing collaboration, continuous delivery, and adaptability (Atlassian, 2026). I chose Agile because the needs of my target users , UIUC students and local beauty providers ,  are not fully knowable in advance. The only way to truly understand what the platform needs to do is to build something, put it in front of real users, and listen to what they say.
Rather than spending months designing a perfect system before writing a single line of code, the Agile approach allows me to release a working MVP at the end of the nine-week development timeline and then iterate based on what I learn. Every sprint produces a testable increment of the product, and every round of user feedback informs the next sprint's priorities. This creates a continuous loop: design, build, test, collect feedback, and improve. For example, the provider matching system will launch as a simple manual selection tool. If user behavior data shows that students want more automated recommendations, that becomes a priority for a future sprint. If it turns out manual selection works just fine, I have saved significant development time by not over-engineering a solution to a problem that did not actually exist.
Agile also helps me practice triaging  doing the most critical work first and deferring lower-priority enhancements to later sprints. For a small team with limited resources, this discipline is essential. Without it, it is very easy to spend time building features that look exciting but do not actually serve the core user need (Alicea, 2026).
Technical Debt Management
Technical debt is the implied cost of additional rework caused by choosing an easier or more limited solution now instead of a better, more time-consuming approach (Watt, 2014). Every project incurs some initial technical debt , it is unavoidable, especially when working under time and resource constraints. The key is not to pretend it does not exist but to manage it deliberately and keep it visible throughout the project lifecycle.
For the Campus Beauty Booking Platform, I am making several intentional technical debt decisions in order to ship the MVP on time. The provider availability system will launch as a manually updated static schedule rather than a real-time automated calendar. The matching logic will begin as a simple dropdown selection rather than an algorithm-driven recommendation engine. These are easy solutions that will require rework later, but they allow the team to deliver a functional product within the nine-week timeline without getting blocked by technical complexity. As the course material describes, this is the classic tradeoff between speedy delivery and long-term maintainability (Alicea, 2026).
Over a five-year window, additional sources of technical debt are likely to emerge. Version migration costs will require periodic rework as core dependencies are updated. Scaling limitations may appear as the user base grows beyond a single campus, requiring migration from a lightweight SQLite database to a more robust infrastructure. Documentation decay is another long-term risk ,  if the team does not consistently update technical documentation alongside code changes, new contributors will struggle to onboard effectively. Code smells such as unclear naming conventions or redundant logic will also accumulate over time if regular code review sessions are not built into the workflow (Alicea, 2026).
To manage these risks, I plan to use an architecture dashboard to keep technical debt visible rather than letting it build up silently. I will also establish clear contribution guidelines in the GitHub repository from day one, ensuring that every contributor understands the standards for code quality and documentation. By treating technical debt as a first-class concern rather than an afterthought, the platform is positioned to remain maintainable and scalable as it grows.
Automation in Project Management
Automation plays a dual role in the Campus Beauty Booking Platform,  it is both a feature of the product itself and a tool for managing the development process. Understanding where automation helps and where it creates new problems is one of the more nuanced challenges in building a project like this (Alicea, 2026).
At the product level, automation is what makes the platform efficient. Automated booking confirmations, provider notifications, and post-appointment feedback request emails reduce the administrative burden on both users and providers. The ratings system is designed to automatically aggregate user reviews and surface high-performing providers, creating a self-improving quality signal without requiring manual curation. These are the kinds of automation that genuinely add value because they handle repetitive, standardized tasks that do not require human judgment.
At the project management level, automation tools like GitHub Actions can run automated tests whenever new code is submitted via a pull request, catching errors before they are merged into the main codebase. Automated issue tracking through the GitHub Kanban board keeps the team aligned on priorities without requiring constant synchronous check-ins, which is especially important for a small, distributed team.
However, automation also carries real risks. Over-automating the development process for a team of three to five contributors can create what the course describes as technological sprawl — a proliferation of tools that becomes harder to manage than the project itself (Alicea, 2026). There is also the paradox of automation: as systems become more automated, team members may lose the manual awareness needed to intervene when something breaks. For this reason, I am taking a golden mean approach , automating repetitive and standardized tasks while preserving human judgment for decisions that require context, such as resolving booking disputes or evaluating new contributor pull requests.
Roadmap and Workflows
TCAT Workflow Model
The platform's core booking process is mapped using the Trigger-Condition-Action-Terminator (TCAT) model, which I developed in Reflection 3. The TCAT model gives a clear picture of how a booking moves through the system from the moment a student submits a request to the moment it is stored and used to inform future recommendations.
Figure 1: Campus Beauty Booking Platform Workflow (TCAT Model)


The two decision points in this workflow are the most critical control mechanisms in the system. Provider availability ensures that the platform handles scheduling conflicts gracefully rather than double-booking providers. The service completion check creates a structured resolution path for unsatisfactory services, which protects both students and the platform's reputation. The feedback loop at the end of every booking is what allows the platform to improve over time , every completed appointment generates data that makes the next booking better.

Project Milestone Timeline
Table 1: Development Timeline and Milestones
Timeframe
Milestone
Deliverable
Week 1–2
Project Planning
Define services, target users, and tech stack
Week 3–4
Design Phase
Booking flow wireframes and UI mockups
Week 5–7
Development
Build booking system and provider matching
Week 8
Testing
Identify bugs and improve user experience
Week 9
MVP Launch
Platform released to UIUC students
Ongoing
Iteration
Add features based on user feedback
Year 1
Full Release
Automated matching and ratings system live
Year 5
Scale
Platform adapted for additional campuses

The nine-week timeline is intentionally aggressive. By forcing the team to hit a hard launch deadline at Week 9, the MVP-first approach prevents scope creep and keeps development focused on the features that matter most. The ongoing iteration phase after launch is where the real work begins , every round of user feedback informs the next round of improvements, creating the continuous improvement loop that Agile methodology is designed to support (Atlassian, 2026).
Implementation Details
Technical Stack
The Campus Beauty Booking Platform will be built using a lightweight, open-source-friendly technology stack designed to minimize initial technical debt while remaining scalable as the project grows.
Version Control: GitHub — all code, documentation, and project management is centralized here
Backend Logic: Python — used for provider matching logic and booking management
Frontend: HTML, CSS, and JavaScript — a simple, mobile-friendly interface designed for students booking on their phones
Database: SQLite for the MVP, with a clear migration path to PostgreSQL as the user base grows
Documentation: Markdown — all project documentation written in GitHub-flavored Markdown
I chose this stack because it prioritizes accessibility over sophistication. Every tool is free, widely documented, and well supported by open-source communities. This means that new contributors can get up and running quickly without needing expensive software or specialized hardware. It also means that if a tool becomes outdated or unsupported, there are well-established migration paths rather than dead ends.
Community Building
The platform's community strategy focuses on two distinct groups: students as users and beauty service providers as contributors. For students, the primary onboarding channel is campus social media and word-of-mouth, targeting early adopters who are already active in UIUC student communities. For providers, onboarding is facilitated through a clear Start Here guide in the GitHub repository, a contribution guide outlining how providers can register their services, and a simple intake form for availability and pricing information.
Building a healthy contributor community requires more than just good documentation. It requires creating a culture where contributors feel valued and where the project's goals are clearly communicated. As Dr. Alicea emphasized in lecture, being a trustworthy project manager who genuinely cares for the needs of both end users and team members is what makes a community sustainable over time (Alicea, 2026). For this project, that means being transparent about decisions, responding to feedback quickly, and recognizing contributions publicly.
The GitHub Kanban board established during Quiz 2 serves as the central tool for community coordination. Issues are triaged with clear labels distinguishing between bugs, feature requests, documentation needs, and urgent items. New contributors ,  both technical and non-technical, are directed to good first issues that provide a low-barrier entry point into the project. This mirrors the open-source community building principles discussed throughout the course, where the goal is to lower the barrier to contribution as much as possible while maintaining quality standards (Cotton, 2023).
Rescoping Strategy
Based on MoSCoW prioritization, the platform's features are categorized as follows for the MVP launch:
Must Have: Basic booking form, provider availability display, booking confirmation, payment processing
Should Have: Ratings and feedback system, provider profile pages, booking history
Could Have: Automated provider matching algorithm, push notifications, loyalty rewards
Won't Have (for MVP): AI-powered recommendations, multi-campus support, in-app messaging
The features in the Could Have and Won't Have categories represent deliberate descoping decisions. They are not abandoned , they are documented in the GitHub repository as future issues with clear descriptions of what they would require to implement. This way, the team always has a visible roadmap of where the project is going, and contributors who join later can immediately see where they can add value.
Sustainability and Lifecycle
The long-term sustainability of the Campus Beauty Booking Platform depends on three things working together: technical maintainability, community health, and a realistic plan for keeping the platform financially viable.
From a technical standpoint, sustainability means staying ahead of the technical debt that will inevitably accumulate. The architecture dashboard approach keeps debt visible. Regular code review sessions prevent code smells from embedding themselves in the codebase. Clear documentation standards ensure that every major decision is recorded and accessible to future contributors. Without this discipline, even a well-built MVP can become unmaintainable within a year or two as dependencies update and team members change.
From a community standpoint, sustainability means maintaining an active, engaged contributor base even as the initial excitement of the launch fades. The community commitment curve — starting with a small group of highly motivated early contributors and gradually expanding through structured onboarding ,  provides a framework for this. Public documentation, contributor recognition, and clear communication channels all help keep contributors engaged over the long term (Cotton, 2023). From a financial standpoint, the MVP phase will operate at minimal cost, leveraging free-tier tools and volunteer contributor time. As the platform scales, a small transaction fee model provides a sustainable revenue mechanism that aligns the platform's financial health with its user activity. This revenue can be reinvested into infrastructure, contributor recognition, and feature development, creating a cycle of growth that supports itself over time.
Challenges and Risks
No project is without its risks, and being honest about them from the beginning is part of what makes a project plan credible. For the Campus Beauty Booking Platform, the most significant risks fall into three categories.
The first is adoption. A booking platform is only useful if both students and providers use it. Convincing providers ,  many of whom are informal, solo operators ,  to adopt a new platform requires building trust and demonstrating clear value. If the initial provider pool is too small, students will not find the platform useful, and the network effect that makes it valuable will never materialize. The mitigation strategy here is to focus heavily on provider onboarding in the first two weeks of the timeline, securing at least a small cohort of committed providers before the platform launches to students.
The second risk is scope creep. Beauty services encompass a wide range of specialties, price points, and service models. It would be very easy to try to serve every possible use case from the beginning and end up building a bloated, unfocused product. The MoSCoW prioritization framework and the MVP-first approach are the primary defenses against this, but they only work if the team has the discipline to say no to feature requests that fall outside the MVP scope.
The third risk is technical debt accumulation. As discussed earlier, the platform intentionally incurs some technical debt in order to launch on schedule. The risk is that this debt accumulates faster than the team can pay it back, eventually making the codebase too difficult to maintain or extend. Regular triage of the GitHub issue board, consistent code review, and a clear policy of addressing debt in every sprint rather than deferring it indefinitely are the strategies I plan to use to keep this risk manageable.
Conclusion
Building the Campus Beauty Booking Platform has been a process of translating a real problem I see in my everyday life into a structured, manageable project plan. The three principles that have shaped this project is Agile methodology, technical debt management, and balanced automation which are not abstract concepts. They are practical tools that I have applied directly to the decisions I have made about how to build this platform, what to build first, and how to build it in a way that can last.
The TCAT workflow and milestone timeline give the project a clear organizational structure. The MVP-first approach and MoSCoW prioritization keep the team focused on delivering real value to real users. The community building strategy ensures that the platform grows through genuine relationships and contributions rather than just code. And the sustainability plan ensures that the work done in the first nine weeks is not the end of the story but the beginning of it.
I am genuinely excited about this project because it solves a problem I care about, and because this course has given me the tools to approach it with both rigor and intention. The Campus Beauty Booking Platform is not just a class assignment ,  it is a real idea that I plan to continue developing.
References
Alicea, B. (2026). Integrative Project Management [Course Lecture Notes]. University of Illinois Urbana-Champaign.
Atlassian. (2026). What is Agile? https://www.atlassian.com/agile
Cotton, B. (2023). Program Management for Open Source Projects. The Pragmatic Bookshelf.
Project Management Institute. (2021). A Guide to the Project Management Body of Knowledge (PMBOK Guide) (7th ed.). Project Management Institute.
Watt, A. (2014). Project Management. BCcampus Open Education. https://opentextbc.ca/projectmanagement/
