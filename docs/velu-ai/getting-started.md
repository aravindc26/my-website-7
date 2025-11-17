---
title: Getting Started with Velu AI
sidebar_position: 2
---

Kickstart your Velu AI workspace with these onboarding steps, built from the Phase 1 product plan.

## 1. Confirm prerequisites

- **Velu AI access:** Ensure you have an organization account and the appropriate role (admin or reviewer) for approving documentation updates.
- **GitHub account:** Velu AI ships documentation changes through your source repositories, so you need an active GitHub account with access to the target documentation repo.
- **Context system credentials:** Collect admin or integration tokens for the knowledge sources you plan to connect, such as Google Drive, Slack, Linear/Jira, Confluence, Notion, and Zendesk.

## 2. Create your workspace and invite collaborators

1. Sign in to Velu AI and create or join your organization workspace.
2. Invite teammates across technical writing, product, engineering, and support so they can review, approve, or consume updates.
3. Define default governance rules—set reviewers for high-risk docs, choose the style guide Velu AI should enforce, and decide when approvals are mandatory.

> Velu AI emphasizes safe automation with role-based approvals, hallucination scoring, and audit logs, so configuring these early increases trust as the system drafts changes.

## 3. Connect your documentation repository

Immediately after sign-up, Velu AI walks you through GitHub setup. Authorize the Velu AI GitHub app, pick the repository (or directories) that store your documentation, and confirm the branch where Velu will open pull requests. This connection lets Velu AI publish diff-based updates while preserving your existing review workflow.

## 4. Add context sources for continuous ingestion

In the same onboarding flow, choose the systems Velu AI should listen to:

- **Google Drive** for specs, meeting notes, and legacy docs.
- **Slack** to capture feature discussions and customer feedback threads.
- **Linear/Jira** for roadmap changes and release notes.
- **Zendesk or other ticketing tools** to surface recurring support issues.
- **Confluence/Notion/Git repos** to sync reference docs into Velu’s context graph.

Velu AI builds a knowledge graph from these sources so it can detect stale content and draft accurate updates.

## 5. Run your first documentation update

1. From the Velu AI console or Slack bot, run a stale-content scan on the repositories you connected.
2. Review the proposed diffs. Velu AI highlights what changed, references the signals it used (tickets, commits, meeting notes), and applies your documentation style rules.
3. Approve changes that look correct, request edits, or assign a reviewer to keep the human-in-the-loop safety net intact.

## 6. Generate a new article with Velu AI

1. Open the "Ask Velu" interface and prompt it to draft an article—for example, “Create a release note for the new Slack integration.”
2. Velu AI searches the context sources you connected (Google Drive, Slack, Linear/Jira, etc.) to assemble accurate, up-to-date content.
3. Inspect the draft, tweak any details, and confirm the citation trail if needed.
4. When satisfied, select **Create Pull Request**. Velu AI pushes the article to your GitHub documentation repo so it enters your standard review and deployment pipeline.

## 7. Next steps

- Configure additional connectors (video/audio ingestion, Chrome extension) as they become available to capture richer product context.
- Track automation metrics: percentage of docs updated automatically, turnaround time from release to published documentation, and help center coverage.
- Expand governance—fine-tune hallucination thresholds, add SOC2-friendly audit exports, and iterate on approval workflows as confidence grows.

With these steps complete, Velu AI acts as your documentation brain—continuously converting product knowledge into trusted, publish-ready content.
