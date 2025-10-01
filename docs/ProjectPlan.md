---
title: "Project Management Plan — Project 03: This Is Your Song"
author: "Unofficial Project Manager: John Barkle IV"
course: "CMPA 3301 — Fundamentals of Computing Applications"
date: "Sep 21, 2025"
---

# Project Management Plan — This Is Your Song

## 1. Introduction
This Project Management Plan governs the execution of the *This Is Your Song — Proof of Concept Website*. 
It is based on the **Project 3 Proposal Guidance** and has been tailored to meet the CMPA 3301 requirements.

The plan ensures strict adherence to the **Scope Statement** to remain compliant with project management 
principles and course expectations.

## 2. Scope Statement (Condensed)
See approved **Final Project Scope Statement** (docs/final-project-scope.md).

**Key Note:** The project team will strictly adhere to this scope. Any proposed change will be logged, 
reviewed against acceptance criteria, and either rejected as scope creep or justified as scope discovery 
with sponsor approval.

## 3. Work Breakdown Structure (WBS)
**Level 1 — Project Deliverables**
1. **Initiation**
   - Customer Intake Interview
   - Project Charter
   - Scope Statement submission for review
   - Incorporation of review feedback

2. **Planning**
   - Project Management Plan (this document)
   - Web design planning session
     - Decide design concept and palette
     - Choose HTML/CSS features/functions
   - Identify demo songs and create jingle

3. **Execution**
   - GitHub setup
     - Initialize repo
     - Clone repo to local environment
     - Publish to GitHub Pages
   - Development
     - Home page: banner, text, jingle player
     - Catalog page: four demo audio thumbnails, embedded intake prompt, mailto CTA
   - Configure audio players
   - Draft documentation (`scope`, `plan`, `retrospective`, `README`)

4. **Monitoring & Control**
   - QA review against acceptance criteria
   - Rewrite session to refine content/design as needed

5. **Closure**
   - Project retrospective
   - Final submission

## 4. Workflow (Step Sequence)
1. Intake + Charter approved
2. Scope drafted, submitted for review, feedback incorporated
3. Planning session: finalize design, palette, features
4. Repo setup (initialize, clone, publish with GitHub Desktop)
5. Development of Home + Catalog pages with LiveServer/FiveServer preview
6. Asset integration (jingle + demo songs + thumbnails)
7. QA: test against acceptance criteria (navigation, audio, email CTA, embedded prompt)
8. Rewrite/refinement session
9. Final retrospective and submission

## 5. Stakeholder Registry
| Stakeholder        | Role/Interest                  | Influence | Engagement Strategy           |
|--------------------|--------------------------------|-----------|-------------------------------|
| Greg Gamel         | Instructor / Sponsor           | High      | Provide rubric, review, and approval |
| John Barkle IV     | Student / Project Manager      | High      | Executes, documents, delivers |
| Suno AI            | External Tool (audio creation) | Medium    | Generates demo audio tracks   |
| Technical Support  | IT help desk                   | Low       | Assist with GitHub/Pages issues |
| Alex Dominicelli   | Peer / Consultant              | Medium    | Provide peer review feedback  |

## 6. Tools & Resources
- **Tools:**
  - GitHub / GitHub Desktop
  - VS Code IDE
  - LiveServer / FiveServer (preview)
  - Suno AI (audio generation)

- **Resources:**
  - CMPA 3301 course materials and Project 3 Proposal Guidance
  - Mozilla Developer Network (MDN) for HTML/CSS reference
  - Instructor feedback

## 7. Risk Analysis (TAME Framework)

- **Technical Risks**
  - Deployment errors with GitHub Pages.  
    *Mitigation:* Test early with LiveServer/FiveServer; verify settings in Pages.  
  - CSS layout challenges without JavaScript support.  
    *Mitigation:* Research course-approved CSS techniques; simplify design.

- **Assumptions Risks**
  - Assume browsers support `<audio>` element consistently.  
    *Mitigation:* Test in Chrome, Firefox, Edge. Provide fallback message.
  - Assume I have the required skill and aptitude to  take on the project as scoped.

- **Management Risks**
  - Scope creep (adding features beyond two pages).  
    *Mitigation:* Enforce acceptance criteria defined in Scope Statement.  
  - Time conflicts with other coursework.  
    *Mitigation:* Weekly checkpoints and early start.
  - Failure to meet all required Documentation and Rubric Requiremtn
    *Mitigation:* Create detailed deliverables checklist and verify all submission were accepted online.

- **External Risks**
  - Reliance on Suno AI for demo songs; service may change/limit features.  
    *Mitigation:* Store generated audio locally in repo assets.  
  - Peer feedback availability (Alex Dominicelli).  
    *Mitigation:* Proceed with self-QA if peer not available.

- **Scope creep:** Adding features beyond two pages. *Mitigation:* enforce acceptance criteria.
- **Deployment errors:** GitHub Pages misconfig. *Mitigation:* test early with LiveServer + GitHub Pages.
- **Time conflicts:** Other coursework deadlines. *Mitigation:* weekly task checkpoints.

## 8. Quality Management
- Deliverables tested against acceptance criteria.
- Cross-browser test (Chrome, Edge, Firefox).
- Peer review by Alex Dominicelli.
- Rewrite session ensures clean final product.

## 9. Communication Plan
- GitHub commits serve as progress log.
- Email instructor for clarifications.
- Submit final repo link + docs to Canvas.

## 10. Definition of Done
The project is **done** when:
- The website (Home + Catalog) is live on GitHub Pages.
- All acceptance criteria are satisfied.
- Documentation (`scope`, `plan`, `retrospective`) is present in `docs/`.
- The project passes QA and rewrite session review.

## 11. Success Criteria
The project is considered **successful** if:
- The deliverable aligns 100% with the Scope Statement.
- All rubric requirements are satisfied (completeness, professionalism, clarity).
- Sponsor (instructor) validates that the site and documentation meet CMPA standards.
- The final product demonstrates proof of concept for *This Is Your Song*.
