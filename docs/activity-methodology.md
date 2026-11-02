# GitLab activity methodology

These grids summarize available GitLab activity from 2022 through 2026. The history was recovered on November 2, 2026. The 2026 grid covers January 1 through that date; later dates are faded.

## What is counted

Each square shows the number of recovered activity records for that day. Records include:

- Authored commits, including merge and squash commits.
- Merge requests opened, and merges or closures attributed to me.
- Comments and code review comments.
- Approvals and approval removals.
- Merge request system notes recording added commits.
- Authored issues, where available.

A single piece of work can produce several records, such as a commit, a merge request update and an approval. These totals describe recorded activity rather than completed tasks or productivity.

## How the history was recovered

Merge requests were discovered through authorship and available reviewer or assignee records. Their discussions and authored merge request commit histories were inspected alongside local Git history. Reviewer assignment alone is not counted.

Records are deduplicated by their source identifiers. Commits are deduplicated by commit hash; original, merge and squash commits can still represent the same underlying work.

Dates use Asia/Manila. Commits use their author timestamps; other records use their recorded action timestamps. Every year uses the same color scale: 0, 1–3, 4–7, 8–14, and 15 or more records per day. An active day has at least one recovered record.

## Coverage limits

This is a partial reconstruction. Comment-only participation, issue discussions, commit comments, inaccessible projects and deleted or expired records may be missing. Merge request commit-update notes do not establish original push counts or branch creation dates.

The grids are a separate historical overview, not a reproduction of GitLab’s original contribution calendar or GitHub’s native contribution graph. They are static snapshots and do not update automatically.

## Public data

This repository publishes aggregate grid images and this methodology. Raw API responses, discussion contents, company project details, internal links, detailed record archives and access tokens are excluded.
