# The Relationship Architect

# The Relationship Kernel: An External Executive Function Stack

### ⚠️ Status: Active Alpha
**Current Deployment:** Successfully running in a live production environment (Cambridge, MA) to facilitate a new relationship for a neurodivergent user.
**Seeking:** Collaborators, Architects, and Testers to help evolve the framework.

---

### What is this?
This repository is not a collection of "pickup artist" scripts or generic dating advice. It is a **skeleton for a Stateful Dating Architecture.**

Modern dating requires high-speed "Theory of Mind" processing, constant context switching, and real-time boundary enforcement. For "Systemitizers" (SQ-R > 70), engineers, or those recovering from high-control relationships, this processing load can cause system failure (burnout, masking, or missed red flags).

**This project offloads that processing to an external kernel.** By feeding an LLM a persistent "Knowledge Graph" of your identity, values, and hard constraints, the AI stops acting as a generic chatbot and starts acting as a **Chief of Staff** who knows your history, your quirks, and your non-negotiables.

### The Vision: Three Development Paths
We are looking for collaborators to help push this "skeleton" architecture along three distinct but compatible vectors:

#### 1. The Open Source Relationship Protocol (The CLI for RA)
Relationship Anarchy (RA) is a philosophy of "building your own rules," yet most people lack the tools to define those rules clearly.
* **The Goal:** Move from vague "vibes" to clear Configuration Files.
* **The Mechanism:** Using the `relationship_smorgasbord.txt` as a config file, the system compiles potential matches against your dependencies. If you have **Marriage** set to `[OFF]` and **Parallel Play** set to `[CORE]`, the system flags incompatibilities before emotional attachment occurs.

#### 2. The Neuro-Bridge (Translation Layer)
For users with traits like Face Blindness or Social Processing Lag, the dating world is full of invisible data.
* **The Goal:** A "Translation Layer" for the neurodivergent heart.
* **The Mechanism:** The `knowledge.txt` file acts as a User Manual. It allows the system to help the user explain their "Hardware Transparency" (e.g., "I'm not ignoring you; I'm buffering") in a way that creates intimacy rather than confusion.

#### 3. The Safety Sidecar (Objective Auditing)
For survivors of narcissism or gaslighting, "trusting your gut" is often a compromised sensor.
* **The Goal:** An objective third party that never gets tired and never forgets your boundaries.
* **The Mechanism:** The **Auditor Protocol**. The system reviews incoming messages and interactions against your defined constraints. It alerts the user to "Scope Creep" or boundary violations that a human brain might rationalize away in the moment.

### How to Contribute
This project is currently a set of text-based configuration files and prompt architectures. We are looking for:
* **Testers:** To fork the config files, adapt them to their own "Operating Systems," and report back on efficacy.
* **Coders:** To wrap this logic into a more accessible UI or CLI tool.
* **Philosophers:** To refine the `smorgasbord` definitions and safety protocols.

*Fork the repo, update the `knowledge.txt` with your own system specs, and let's debug human connection together.*

The Relationship Architect was created as a collaboration between Pace Willisson and Gemini.

## Table of Contents
1. [Overview](#overview)
2. [Phase 1: Initialization](#phase-1-initialization)
3. [Phase 2: The Core Data Loop](#phase-2-the-core-data-loop-identity--requirements)
4. [Phase 3: The Interface Layer](#phase-3-the-interface-layer-voice--visuals)
5. [Phase 4: Deployment](#phase-4-deployment)
6. [Usage Protocols](#usage-protocols)
7. [Appendix A: How This AI Actually Works](#appendix-a-how-this-ai-actually-works-the-fresh-contractor-analogy)
8. [Appendix B: Glossary of Terms](#appendix-b-glossary-of-terms)

## Overview

The Consultant is composed of two distinct layers:
1.  **The Kernel (System Instructions):** The "Brain." A fixed set of logic, protocols, and personality constraints.
2.  **The User Stack (Knowledge Files):** The "Context." A set of text files defining your specific mission, boundaries, and voice.

## Phase 1: Initialization

To begin, initialize a new Gem (or custom system prompt) with the base logic.

1.  Copy the raw contents of **[system_instructions.txt](https://github.com/pacew/dating-consultant-gem/blob/main/system_instructions.txt)**.
2.  Paste this into the **System Instructions** field of your Gem.

*Note: At this stage, the Consultant is using a generic "Engineer" metaphor. You will personalize this in Phase 2.*

## Phase 2: The Core Data Loop (Identity & Requirements)

This phase uses "Amplified Journaling." You will not just write files; you will use the Consultant to audit them for logical consistency before finalizing them.

### Step A: The Rough Drafts
Create the following files locally:

* **[mission.txt](https://github.com/pacew/dating-consultant-gem/blob/main/mission.txt):** A statement of who you are *outside* of a relationship. This is the entity the Consultant must protect.
* **[relationship_smorgasbord.txt](https://github.com/pacew/dating-consultant-gem/blob/main/relationship_smorgasbord.txt):** The configuration file.
    * You may use any of the values defined in the file header: `[CORE]`, `[OPEN]`, `[NEUTRAL]`, `[SITUATIONAL]`, `[TOLERATED]`, `[OFF]`, or `[N/A]`.
    * **Crucial:** These values must remain enclosed in square brackets (e.g., `[CORE]`, not just `CORE`) for the system to parse them correctly.
* **[dating_profile.txt](https://github.com/pacew/dating-consultant-gem/blob/main/dating_profile.txt):** Your current public-facing bio and prompts.

### Step B: The Consistency Audit
Do not upload these to the "Knowledge" section yet. instead, open a **chat window** with your initialized Consultant and upload the three files.

Paste this text into the chat:
```
Act as a logic auditor. Compare my Mission, my Smorgasbord,
and my Dating Profile. Identify contradictions. Where does
my Profile promise something my Smorgasbord marks as [OFF]?
Where does my Smorgasbord demand something that conflicts
with the autonomy described in my Mission? Be blunt.
```

**The Work (The Dialog):**
This is a collaborative dialog, not just a pass/fail test. Interact with the Consultant to refine your data:
* **Drafting & Revising:** You can ask the Consultant to rewrite sections of your Profile or Mission to better reflect the hard boundaries in your Smorgasbord.
* **Clarifications:** If a standard Smorgasbord row feels too broad, ask the Consultant to help you write a specific comment for that row, or suggest new rows entirely to capture a specific nuance of your life.
* **Thought Experiments:** If you are having trouble choosing an answer for an item in the smorgasbord, ask the Consultant: *"Construct a thought experiment to test my reaction to financial entanglement."* The Consultant will present a hypothetical scenario to help you gauge your visceral reaction, which you can then codify into the file.

**Finalizing Metadata:**
Before you finish, ensure the profile includes the necessary technical specs.
* **Run this prompt:** *"Help me add a `[LOGISTICS & METADATA]` section to the bottom of `dating_profile.txt`. Based on my Mission and Bio, fill in standard fields (Age, Location, Height, Politics, Religion, Job, etc.) and ask me for any missing data points."*

*Action:* Edit the local files until the Consultant finds no logical contradictions and the data feels accurate.

### Step C: Defining the Metaphor
The Consultant needs to think using your cognitive framework, not the default Engineer logic.

Paste this text into the same chat:
```
Based on the finalized Mission and Smorgasbord we just
agreed on, what is my cognitive style? Am I an Architect,
a Curator, a CEO, or a Gardener? Define my 'Chaos Tolerance'
and my 'Emotional Reward' mechanism.
```

### Step D: The Final Build
Now that the files are audited and the metaphor is defined, ask the Consultant to generate the final code for you to download.

Paste this text into the chat:
```
We have finished the audit and defined the metaphor.
Please generate the final versions of the following files,
updated with all our changes and your specific formatting:

1. `system_instructions.txt` (Update Section 1 with my
   details and Section 2 with the '[Metaphor Name]' persona).
2. `mission.txt`
3. `relationship_smorgasbord.txt`
4. `dating_profile.txt` (including the metadata section).

Present each file in a separate code block for easy copying.
```

**Action:** Copy the content of these code blocks into your local files, overwriting the rough drafts.

## Phase 3: The Interface Layer (Voice & Visuals)

Now that the logic is solid, we define how you present to the world.

### Step A: Voice Analysis
1.  Gather 5-10 previous emails or messages that represent your authentic voice at its best (clear, kind, effective).
2.  Paste them into a single document (e.g., `past_emails.txt` or a Word doc) and **upload that file** to the chat.
3.  Paste this text into the chat:
    ```
    Analyze the uploaded file to capture my natural voice.
    Create a `messaging_style_reference.txt` that preserves
    my personality but applies an 'Anti-Hedging' filter—rewrite
    my habits to be direct and clear (e.g., changing 'I guess
    we could...' to 'I would like to...').
    ```
4.  Save the output as **[messaging_style_reference.txt](https://github.com/pacew/dating-consultant-gem/blob/main/messaging_style_reference.txt)**.

### Step B: Photo Curation
1.  Upload a batch of potential profile photos (10-15 is ideal, but the Consultant can work with fewer).
2.  Paste this text into the chat:
    ```
    Select the best 4-6 photos that tell a coherent story
    consistent with my `mission.txt`. Explain your reasoning
    for each selection (why this photo works). Crucially,
    evaluate the narrative: is there a gap in the story?
    Suggest one specific photo I should take to fill that gap.
    ```

## Phase 4: Deployment

Once the files are audited and the System Instructions are updated with the Metaphor:

1.  Download **[nvc_inventory.txt](https://github.com/pacew/dating-consultant-gem/blob/main/nvc_inventory.txt)** from the repository (this file rarely needs editing).
2.  Upload the final versions of the following to the Gem's **Knowledge** section:
    * `mission.txt`
    * `relationship_smorgasbord.txt`
    * `dating_profile.txt`
    * `messaging_style_reference.txt`
    * `nvc_inventory.txt`
3.  **Save** the Gem.
4.  **Start a New Chat.**

The Consultant is now live.

## Usage Protocols

* **Screening Matches:** Paste a match's profile text. Ask: *"Audit this match against my Smorgasbord."*
* **Drafting Messages:** Provide a rough idea. Ask: *"Draft this using my Messaging Style."*
* **Maintenance:** Every 3 months, ask the Consultant to review if your choices in chat are drifting from the hard-coded `mission.txt`.

---

## Appendix A: How This AI Actually Works (The "Fresh Contractor" Analogy)

To explain how this system works to non-technical users, use the **"Fresh Contractor" Analogy**:

* **The Setup:** Imagine you hire a specialized consultant (the AI) to work on a project.
* **The Constraint:** Every time you ask a question, the consultant answers and then is fired. Their memory is wiped immediately after answering.
* **The Next Question:** When you ask a follow-up, you hire a *new* consultant who is an exact clone of the first one, but they have never met you.
* **The Solution:** To make it work, you (the system) hand the new consultant a clipboard containing a transcript of everything said so far (your Knowledge Files and Chat History). The new consultant reads the transcript in milliseconds, gets up to speed, and answers as if they’ve been there the whole time.

This implies that if the "clipboard" (your Knowledge Files) contains contradictions or vagueness, the Contractor will fail. This is why we spend Phase 2 strictly editing the files.

## Appendix B: Glossary of Terms

The Consultant uses specific terminology derived from **Relationship Anarchy** and **Nonviolent Communication**.

### 1. The Relationship Smorgasbord
A conceptual tool that breaks a relationship down into individual components (Sex, Finances, Living arrangements, Kink, etc.). While originally developed to design non-traditional relationships, it works equally well for defining traditional ones. In this system, it serves as a precision instrument: by listing exactly what you want, the Consultant can detect when your dating profile language might be interpreted in ways incompatible with your true desires, preventing poor matches.
* *External Resource:* [The Relationship Anarchy Smorgasbord (Multiamory)](https://www.multiamory.com/podcast/339-the-smorgasbord-of-relationships)

### 2. Key Terms defined in `relationship_smorgasbord.txt`
* **Relationship Anarchy (RA):** A philosophy that rejects the "Relationship Escalator" (the idea that dating must progress to marriage and kids). It treats every relationship as unique.
* **Kitchen Table Polyamory:** A style where partners and "Metamours" (partners' partners) are comfortable hanging out together as a group (like sitting around a kitchen table).
* **Parallel Polyamory:** A style where relationships run on separate tracks. You might know of your partner's other partners, but you rarely interact.
* **Metamours:** Your partner's other partners.
* **NVC (Nonviolent Communication):** A communication framework based on `Observation > Feeling > Need > Request`. It is designed to remove blame and increase clarity.
* **Living Apart Together (LAT):** A committed relationship where partners choose to maintain separate residences.
