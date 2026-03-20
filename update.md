You are helping me improve my personal portfolio website built with static HTML/CSS and hosted on GitHub Pages.

Your task is to upgrade the Projects page into a clean, interactive experience where users can select ONE project at a time and view its full case study.

Please make all changes using only HTML, CSS, and lightweight JavaScript. Do NOT introduce frameworks.

The site should feel structured, calm, minimal, and professional.

-----------------------------------
PART 1 - PROJECTS PAGE STRUCTURE
-----------------------------------

Update "/projects.html" with the following structure:

1. Add this intro paragraph at the top of the Projects page:

"The following projects are explorations of how artificial intelligence can reshape the operational backbone of organizations.

My work as a Chief of Staff and operations leader has centered on enabling clarity - translating fragmented information into structured insight, aligning cross-functional teams, and helping leaders move from decision to execution. These projects extend that work into an AI-native context.

Rather than building standalone tools, I am interested in how AI can augment the underlying systems that drive organizations: how information flows, how priorities are negotiated, how decisions are framed, and how execution is coordinated across teams.

Each project is a prototype of a broader question: what does it mean to design organizations where intelligence is embedded into the operating system itself?"

-----------------------------------
PART 2 - INTERACTIVE PROJECT SELECTION
-----------------------------------

Replace the current project list with an interactive project selection layout.

Desktop layout:
- Left side: vertical list of project titles only
- Right side: detail panel showing the selected project's full case study

Mobile layout:
- Project title list at the top
- Detail panel below

Interaction requirements:
- Only ONE project should be visible at a time
- Clicking a project title should replace the content in the detail panel
- Do NOT use an accordion
- Do NOT stack all projects on the page
- Do NOT create a long scrolling wall of text
- Default state: the first project is selected on page load
- Optional but recommended: subtle fade transition between project selections

The experience should let the user quickly scan the list of projects, click the one that interests them, and read only that project's details.

-----------------------------------
PART 3 - DISPLAY ONLY THE FIRST 9 PROJECTS
-----------------------------------

For now, display ONLY these 9 projects on the site:

1. Strategic Priorities Translator and OKR Coherence Analyzer
2. Flash Report and Executive Briefing System
3. Enterprise Portfolio and Program Health Monitor
4. Leadership Alignment Simulator
5. Organizational Cadence Designer and Meeting Audit Tool
6. Cross-Functional Dependency Mapper
7. Stakeholder Communication Planner
8. Strategic Narrative Consistency Checker
9. Initiative Portfolio Rationalization Tool

Do not display projects 10 through 15 yet.

Structure the code so that additional projects can be added later without reworking the page architecture.

-----------------------------------
PART 4 - PROJECT DETAIL PANEL CONTENT
-----------------------------------

Each selected project should render in the detail panel with:

- Title
- Clearly separated section headings:
  - The Problem
  - Why This Matters
  - The Insight
  - What I Am Building
  - Technical Approach
  - Connection to PMBOK
  - What This Demonstrates

Formatting rules:
- Break long text into readable paragraphs
- Use clean spacing between sections
- Section headings should be visually clear and slightly emphasized
- Keep the detail panel document-like and easy to read
- Prioritize readability over visual flourish

-----------------------------------
PART 5 - PROJECT CONTENT TO INSERT
-----------------------------------

Insert the following full content for the first 9 projects.

PROJECT 1
Title: Strategic Priorities Translator and OKR Coherence Analyzer

The Problem:
Every organization has a version of the same recurring failure. Leadership spends days - sometimes weeks - aligning on strategic priorities. Those priorities get announced at an all-hands, written into a planning document, and cascaded to department heads. And then, quietly, each team interprets them differently. By the time the quarter is underway, the organization is executing against five slightly different versions of the same strategy, and nobody has named it yet.

The second layer of the problem is the OKR system meant to prevent this. In most organizations, OKRs have become a compliance exercise. Key results are written to be achievable rather than meaningful. They measure activity - calls made, features shipped, documents produced - rather than outcomes. Team-level objectives have no traceable line back to company strategy. The system exists, but it is not doing the work it was designed to do.

Why This Matters:
In PMBOK terms, this is a failure at the program and portfolio level - specifically in the domains of benefits realization management and stakeholder alignment. When individual project teams are executing competently but toward misaligned objectives, the organization is burning resources on work that does not compound toward its stated goals. The cost is invisible on any individual project plan and only becomes apparent when leadership steps back and asks why the portfolio of work is not adding up to the outcomes they expected.

For a Chief of Staff, Deputy CoS, or senior operations professional, closing this gap is one of the most consequential contributions they can make. It requires the organizational authority to ask uncomfortable questions, the analytical ability to map what is actually happening against what was intended, and the facilitation skill to surface trade-offs without triggering defensiveness. This project demonstrates all three.

The Insight:
The orphaned work report is the most politically significant output this tool produces. In most organizations, a meaningful proportion of active work - projects that teams are genuinely committed to and executing against - has no traceable connection to the stated strategic priorities. Nobody decided this work should not happen. It simply accumulated over time, and nobody has held up the full picture and asked whether it belongs.

Surfacing that clearly, neutrally, and with enough specificity to be actionable is an organizational act as much as an analytical one. It gives the operator the language and evidence needed to initiate a productive leadership conversation without it appearing as a critique of any individual team.

What I Am Building:
A prototype tool that accepts two inputs: the organization's stated strategic priorities or OKRs, and a set of team-level project lists or department OKRs. The system produces a structured alignment analysis including an initiative-to-priority mapping, an orphaned work report, a list of stated priorities with no corresponding work underway, a measurement validity check on each key result assessing whether it actually measures the objective it claims to, and a trade-off summary where priorities appear to be competing for the same resources across functions.

For weak or activity-based key results, the system generates specific, rewritten alternatives as a starting point for the leadership team's review.

Technical Approach:
This prototype is being built using the Claude API to perform semantic alignment analysis across unstructured text inputs. The interface is a two-panel web layout - priorities on the left, team work on the right - with a structured report generated on submission. The tool will be deployed via Vercel with a clean, document-style output designed to be shared directly in a leadership review.

Connection to PMBOK:
This project applies directly to the PMBOK domains of portfolio management, benefits realization, and scope management. The measurement validity check reflects the principle that project success criteria must be defined in terms of outcomes, not outputs - one of the most consistently violated principles in organizational goal-setting. The trade-off analysis reflects portfolio-level resource management: the recognition that a set of individually reasonable commitments can collectively exceed organizational capacity.

What This Demonstrates:
Systems thinking applied to organizational strategy. The ability to move between the executive level - where priorities are set - and the operational level - where work actually happens - and to name the gap between them in a way that creates productive action rather than defensiveness. This is a core capability for a Chief of Staff, a Strategic Operations lead, or a senior program manager operating at the portfolio level.

PROJECT 2
Title: Flash Report and Executive Briefing System

The Problem:
Every week, in organizations of every size, the same scene plays out. Department heads write their updates in isolation. Metrics are pulled from different sources using different methodologies. Narratives are crafted to present each team's work in the most favorable light. The Chief of Staff or operations lead assembles these inputs into a single document and sends it to leadership - and nobody in that process has systematically checked whether the story one team is telling is consistent with the data another team is reporting.

The result is a flash report that looks complete but is not coherent. Leadership reads it, forms impressions, and walks into board meetings or leadership reviews with a picture of the organization that has quiet contradictions built into it. The contradictions surface eventually - usually at the worst possible moment.

Why This Matters:
The flash report is one of the most operationally important artifacts a Chief of Staff manages. It is not simply a reporting document. It is the primary mechanism through which the CEO, leadership team, and board maintain a shared understanding of organizational performance. When it is done well, it creates alignment. When it is done poorly, it creates the illusion of alignment while masking divergence.

Managing this reporting channel - determining which metrics matter, working with the CEO to define what gets reported and at what frequency, consolidating inputs from across the executive team, and preparing leadership for the questions those inputs will generate - is one of the most complex and judgment-intensive responsibilities of the role. It sits at the intersection of information architecture, executive communication, and organizational governance.

The Insight:
The highest-value output of this system is not the summary - it is the preparation it enables. A well-constructed executive briefing arms the CEO and CFO to walk into a board meeting knowing which questions are coming and having already thought through the answers. The divergence detection between team narratives is what makes this possible: when one team's data tells a different story than another team's narrative, that tension needs to be resolved before the board meeting, not during it.

The question generator - surfacing what the CEO or board should be asking based on what is present, missing, or ambiguous in the submitted data - is the feature that most directly reflects the Chief of Staff's function as an executive thought partner.

What I Am Building:
A prototype system that accepts cross-functional inputs from multiple department updates, KPI figures, and written executive narratives. The system will generate a tiered briefing: a concise executive summary, a structured body covering key signals by function, cross-functional implications, and decisions required, a consistency check that flags where metrics and narratives diverge across teams, and a pre-built question set surfacing what the CEO or board should be asking based on gaps or ambiguities in the submitted data.

The output will be formatted in two versions: a detailed operational brief for the Chief of Staff's own preparation, and a cleaner executive version ready for distribution to the leadership team or board.

Technical Approach:
This prototype is being built using the Claude API to perform cross-functional consistency analysis across multiple text and data inputs simultaneously. The interface will allow users to paste inputs from multiple departments in a structured format, with the system detecting divergence across submissions rather than simply summarizing each one in isolation. The tool will be deployed via Vercel with two distinct output formats designed for different distribution contexts.

Connection to PMBOK:
This project reflects the PMBOK knowledge areas of communications management and stakeholder engagement - specifically the principle that different stakeholders require information at different levels of detail, formatted for different decision-making contexts. The consistency check applies the PMBOK concept of integrated change control at the reporting level: ensuring that changes in one functional area are reflected coherently across the broader organizational picture before that picture is presented to governance bodies.

What This Demonstrates:
The ability to design and operate the information architecture that keeps leadership teams informed and aligned. This is a capability that is relevant across Chief of Staff, COO support, Strategic Operations, and senior project management roles - anywhere that a professional is responsible for ensuring the right information reaches the right people in the right format at the right time.

PROJECT 3
Title: Enterprise Portfolio and Program Health Monitor

The Problem:
In a scaling organization, the gap between project management and portfolio management is where strategic commitments quietly go unmet. Individual project managers track their own workstreams with discipline. Department heads have clear visibility into their own teams. But no one holds the consolidated view - which initiatives are on track across the full portfolio, where blockers are concentrating across multiple workstreams simultaneously, and whether the aggregate set of organizational commitments is achievable given current capacity and pace.

The consequence is predictable. Initiatives that appear healthy in isolation are quietly blocked by a shared dependency that nobody has named at the portfolio level. Resource constraints that show up as individual project delays are actually a portfolio-wide capacity problem that requires a different kind of intervention. The organization keeps reporting green on individual projects while the portfolio drifts from its commitments.

Why This Matters:
This is the core problem that formal program and portfolio management disciplines exist to solve - and it is the problem that a PMP-certified professional operating in a Chief of Staff, Strategic Operations, or senior program management role is uniquely positioned to address. The PMBOK framework distinguishes explicitly between managing individual projects and governing a portfolio of interdependent initiatives: the latter requires a different set of skills, a different vantage point, and a different set of tools.

In most scaling companies, this function is not formally staffed. The Chief of Staff or a senior operations professional absorbs it by necessity - often without the infrastructure to do it well. This project is a demonstration of what that infrastructure could look like.

The Insight:
The blocker concentration analysis is the most operationally valuable output this system produces. In most organizations, the same two or three teams, decision-makers, or dependency points are responsible for a disproportionate share of cross-portfolio friction. Individual project managers each see their own blocker in isolation. Nobody is aggregating the pattern. A program-level operator who surfaces that concentration - and brings it to a leadership conversation as a systemic issue rather than a sequence of individual project complaints - changes how the organization actually responds.

The three-audience output structure reflects an equally important insight: the same portfolio data needs to be framed differently depending on who is in the room and what decisions they are being asked to make. A CoS or program manager who handles that translation fluently - operational detail for their own use, synthesized summary for the leadership team, narrative-level overview for the board - is performing a communication architecture function that is as valuable as the analysis itself.

What I Am Building:
A prototype system that accepts a portfolio of active initiatives across the organization - each with a description, owner, current status, key milestones, cross-initiative dependencies, and known blockers. The system will generate a portfolio-wide health assessment: a consolidated progress summary, a blocker concentration analysis identifying which teams or dependencies are creating friction across multiple workstreams, a risk escalation map flagging initiatives at highest risk of missing commitments, and a cross-initiative dependency view showing where one stalled workstream is creating downstream exposure for others.

The system will generate three distinct output formats from the same underlying data: a detailed operational brief for the program manager or CoS, a consolidated summary for the weekly leadership meeting, and a higher-level narrative for board or investor reporting.

Technical Approach:
This prototype is being built using the Claude API to perform cross-initiative dependency and risk analysis across multiple unstructured project inputs. The interface will allow users to input five to fifteen initiative summaries with status and blocker notes, with the system performing portfolio-level pattern recognition rather than simply summarizing each submission. The tool will be deployed via Vercel with three switchable output formats designed for different audience contexts.

Connection to PMBOK:
This project is a direct application of PMBOK's portfolio management domain - specifically the processes of portfolio performance management, risk management at the program level, and benefits realization tracking. The blocker concentration analysis reflects the PMBOK principle of integrated portfolio oversight: the recognition that risks and constraints must be assessed not just at the project level but in terms of their cumulative effect across the portfolio. The three-audience output structure reflects the PMBOK stakeholder communication principle that reporting must be calibrated to the information needs and decision-making authority of each audience.

What This Demonstrates:
Portfolio-level thinking grounded in formal program management methodology. The ability to hold a cross-functional, multi-initiative view of organizational execution and translate that view into actionable insight for different levels of leadership. This is a capability that is directly relevant to Chief of Staff, COO support, Strategic Operations, and senior program management roles - and one that a PMP certification, combined with practical organizational experience, makes uniquely credible to demonstrate.

PROJECT 4
Title: Leadership Alignment Simulator

The Problem:
Leadership misalignment is one of the most damaging and least visible organizational conditions a company can experience. It rarely announces itself directly. Instead, it surfaces as decisions that take longer than they should, initiatives that stall without a clear reason, and a persistent sense that the leadership team is not quite pulling in the same direction - even when everyone appears to agree in the meeting.

The underlying cause is almost never bad intent. It is the reality that functional leaders carry different mental models of what success looks like, operate with different time horizons, and are accountable to different incentive structures. A Chief Revenue Officer and a Chief Product Officer can attend the same strategy meeting, hear the same priorities, and leave with genuinely different understandings of what was decided and what it means for their teams.

Why This Matters:
One of the most delicate and high-value functions of a Chief of Staff is to identify and resolve these misalignments before they reach the broader organization. This work typically happens through careful listening, private conversations, and skilled facilitation across the leadership team. The diagnostic capability, however, is almost never systematic - it lives in the CoS's head, dependent on their relationship access and pattern recognition, and it leaves with them when they do.

For a senior operations professional or Deputy CoS building toward this function, the ability to structure and systematize this diagnostic - to move from sensing tension between two leaders to identifying specifically where their mental models diverge and what a path toward convergence looks like - is a significant step up in operational sophistication.

The Insight:
The most valuable output this system produces is the identification of surface agreement masking real tension. This is the organizational pattern that does the most quiet damage: the leadership meeting where everyone says yes and nothing moves afterward. The yes is genuine in the moment - nobody is being dishonest. But the underlying assumptions about what the yes means, what resources it implies, and whose priorities it advances are different for each person in the room.

A Chief of Staff or operations professional who can surface that pattern - and frame it as a structural issue rather than a personality conflict - is performing one of the most sophisticated acts of organizational stewardship. This tool structures that diagnostic in a way that makes it repeatable and less dependent on any single person's political instincts.

What I Am Building:
A prototype system that accepts structured inputs representing the perspectives of two to four functional leaders on a shared organizational issue - drawn from stated priorities, recent communications, or a plain-text description of their known positions. The system will identify points of genuine alignment, areas where surface agreement conceals divergent assumptions, structural conflicts rooted in differing incentives or time horizons, and suggested paths toward convergence that the CoS or facilitator can bring to a structured leadership conversation.

The output will include a synthesis narrative - a neutral framing of the alignment landscape that could be used to open a facilitated discussion - and a set of specific facilitation moves calibrated to the nature of the tension identified.

Technical Approach:
This prototype is being built using the Claude API to perform comparative perspective analysis across multiple leadership inputs simultaneously. The interface will accept structured text inputs for each leader's position, with the system performing alignment and tension analysis rather than simply summarizing each perspective independently. The tool will be deployed via Vercel with a clean, facilitator-ready output format.

Connection to PMBOK:
This project reflects the PMBOK knowledge areas of stakeholder engagement and communications management - specifically the processes of identifying stakeholder positions, assessing areas of potential conflict, and developing engagement strategies tailored to different stakeholder profiles. The facilitation move recommendations reflect the PMBOK principle that conflict resolution in project and program environments requires matching the intervention to the nature and source of the conflict, not applying a generic approach.

What This Demonstrates:
The ability to hold multiple leadership perspectives simultaneously, identify structural sources of misalignment, and develop a facilitated path toward convergence. This is a core capability for a Chief of Staff, Deputy CoS, or senior operations professional responsible for cross-functional alignment - and one that is genuinely difficult to demonstrate on a resume without a concrete artifact to point to.

PROJECT 5
Title: Organizational Cadence Designer and Meeting Audit Tool

The Problem:
In most organizations, the meeting structure was never designed - it accumulated. A weekly leadership meeting was added when the team reached a certain size. A monthly business review was introduced after a missed quarter. A daily standup appeared during a crisis and never went away. Each addition made sense in the moment. Collectively, they produce a calendar that is dense, redundant, and misaligned with how the organization actually needs to make decisions and share information.

The consequence is twofold. Leadership time - the scarcest resource in any organization - is consumed by meetings that are not calibrated to the decisions those leaders need to make. And the organization loses the sense of rhythm and momentum that a well-designed cadence provides: the steady drumbeat of daily, weekly, monthly, and quarterly forums that creates alignment, surfaces problems early, and keeps strategic priorities visible across the organization.

Why This Matters:
Designing and maintaining the organizational cadence is one of the most operationally consequential responsibilities of a Chief of Staff. This means managing not just the scheduling logistics but the strategic intent behind each meeting type - ensuring that daily check-ins prepare the principal for the week, that weekly leadership meetings are structured around decisions rather than status updates, that monthly business reviews give leadership a genuine pulse on organizational health, and that quarterly all-hands and board meetings receive the preparation they require.

When this cadence drifts - when meetings lose their distinct purpose, when agendas become catch-all, when the ratio of decision-making to status-reporting tips in the wrong direction - the whole operating system of the organization slows with it. Auditing and resetting the cadence is one of the most direct interventions a CoS or senior operations professional can make on organizational effectiveness.

The Insight:
Most efforts to improve meeting culture focus on reducing volume. The more consequential question is composition. A leadership calendar weighted toward status updates reflects a team that has become operational rather than strategic - and that shift rarely announces itself. Leaders do not decide to become operational; they drift there, meeting by meeting, as the calendar fills with forums that report progress rather than drive decisions.

Combining an audit function - diagnosing the current state - with a design function - recommending what the cadence should look like - in a single tool allows an operator to move immediately from diagnosis to prescription, with a concrete recommendation ready to bring to the CEO.

What I Am Building:
A two-mode prototype tool. In audit mode, users will describe their current meeting structure - or paste a representative week's calendar - and the system will categorize each meeting by type: decision-making, status reporting, cross-functional coordination, relationship-building, or ceremonial. It will produce a time portfolio showing the composition of leadership time, a strategic alignment assessment, and specific recommendations for meetings that should be restructured, combined, or retired.

In design mode, users will describe their organization's stage, team structure, coordination challenges, and key decision rhythms. The system will recommend a full cadence covering daily, weekly, monthly, and quarterly forums - with suggested agendas, facilitation notes, participant sets, and a set of common anti-patterns to avoid at each level.

Technical Approach:
This prototype is being built using the Claude API to perform meeting classification and cadence analysis from unstructured text inputs. The two-mode interface will allow users to move between audit and design functions within the same session. The tool will be deployed via Vercel with a clean, shareable report output designed to be presented directly in a CoS-to-CEO conversation.

Connection to PMBOK:
This project reflects the PMBOK knowledge areas of communications management and stakeholder engagement - specifically the processes of planning communications based on stakeholder information needs and designing governance structures that support effective decision-making. The distinction between decision-making meetings and status-reporting meetings maps directly to the PMBOK concept of separating governance forums from operational forums - a principle that is well-established in program management but rarely applied systematically at the organizational level.

What This Demonstrates:
The ability to think about organizational rhythm as a designed system rather than an inherited default. This is a capability that is directly relevant to Chief of Staff, COO support, and senior operations roles - and one that speaks to a level of organizational design thinking that goes beyond scheduling and coordination into the structural conditions that enable good decision-making.

PROJECT 6
Title: Cross-Functional Dependency Mapper

The Problem:
The most consistent failure mode in cross-functional execution is not poor performance within individual teams. It is the dependencies between teams that nobody has explicitly named. Team A is waiting on a decision from Team B that Team B does not know they are responsible for making. Team C's timeline is built on an assumption about Team D's delivery that Team D has never confirmed. These constraints are real, consequential, and largely invisible - until they have already produced a delay, a missed commitment, or a frustrated conversation in a leadership meeting about why a critical initiative has stalled.

The challenge is structural, not motivational. Teams are accountable for their own workstreams. Nobody is formally accountable for the white space between them. That white space is where cross-functional projects break down.

Why This Matters:
Cross-functional orchestration is one of the defining responsibilities of a Chief of Staff, a program manager, or a senior operations professional. The ability to see across team boundaries - to identify the handoffs, the shared assumptions, the unresolved questions that span multiple workstreams - and to surface those dependencies before they become blockers is one of the most valuable contributions an operator at this level can make.

In PMBOK terms, dependency management is a core process within schedule management and integration management. At the program level, it extends beyond individual project timelines into the mapping of inter-project relationships and the active management of shared constraints. This project applies that discipline to the organizational reality of how cross-functional work actually gets coordinated in a scaling company.

The Insight:
The distinction between explicit and implicit dependencies is the analytical core of this tool. Explicit dependencies - named handoffs, stated blockers, formally agreed sequencing - get tracked, because they have been acknowledged by both parties. Implicit dependencies - where one team's work will constrain another's, even though neither team has named that relationship - are where projects actually break down. They are invisible on any individual project plan and only become visible once they have already caused a delay.

A program manager or CoS who can surface implicit dependencies before they become explicit blockers is operating proactively rather than reactively. That shift - from dependency firefighter to dependency architect - is one of the clearest expressions of program management sophistication.

What I Am Building:
A prototype system that accepts project descriptions or status updates from multiple teams - typically three to five - and performs a dependency analysis across all submissions simultaneously. The system will identify explicit dependencies (named handoffs and stated blockers), implicit dependencies (inferred constraints based on the nature and sequencing of the work described), critical path exposure (which teams sit at the intersection of the most dependencies), areas of unclear ownership, and a ranked list of coordination risks with suggested resolution actions and recommended touchpoints.

Technical Approach:
This prototype is being built using the Claude API to perform cross-team dependency inference from unstructured project descriptions. The system will analyze multiple team briefs simultaneously rather than summarizing each in isolation, enabling it to surface relationships that are not visible in any single team's submission. The tool will be deployed via Vercel with a clean dependency matrix output and a prioritized risk register formatted for a program review or leadership discussion.

Connection to PMBOK:
This project is a direct application of PMBOK's schedule management and integration management knowledge areas - specifically the processes of defining activity dependencies, identifying the critical path, and managing inter-project interfaces at the program level. The distinction between explicit and implicit dependencies maps to the PMBOK concepts of mandatory, discretionary, and external dependencies. The risk ranking output reflects the PMBOK risk management process of qualitative risk assessment applied to dependency exposure.

What This Demonstrates:
Program-level thinking applied to cross-functional execution. The ability to see across team boundaries, surface the constraints that no individual team can see from their own vantage point, and structure that analysis in a way that creates productive action. This is a core capability for a Chief of Staff, program manager, or senior operations professional - and one that a PMP certification makes particularly credible to demonstrate.

PROJECT 7
Title: Stakeholder Communication Planner

The Problem:
In change management and project execution, communication is almost always treated as an afterthought. The strategy gets decided, the implementation plan gets built, and then - usually in the final days before launch - someone asks who needs to be told and what they need to hear. The result is messages that go out too late, to the wrong audiences, at the wrong level of detail. Affected stakeholders feel surprised. Teams feel unheard. Resistance builds that structured planning could have prevented.

The deeper problem is that most communication planning stops at the message. It defines what to say but does not prepare communicators for what comes back. The first question from a skeptical stakeholder exposes the plan's fragility - and by then, the communication has already done damage that is difficult to undo.

Why This Matters:
Stakeholder communication is one of the most consistently underdeveloped capabilities in operational leadership. A Chief of Staff, operations lead, or program manager who can design a communication architecture - not just a message, but a full plan covering audience segmentation, channel selection, timing sequencing, and anticipatory response preparation - is adding a layer of organizational sophistication that most execution plans lack.

In change management and program delivery contexts, communication failure is one of the primary causes of initiative failure. Not because the strategy was wrong, but because the people affected by it never received the right information at the right time in the right format from the right person. Structured communication planning is one of the most direct interventions available to prevent that outcome.

The Insight:
The pre-built FAQ is the highest-value output this tool produces. Most communication plans tell communicators what to say. They offer no preparation for the response. A plan that anticipates the likely objections, concerns, and questions from each stakeholder group - and arms the communicator with thoughtful, honest responses before those questions are asked - is addressing the harder, more human dimension of organizational change.

The second insight is sequencing. Who hears about a change first, and in what context, shapes how every subsequent conversation goes. A stakeholder who learns about a significant change from a rumor rather than from their direct leader will process it differently - regardless of what the official communication says. This tool makes sequencing a deliberate, structured decision rather than an afterthought.

What I Am Building:
A prototype system that accepts a structured description of the change being communicated, the stakeholder groups affected with their likely concerns and relationship to the change, the timeline and key milestones, and any known sensitivities. The system will generate a full communication plan: a stakeholder matrix with influence and impact assessments, audience-specific messages calibrated by level of detail and tone, channel and timing recommendations aligned to the organizational cadence, a sequencing plan for who hears what and in what order, and a pre-built FAQ that addresses the anticipated concerns of each stakeholder group before they become active objections.

Technical Approach:
This prototype is being built using the Claude API to perform stakeholder analysis and communication architecture generation from structured text inputs. The interface will guide users through a structured intake process designed to surface the information needed for a complete communication plan. The tool will be deployed via Vercel with a clean, exportable output formatted for immediate use in a project or change management context.

Connection to PMBOK:
This project is a direct application of the PMBOK communications management knowledge area - specifically the processes of planning communications management, managing communications, and monitoring communications effectiveness. The stakeholder matrix reflects the PMBOK stakeholder engagement assessment matrix. The sequencing plan reflects the PMBOK principle that communication timing and channel selection are as strategically significant as message content. The pre-built FAQ reflects the PMBOK risk response planning process applied to stakeholder resistance.

What This Demonstrates:
The ability to design a communication architecture that is calibrated to the organizational context, the stakeholder landscape, and the human dynamics of change. This is a capability that is directly relevant to Chief of Staff, program management, change management, and senior operations roles - and one that speaks to a practitioner who understands that execution success depends as much on how a change is communicated as on how it is designed.

PROJECT 8
Title: Strategic Narrative Consistency Checker

The Problem:
As organizations evolve, their narratives drift. The investor deck was written eighteen months ago and reflects a strategic position the company has since moved on from. The website was updated by the marketing team in response to a product launch. The all-hands talking points were revised after a difficult quarter. The job descriptions were written by individual hiring managers with their own framing of what the company does and where it is going.

No single person is being dishonest. The narratives have simply evolved at different speeds across different surfaces, shaped by different authors, different audiences, and different moments in the company's history. The result is an organization whose external and internal communications tell subtly different stories - and nobody is holding the center.

Why This Matters:
Narrative consistency is a governance function as much as a communications function. When the story a company tells about itself is coherent across all surfaces - from board materials to product positioning to the language used in hiring - it creates trust with investors, customers, prospective employees, and the existing team. When it is fragmented, that fragmentation creates a quiet but persistent erosion of confidence in leadership clarity.

For a Chief of Staff or senior operations professional, maintaining narrative coherence across surfaces is one of the less visible but more consequential aspects of the role. It requires organizational access to review materials across functions, editorial judgment to identify meaningful inconsistencies, and the relational credibility to facilitate a reconciliation process without appearing to impose a top-down message.

The Insight:
Job descriptions are the most revealing artifact in a narrative consistency audit. They reflect what the organization actually believes it needs at a given moment - the skills it is prioritizing, the problems it is trying to solve, the culture it is trying to build. And they almost always tell a different story than the official strategic narrative. A company whose investor materials describe a product-led growth strategy but whose engineering job descriptions are all for enterprise integration work is showing its real priorities more clearly in its hiring than in its pitch.

Including job descriptions in a narrative audit - alongside investor materials, website copy, and all-hands communications - is a diagnostic move that only someone who has done this work at close range would think to make.

What I Am Building:
A prototype system that accepts multiple narrative artifacts from across an organization - investor memos, product overviews, all-hands talking points, website copy, executive communications, and job descriptions. The system will perform a cross-document consistency analysis, identifying divergences in positioning, terminology, stated priorities, and implied audience across all submitted materials. It will produce a side-by-side inconsistency report and a synthesized narrative framework - a source-of-truth document that reconciles the divergent threads and could serve as a master reference for the organization's communications going forward.

Technical Approach:
This prototype is being built using the Claude API to perform cross-document semantic consistency analysis across multiple unstructured text inputs. The system will analyze all submitted materials simultaneously rather than summarizing each in isolation, enabling it to surface inconsistencies that are only visible in comparison. The tool will be deployed via Vercel with a clean inconsistency report output and a synthesized narrative framework formatted for review by a CoS or communications lead.

Connection to PMBOK:
This project reflects the PMBOK knowledge areas of communications management and stakeholder engagement - specifically the principle that organizational communications must be consistent across stakeholder groups and aligned with the project or program's stated objectives and scope. Applied at the organizational level, this maps to the governance function of ensuring that the narrative presented to different stakeholder groups - investors, employees, customers, and prospective hires - is coherent, current, and aligned with the organization's actual strategic direction.

What This Demonstrates:
The ability to hold the full organizational narrative in view across multiple surfaces simultaneously - and to identify the divergences that create strategic ambiguity. This is a capability that is directly relevant to Chief of Staff, strategic communications, and senior operations roles. Combined with the analytical rigor of building a working tool to perform this analysis, it signals the kind of organizational awareness that is difficult to demonstrate through a resume alone.

PROJECT 9
Title: Initiative Portfolio Rationalization Tool

The Problem:
Organizational ambition compounds faster than organizational capacity. A new initiative gets added in response to a market opportunity. Another follows a leadership priority. A third emerges from a board suggestion. Each addition is defensible in isolation. Collectively, they produce a portfolio of active initiatives that exceeds what the organization can execute well - without anyone having made that trade-off explicitly.

The problem is not the presence of ambitious ideas. It is the absence of a structured mechanism to make the cumulative cost of those ideas visible. Without that visibility, every initiative appears equally funded, equally resourced, and equally likely to succeed - because nobody has put them all on the same page and asked what it would actually take to deliver them all.

Why This Matters:
One of the most important and politically sensitive functions of a Chief of Staff or senior operations professional is to create honest visibility into the full portfolio of active work and facilitate a genuine conversation about what the organization can realistically sustain. This is not a popular function. Every initiative has a sponsor. Every sponsor believes their initiative is the priority. The operator who surfaces the aggregate picture - clearly, neutrally, and with enough specificity to make the trade-offs undeniable - is doing something that changes how the organization allocates its most limited resource: focused execution capacity.

The Insight:
The most politically useful output is a clear picture of what saying yes to everything actually costs. Organizations rarely make explicit trade-offs because no one has assembled the full picture in one place. A Chief of Staff who can do that - neutrally, without appearing to advocate for any particular outcome - is performing one of the most valuable acts of organizational leadership. The tool's value is not in making the decision. It is in making the decision unavoidable.

What I Am Building:
A prototype system that accepts all active initiatives across the organization - each with a description, owner, resource requirements, and stated strategic rationale. The system will assess each initiative against the organization's stated strategic priorities, estimate cumulative resource demand relative to organizational capacity, identify redundant or overlapping efforts across teams, and produce a rationalization framework the CoS can use to facilitate a leadership conversation about focus and sequencing.

The output will include initiatives assessed by strategic fit and resource efficiency, overlap and redundancy flags, and a prioritized set of recommendations formatted for a leadership discussion or planning offsite.

Technical Approach:
This prototype is being built using the Claude API to perform strategic fit assessment and portfolio-level resource analysis from unstructured initiative descriptions. The interface will allow users to upload or paste an initiative inventory, with the system performing cross-initiative analysis rather than evaluating each submission independently. The tool will be deployed via Vercel with a clean portfolio analysis output formatted for a leadership review.

Connection to PMBOK:
This project applies directly to the PMBOK portfolio management domain - specifically the processes of portfolio component selection, prioritization, and balancing. The resource demand estimation reflects the PMBOK principle of portfolio capacity management: the recognition that a portfolio must be balanced not just against strategic fit but against the organization's realistic capacity to execute. The overlap and redundancy analysis reflects the PMBOK integration management principle of identifying and resolving conflicts across portfolio components before they consume resources in parallel.

What This Demonstrates:
The ability to hold a portfolio-level view of organizational work and facilitate the difficult conversations that honest prioritization requires. This is a capability that is directly relevant to Chief of Staff, COO support, Strategic Operations, and senior program management roles - and one that requires both analytical rigor and the organizational judgment to know when and how to surface what the analysis reveals.

-----------------------------------
PART 6 - IMPLEMENTATION PREFERENCES
-----------------------------------

Preferred implementation:
- Store project data in a JavaScript object or array
- Dynamically render selected project content into the detail panel
- Keep the code readable and easy to extend later

Alternative acceptable approach:
- Hidden HTML sections toggled by JavaScript

Keep it simple and maintainable.

-----------------------------------
PART 7 - HOMEPAGE BUTTON CONSISTENCY
-----------------------------------

On the homepage, update these buttons:
- View Projects
- Read Writing
- Connect

Make all three identical in style.

Use the current "Read Writing" button as the visual reference:
- Pink text
- Transparent background
- Pink border outline

Ensure:
- Same width
- Same height
- Same padding
- Same border radius

-----------------------------------
PART 8 - RENAME "READ WRITING"
-----------------------------------

Replace "Read Writing" with:

"Notes"

Update:
- Button text
- Navigation text
- Section labels if applicable

-----------------------------------
PART 9 - MOBILE RESPONSIVENESS
-----------------------------------

Make the site mobile-friendly.

Requirements:
- Under 768px, stack the project list above the detail panel
- No text overflow
- Comfortable reading width
- Buttons are easy to tap
- Maintain spacing and readability

-----------------------------------
PART 10 - BIO TEXT FIX
-----------------------------------

Replace the current bio paragraph with:

"More recently, I have become deeply interested in how artificial intelligence will reshape knowledge work and organizational structure. Rather than approaching AI purely from a technical perspective, I focus on its implications for operators and leaders - particularly how it may transform coordination, decision-making, and execution inside companies."

-----------------------------------
PART 11 - GLOBAL STYLE CLEANUP
-----------------------------------

Across the entire site:
- Replace all long dashes with standard hyphens
- Ensure consistent spacing and typography
- Maintain a clean, elegant, professional aesthetic

-----------------------------------
PART 12 - OUTPUT REQUIREMENTS
-----------------------------------

- Keep the site fully static and GitHub Pages compatible
- Use only HTML, CSS, and minimal JavaScript
- Do not add frameworks
- Do not over-engineer

The result should feel:
- thoughtful
- polished
- structured
- credible for employers reviewing a professional portfolio

Please make the edits directly to the existing site files.