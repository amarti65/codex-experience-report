# Codex Experience Report

## The Wizard and the Pet

**A first-use case study by Anthony Martini, observed July 17, 2026.**

Following OpenAI Builder Lounge NYC, I evaluated Codex's desktop onboarding, permission requests, task supervision with Pet, and an initial application build. I originally shared this report with OpenAI as product feedback. This repository makes the observations and recommendations available to other builders and product teams.

**[Read the report in your browser](report.md)** · **[View or download the illustrated PDF](Codex-Experience-Report-2026-07-17.pdf)**

> The first-use experience succeeded technically. The larger adoption challenge was delegation trust: understanding what the agent can access, why permissions are needed, and whether workflows will remain durable as the product ecosystem changes.

## What I tested

- Installation, product identity, and the onboarding wizard.
- Permission requests for access to other applications, the Dock extension, and connectors.
- Pet as a way to monitor and respond to parallel tasks.
- A first grant-tracker build from approximately six pages of unstructured source material.
- Navigation through the OpenAI Platform workflow for creating a project API key.

## Main findings

| Area | Observation from this first-use session |
| --- | --- |
| Application building | Codex produced and deployed a working first version of a sortable grant tracker with fewer interventions than my previous ChatGPT attempt. |
| Onboarding | Guided exercises helped me begin delegating development and business logic to an agent. |
| Task supervision | Pet made it easier to follow parallel tasks while continuing other work. |
| Product and permissions | Product relationships and the purpose of permission requests were not always clear when decisions were required. |
| Capacity and durability | Remaining usage was difficult to interpret, and rapid product changes raised questions about investing in lasting workflows. |

## Recommendations

These impact and effort ratings are my estimates from the original report.

| Recommendation | User impact | Likely effort |
| --- | --- | --- |
| Explain product relationships during onboarding | High | Low |
| Explain permissions before macOS prompts appear | High | Medium |
| Clarify remaining usage and capacity | High | Low |
| Add a standard post-update feature tour | Medium | Low |
| Address workflow portability and retirement concerns | High | High |

## Scope and limitations

This is one user's first-use evaluation, not a controlled benchmark or a longitudinal study. The grant tracker reached a working initial deployment; its data logic and prioritization behavior were not deeply validated. No grant-tracker source code is included here.

The observations describe the desktop experience on **July 17, 2026**. The original build number was not recorded before an update. The report separately documents a subsequently installed build, **ChatGPT 26.715.61943, released July 20, 2026**. Product names and behavior reflect that period and should not be read as current setup instructions.

This is independent personal feedback. Sharing the report with OpenAI does not imply endorsement or affiliation.

## Repository contents

| File | Purpose |
| --- | --- |
| [README.md](README.md) | Overview, key findings, recommendations, and scope. |
| [report.md](report.md) | Markdown reading edition with the detailed walkthrough. |
| [Codex-Experience-Report-2026-07-17.pdf](Codex-Experience-Report-2026-07-17.pdf) | Eight-page illustrated report, using the supplied recipient-redacted copy. Opens without a password. |

The PDF preserves the supplied redacted report's page content and layout. The Markdown edition repairs text-extraction artifacts, reorganizes the page layout for reading, and omits the original cover-letter paragraph. Its figure references point to the PDF.

## Author and citation

[Anthony Martini](https://github.com/amarti65)

Suggested citation: Martini, Anthony. *Codex Experience Report: The Wizard and the Pet.* Evaluation conducted July 17, 2026.

For corrections or discussion of the observations, please open an issue in this repository.
