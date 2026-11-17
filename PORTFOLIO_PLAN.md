# Review 2 — Plan — Portfolio
**Student:** Tasnim Fariha  
**Course:** IS117, Fall 2026  
**Plan date:** November 17, 2026  
**Status:** Planning complete; implementation and peer review pending

## Research carried forward
Career Exploration compared Citi's Technology, Application Development Summer Analyst 2027 role and JPMorgan Chase's Audit Summer Analyst program (both pages checked November 12, 2026). Citi emphasized translating requirements into technology work and writing/testing code. JPMorgan's audit program emphasized business risks, internal controls, analysis and communication. These are observations from the earlier research submission, not new interviews or evidence of current openings.

Sources:
- [Citi role page](https://jobs.citi.com/job/jersey-city/technology-application-development-summer-analyst-new-york-or-new-jersey-usa-2027/287/102340905456) — checked November 12, 2026 in prior research
- [JPMorgan Chase Audit Summer Analyst overview](https://careers.jpmorgan.com/us/en/students/programs/audit-summer-analyst) — checked November 12, 2026 in prior research

**Goal:** A portfolio for business analyst and business/technology internship opportunities. **Primary persona hypothesis:** A busy recruiter wants to see relevant education, evidence of work, and a résumé quickly. **Secondary persona hypothesis:** A hiring manager wants to inspect project decisions and source code. These are assumptions, not observed interviews.

## Compare two approaches
| Approach | Benefits | Tradeoffs |
|---|---|---|
| Static HTML/CSS with minimal JavaScript | Fits IS117 skills, quick to maintain, simple to audit, can be mobile-friendly | Less built-in support for complex interactions |
| React single-page app | Reusable components and richer interactions | More setup, complexity and testing for a simple portfolio |

**Decision:** Start with HTML/CSS and minimal JavaScript. Clear evidence and working links matter more to this audience than animations. Revisit only if later requirements justify React.

## Five user stories and observable acceptance checks
1. **Introduction:** As a recruiter, I want to identify the student's major and career direction quickly. **Feature:** Home introduction. **Check:** Home page clearly says NJIT, Business and Information Systems, and business analyst interests without extra navigation.
2. **Projects:** As a hiring manager, I want to inspect actual work. **Feature:** Project cards describing the problem, student's role, skills, and repository links. **Check:** Three project entries have accurate descriptions and links; incomplete work is clearly marked.
3. **Professional profiles:** As a recruiter, I want to open GitHub and LinkedIn. **Feature:** Labeled profile links. **Check:** Both open the intended public profiles on desktop and phone.
4. **Résumé:** As a recruiter, I want a readable résumé. **Feature:** Résumé link. **Check:** It opens a current résumé readable on a phone.
5. **Mobile use:** As a visitor on a phone, I want simple navigation. **Feature:** Responsive menu and layout. **Check:** No horizontal scrolling at common mobile widths; text, links and focus states are usable.

**Important:** These are planned checks, not completed tests.

## Planned page options and destinations
- **Home:** Brief introduction and clear links to projects and résumé.
- **About:** NJIT education, work experience, analytical and communication skills; distinguish current skills from learning goals.
- **Projects:** Three entries, with source links and honest status labels:
  - [VOID Brand Studio](https://github.com/itssfariha-lab/is117-brand-studio)
  - [IS117 Web Server](https://github.com/itssfariha-lab/is117-web-server)
  - [Portfolio repository](https://github.com/itssfariha-lab/is117-portfolio) — planning stage
- **Résumé:** Readable résumé link — **not yet supplied**.
- **Contact:** [GitHub profile](https://github.com/itssfariha-lab) and LinkedIn — **exact LinkedIn URL not yet supplied**.

## Visual identity and honest persuasion
Carry forward the strong typographic hierarchy and intentional contrast practiced in VOID Brand Studio, but use a restrained professional style: dark navy, white and blue accents, readable text, consistent spacing, visible focus styles, and mobile-first layout. Describe classroom projects accurately rather than claiming professional production experience. Do not invent testimonials, interviews, metrics, or expertise.

## Evidence → decision → proposed verification
| Earlier finding | Portfolio decision | Future check |
|---|---|---|
| Citi role included technology work based on business requirements | Explain each project's problem, approach, and individual contribution | Inspect project cards for concrete, accurate descriptions |
| JPMorgan program emphasized process analysis, risk and communication | Highlight analytical research and professional writing alongside code | Verify About/Projects include truthful examples |
| Reader may have limited time (**hypothesis**) | Put résumé, projects, GitHub and LinkedIn in easy-to-find navigation | Ask reviewer to locate each destination without guidance |

## Small-step build and review plan
1. Save plan in this repository.
2. Build semantic HTML navigation and homepage.
3. Add About, Projects, Résumé and Contact sections.
4. Add missing real destinations; never substitute fabricated links.
5. Test links, keyboard navigation and mobile layout; record actual outcomes.
6. Request a peer review in GitHub issues; record issue → decision → commit → verification → reviewer retry before closing accepted fixes.

## Review and change record
- **Planning documentation:** This file is the initial plan.
- **Peer feedback received:** None documented yet.
- **Decision/implementation in response to feedback:** Pending.
- **Reviewer retry:** Pending.
- **Open items:** LinkedIn URL, résumé link, deployed documentation/site URLs, actual mobile/link checks, reviewer issue and response.

## AI assistance
ChatGPT assisted with structuring the plan, comparing approaches, drafting stories and translating the student's prior Career Exploration into proposed features. The career-role observations were supplied from the student's prior submission; this document does not claim fresh source verification or completed user testing. The student should review and approve the plan and verify links before submission.
