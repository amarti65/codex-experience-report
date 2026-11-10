# Codex Experience Report

## The Wizard and the Pet

**Evaluation date:** July 17, 2026  
**Prepared by:** Anthony Martini  
**Context:** OpenAI Builder Lounge NYC follow-up

> **Editorial note:** This reading edition converts the supplied report to Markdown and repairs text-extraction artifacts. Running page headers and footers, the blank recipient field, and the original cover-letter paragraph requesting replacement promotional credits have been omitted. Screenshots and the supplied redacted content remain available in the [PDF report](Codex-Experience-Report-2026-07-17.pdf). These are observations from the evaluation date, rather than current product documentation.

### Bottom line

The first-use experience succeeded technically. The larger adoption challenge was delegation trust: understanding what the agent can access, why permissions are needed, and whether workflows will remain durable as the product ecosystem changes.

## Executive Summary

My first experience with the new ChatGPT desktop application and Codex was materially better than my previous attempt to build an application through ChatGPT. Codex successfully produced and deployed a working first version of a grant-tracking application from six pages of unstructured source material.

The strongest parts of the experience were the guided startup process, the improved application-building capability, and Pet, which made it easier to monitor and respond to multiple tasks without continuously switching windows.

### Key Insights

| Area | Observation |
| --- | --- |
| Delegation | Onboarding increased my willingness to delegate business logic to an agent. |
| Execution | Codex produced a working application more easily than my previous ChatGPT attempt. |
| Multitasking | Pet reduced window switching and made parallel task supervision easier. |
| Permissions | Requests appeared before their purpose was sufficiently clear. |
| Product clarity | Multiple app identities created uncertainty about which application and feature set I was using. |
| Durability | Rapid product turnover creates hesitation about investing deeply in workflows. |
| Capacity | The usage display did not clearly communicate how much capacity remained. |

### Overall Impressions

Overall, the first-use experience was successful. Codex worked better than my previous development attempt, Pet was genuinely useful, and the onboarding helped me begin thinking differently about delegating development and business logic to an agent.

The main friction came from product and permission ambiguity. After the update, I had ChatGPT, ChatGPT Classic, and Atlas installed, while the relationship among Chat, Codex, Work, and Pet was not immediately clear. Permission requests involving the Dock, extensions, and access to other applications also appeared before I fully understood why they were needed.

The usage display could more clearly communicate how much work remained available. I completed the guided exercises and a first application build, but did not have enough additional iterations to determine how useful Codex would become in a sustained workflow.

My broader hesitation is workflow durability. The pace at which AI products change makes me cautious about investing deeply in workflows that may later become unsupported, inaccessible, or difficult to migrate.

### Recommendations

*Impact and effort ratings are the author's estimates from the report.*

| # | Recommendation | User impact | Likely effort |
| --- | --- | --- | --- |
| 1 | Explain product relationships during onboarding | High | Low |
| 2 | Explain permissions before macOS prompts appear | High | Medium |
| 3 | Clarify remaining usage and capacity | High | Low |
| 4 | Add a standard post-update feature tour | Medium | Low |
| 5 | Address workflow portability and retirement concerns | High | High |

## Detailed Walkthrough

### 1. Installation and Product Identity

#### Observation

The installation itself was easy, but unlike a typical update it required both an email authentication code and a second code by text.

Following the update, I had the new ChatGPT desktop application alongside ChatGPT Classic, while Atlas remained separately installed. ChatGPT and ChatGPT Classic used similar visual identities, and the relationship among Chat, Codex, Work, and Pet was not immediately apparent.

#### User impact

I was not always certain which application I had opened or which capabilities belonged to each product. A migration screen or clearer visual distinction for the legacy application would reduce this ambiguity.

### 2. Wizard and First-Use Experience

The onboarding wizard was useful, but it did not function as a conventional “What's New” tour. I expected a concise summary of the major changes introduced by the update.

The role-selection wizard used a strong crystal-dispersion visual language.

#### Wizard, Demo, and Permission Context

I selected Engineering. As a founder, I ultimately need an AI assistant to support multiple disciplines rather than remain confined to a single role. The role-based framing reflects how many people use AI today; the longer-term opportunity feels closer to a complete operating layer for a business.

The demo was simple and effective. I asked it to create a diagram from the sample data. The result appeared more accurate and structurally coherent than similar outputs I had received previously. I also completed setup tasks including a weekday morning brief and a GitHub repository triage task; the suggestion panel cleared cleanly after completion.

### 3. Permission Requests

#### “Data from other apps”

The wording was difficult to interpret because the explanatory text emphasized keeping app data separate while the action requested broader access. I was unsure which part came from macOS and which part came from OpenAI.

The prompt appeared before I had a complete mental model of why the access was needed.

Because the privacy boundaries were not yet fully clear, I declined the request initially. I would begin with lower-sensitivity operational work, such as sorting and prioritizing grant opportunities, rather than proprietary or strategically sensitive material.

#### Dock Tile Extension

The settings path was straightforward: System Settings > Login Items & Extensions. In retrospect, it made sense that this approval enabled Pet as a Dock tile, but that connection was not obvious when the request first appeared.

#### Connector Approval

The connector approval screen appropriately foregrounded risk, but it did so before clearly establishing the feature's practical purpose. I appreciated the control to approve or decline the action.

I would be comfortable testing broader machine access on a dedicated Mac mini configured for specific workflows before granting the same access on my primary machine.

### 4. Pet

#### Why it mattered

Pet reduced the cost of supervising parallel tasks. Rather than repeatedly reopening separate windows, I could monitor progress and respond while continuing other work. This made agentic work feel less disruptive and more compatible with my normal desktop workflow.

Because Pet was demonstrated during the Builder Lounge session, I knew to look for it. It was easy to find, enable, and power up once I understood the Dock extension requirement.

*[“Olivia” monitoring multiple tasks from a Mediterranean orchard — PDF, page 6.](Codex-Experience-Report-2026-07-17.pdf#page=6)*

The feature was particularly useful for keeping separate work threads visible. My prior desktop workflow encouraged a self-imposed limit on simultaneous chats because supervising multiple conversations required more window switching.

### 5. First Application Build

For my first application build, I selected the Terra model and provided approximately six pages of unstructured grant and opportunity information aggregated through ChatGPT. I asked Codex to create a deadline-first tracker with filtering, prioritization, warnings, and per-submission actions.

*[Initial build prompt for the grant and opportunity tracker — PDF, page 7.](Codex-Experience-Report-2026-07-17.pdf#page=7)*

#### Application Outcome

The first deployment produced a functioning, sortable grant-tracking interface.

#### Outcome

Codex produced and deployed a working first version with fewer interventions than my prior attempt through ChatGPT. The project was successfully out the door; additional usage would have allowed deeper validation of the data logic and prioritization behavior.

### 6. Platform / API Test

I used Codex to navigate the OpenAI Platform workflow for creating a project API key. The interaction was straightforward and required little manual navigation. A clearer final confirmation about what had been created, where the credential belonged, and how it should be stored securely would make the experience stronger.

## Version Note

This evaluation reflects the desktop build available on July 17, 2026. The application updated before I recorded the original version number; the version shown below is the subsequently installed build.

**Subsequently installed build:** ChatGPT 26.715.61943, released July 20, 2026.

## Conclusion

The first-use experience moved Codex from an abstract capability to a tool I could imagine using regularly. The strongest adoption drivers were successful task completion, the guided exercises, and Pet's support for supervising parallel work. The primary barriers were not technical complexity, but product clarity, permission context, usage transparency, and confidence that workflows will remain durable as the product suite evolves.

With clearer product mapping and more contextual explanations around permissions and remaining usage, I would be substantially more likely to continue building Codex into my operating workflow.
