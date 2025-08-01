# W3PN Infrastructure Guild 🪚

> The digital plumbers, electricians, and janitors of our ecosystem. We provide the resilient, reliable, and convivial platforms that empower our community to build and collaborate effectively.

This repository is the central hub for the Infrastructure Guild's **work**. Here you will find our project board, our open tasks (Issues), and our contributions (Pull Requests). For community discussion and formal governance, please see our [Zulip "Commons"](https://commons.w3pn.org/).

---

## 💂 Guild Stewards

Stewards are the guardians and facilitators of this guild, not its managers. They are here to help unblock contributors, manage core credentials, and ensure our principles are upheld. They can help you craft a Formal Proposal for Zulip if needed.

- Tree ([@burningtree](https://github.com/burningtree))
- Mf ([@debelg](https://github.com/debelg))

Feel free to tag them in an Issue or PR if you need administrative help or guidance.

---

## Our Mission

Our mission is to build and maintain the foundational infrastructure that our community relies on. We do this not as gatekeepers, but as enablers. We succeed when our infrastructure is so reliable it's invisible, and when our tools are so effective that community members are empowered to self-serve without needing to ask for permission.

---

## 🏛️ Core Principles

Our work is guided by the core principles of the main [Community Constitution](https://docs.w3pn.org/constitution/). Specifically, we operate on:

1.  **Reliability & Resilience:** Our systems must be dependable. We prioritize stability, implement monitoring, and conduct blameless post-mortems when things fail.
2.  **Empowerment through Automation:** Our goal is to automate ourselves out of a job. We build self-service tools that allow contributors to deploy and manage projects without creating bottlenecks.
3.  **The Principle of Conviviality:** We choose tools that enhance user freedom and autonomy. This means favouring open-source, privacy-preserving, and self-hostable systems.
4.  **Public by Default:** Most of our work, discussions, and decision-making happen in public channels. This ensures transparency and allows anyone to learn from our process.
5.  **Pragmatic & Iterative:** We favour practical solutions and continuous improvement over seeking perfection. We launch, we learn, we iterate.

---

## 🗺️ What We Do (Our Scope)

The Infrastructure Guild is responsible for the following shared resources.

**In Scope:**
*   🌐 **Domains & DNS:** Managing domain registration and DNS records.
*   ☁️ **Cloud/hosting Providers:** Managing access and billing for our core cloud/hosting accounts (e.g., VPS, barebone).
*   🚀 **CI/CD & DevOps:** Building and maintaining shared Radicle, Woodpecker or GitHub Actions, Runners and deployment pipelines.
*   🛠️ **Community Tooling:** Hosting and maintaining community-wide tools (e.g., our websites, Zulip forum, Grafana, photo archive).
*   🔐 **Security & Access:** Managing repository permissions, secret management (e.g., Bitwarden, Authentik), and security best practices.
*   📊 **Monitoring & Alerting:** Keeping an eye on the health of our shared services.

**Out of Scope:**
*   Application-level code and bugs (this belongs to the specific project teams).
*   Individual project budgets or roadmaps.

---

## 🤝 How to Contribute (Our Workflow)

Our guild operates on **Intentional Do-ocracy**. You have the agency to make things happen. This workflow is for organizing and executing work **within the guild**.

1.  **Discuss the Idea:** Start a conversation in the [`#infra` channel on Zulip](https://commons.w3pn.org/#narrow/stream/infra). This is where we do our initial brainstorming and coordination.
2.  **Define the Work:** Once an idea is ready to become an actionable task, create a **[GitHub Issue](https://github.com/web3privacy/infra/issues)**. This is our "to-do" list. It is not a formal proposal, but a work-tracking item.
3.  **Do the Work:** Assign the issue to yourself (or ask to have it assigned) and start working. Open a **Draft Pull Request** early to show progress and get feedback.
4.  **Reflect and Complete:** When the PR is ready, request reviews. Once merged, close the issue and post a brief summary of your work back in the [`#infra` Zulip channel](https://commons.w3pn.org/#narrow/stream/infra) so the community can see what was accomplished.

---

## 💬 Communication Channels

-   **💬 Primary Discussion (Public):** The [`#infra` channel on our "Commons" Zulip](https://commons.w3pn.org/#narrow/stream/infra) is our guild's public square. Use it for questions, brainstorming, sharing updates, and general chat.

-   **⚖️ Formal Community Proposals (Public):** The [`#proposals` channel on "Commons" Zulip](https://commons.w3pn.org/#narrow/stream/proposals) is the **official venue for all community-wide Formal Proposals**. If the Infra Guild needs budget or is making a decision that affects the whole community, we will post it there.

-   **🏗️ Guild Work Tracking (Public):** We use [GitHub Issues and PRs](https://github.com/web3privacy/infra/issues) to organize the day-to-day tasks of this guild. This is our workshop, not our parliament.

-   **🔒 Internal Communication (Private):** We use a private Signal/Zulip groups for sensitive matters that cannot be public (e.g., security vulnerabilities). Contact a Guild Steward for access.

---

## ⚖️ Governance: Guild Work vs. Community Proposals

It is crucial to understand the two levels of decision-making:

### Level 1: Guild-Internal Work
Our own tasks are managed within the guild using a lightweight do-ocracy. We use **GitHub Issues** to define work and **Pull Requests** to review it. We trust contributors to make good decisions, and the authority for a task lies with the person doing it. This is **not** a formal governance process.

### Level 2: Formal Community Proposals
When a decision requires community consent as defined by the Constitution—such as spending treasury funds, adopting a new core technology for everyone, or changing a shared brand asset—the Infrastructure Guild must initiate a **Formal Proposal on Zulip**.

This process is handled entirely in the **[#proposals channel on "Commons" Zulip](https://commons.w3pn.org/#narrow/stream/proposals)** and follows the "Lazy Consensus" model: a 72-hour review period where silence equals consent.

**GitHub is never used for formal, binding community proposals.**
