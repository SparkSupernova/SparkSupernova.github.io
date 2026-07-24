# Project Plan

## Planning Approach

This plan treats the portfolio as a small technical artifact carrying a complex
research-communication responsibility. The critical path runs from scope
definition to public-source verification, research synthesis, page development,
documentation, deployment, and final validation. Optional features cannot delay
the required deliverables, but simplification cannot erase the intellectual
structure of the work.

## Risk Assessment Method

Risks are scored using the Chapter 4 method:

`Impact × Probability = Risk Score`

Impact and probability use a 1–5 scale. The response uses the TAME framework:
Transfer, Accept, Mitigate, or Eliminate.

## TAME Risk Analysis

| Risk | Impact | Probability | Score | TAME Response | Planned Action | Owner |
| --- | ---: | ---: | ---: | --- | --- | --- |
| Missing the final deadline because the project started late | 5 | 5 | 25 | Mitigate | Freeze optional features, work from the rubric, and complete critical-path deliverables first | Ifejah |
| Accidentally publishing proprietary architecture | 5 | 3 | 15 | Eliminate | Use public sources only and exclude private code, data, schemas, and internal metrics | Ifejah |
| Scope creep from treating a two-page prototype like a production platform | 4 | 4 | 16 | Mitigate | Enforce the scope statement and defer forms, JavaScript features, extra pages, and backend work | Ifejah |
| GitHub Pages deployment delay or failure | 4 | 3 | 12 | Mitigate | Use the required repository name, deploy from `main`, and verify the Pages workflow and HTTP response | Ifejah / GitHub |
| Public link changes after submission | 3 | 2 | 6 | Accept | Verify links at submission time and keep project files available in the repository and ZIP | Ifejah |
| Remote fonts fail to load | 2 | 2 | 4 | Accept | Provide readable system-font fallbacks in CSS | Ifejah |
| The project loses coherence as documentation is added | 3 | 3 | 9 | Mitigate | Keep the same purpose, terminology, visual system, and acceptance criteria across every artifact | Ifejah |
| Protective simplification makes an established research program look immature | 5 | 4 | 20 | Mitigate | Preserve the public theory-to-application hierarchy and verify that named contributions appear in both pages and documentation | Ifejah |

## Work Breakdown Structure

### 1. Initiation and Scope

- Identify project purpose and intended audience
- Review course rubric and technical requirements
- Define what is in scope and out of scope
- Identify privacy and intellectual-property boundaries

### 2. Content and Evidence

- Review public SparkPlugged website
- Review public GitHub profile and repositories
- Review public NovaLiveSystem showcase
- Review published preprints, public model cards, and evaluation dataset
- Select claims appropriate for a general audience
- Map claims into theory, architecture, models/evaluation, infrastructure, and application
- Draft homepage and About-page content without flattening the research hierarchy

### 3. Technical Implementation

- Build semantic homepage structure
- Create responsive visual system in one stylesheet
- Add accessible navigation and focus states
- Build the linked About page
- Check internal and external links

### 4. Project Documentation

- Revise the scope statement
- Assess risks using TAME
- Create the WBS and schedule
- Write the project retrospective
- Update the repository README

### 5. Version Control and Deployment

- Commit the homepage structure
- Commit the visual design
- Commit the README
- Commit the second page
- Commit project-management documentation
- Push changes to the public GitHub repository
- Monitor GitHub Pages deployment

### 6. Quality Assurance and Submission

- Verify required files
- Check shared stylesheet usage
- Check responsive rules and accessibility features
- Confirm both live pages return successfully
- Create a clean submission ZIP
- Submit the repository and live-site links

## Task Schedule

| Sequence | Task | Dependency | Estimated Duration | Deliverable |
| ---: | --- | --- | ---: | --- |
| 1 | Confirm requirements and scope | None | 30 minutes | Approved project boundary |
| 2 | Gather and verify public content | 1 | 45 minutes | Evidence-backed content set |
| 3 | Build homepage HTML | 2 | 60 minutes | `index.html` |
| 4 | Build shared responsive styles | 3 | 90 minutes | `style.css` |
| 5 | Write and link About page | 3–4 | 45 minutes | `about.html` |
| 6 | Write scope and project plan | 1–5 | 60 minutes | `scope.md`, `plan.md` |
| 7 | Write retrospective | 3–6 | 30 minutes | `retrospective.md` |
| 8 | Update README and verify structure | 5–7 | 30 minutes | `README.md` |
| 9 | Commit and deploy | 8 | 20 minutes | Public repository |
| 10 | Verify live site and package submission | 9 | 20 minutes | Live site and ZIP |

## Critical Path

The critical path is:

`requirements → public evidence → research synthesis → homepage → shared styling → About page → documentation → deployment → verification`

Documentation can begin before visual polishing is complete, but deployment
cannot occur until both pages, the shared stylesheet, and the README are ready.

## Communication Plan

| Audience | Information | Channel | Timing |
| --- | --- | --- | --- |
| Instructor | Final repository and live-site links | Canvas submission | At completion |
| General visitor | Purpose, selected work, and professional links | Website and README | Continuous after publication |
| Project owner | Scope, risks, completion state, and lessons learned | Repository documentation and commit history | At each major milestone |

## Change-Control Rule

A proposed change is accepted only if it directly supports a rubric requirement,
fits before the deadline, and does not expose private information. Otherwise, it
is deferred. This rule protects time, scope, and quality as a connected triple
constraint rather than treating each one separately.
