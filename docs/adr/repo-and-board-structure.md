 
# 1. GitHub Repo and Shared Board design

## Status

Pending

## Background

The Delivery Assurance team needs to be able to:

- Easily onboard and ramp up individuals,
- Intake work from many different streams, including but not limited to;
  - Directly from Leadership Teams asks,
  - One-off, tightly scoped pieces of work from other sources (fka #help-wanted and #microrequests),
  - Guides & Methods repos, and
  - Tock repo.
- Prioritize, assign, and track work from these disparate streams

## Proposal

In order to accommodate these needs, we propose:

- A GitHub repo to intake issues that are direct asks from the Leadership Team and are one-off,
  scoped pieces of work being requested from other sources. This repo will also be the source of
  truth for Delivery Team documentation.
- A shared GitHub Projects board that will pull work in from the Delivery Assurance repo, along
  with other project repos in order to prioritize, assign, and track the work in one place.

In order to make this workflow more seamless, we also propose:

- Creating an issues template that provides some data to make prioritization for the leadership
  team easier.
- Creating a GitHub action so that new issues in the anticipated repos are automatically added
  to the backlog page.

## Reasons

A shared Projects board is not associated with any one GitHub repo; instead, multiple repos can
be linked to the board via the GitHub GUI. Using that rather than a single repo Projects board
means that the team won’t have to copy issues over in order to track the work. This saves time,
energy, and is a lot less tedious for the team.

There are two different ways to add issues to a shared Projects board.

When you create an issue, there is a Projects option in the right side-nav that allows you to
add it manually. However, this is easy to miss and adds burden to the individual adding the
issue. Risks include important issues not being added, prioritized, or tracked.

Adding a GitHub action to automatically add issues to the shared Projects board means every
single issue will be added. This means the Team Lead and Executive Sponsor will have to
prioritize, and maybe delete some issues from the Projects board that are superfluous in some
way. Since the team will be doing backlog grooming at the start of every iteration to ensure
priority and expertise, that seems like a safer way of intaking work from different repos.

We want to ensure that the Leadership Team does not get bogged down in backlog grooming.
To mitigate that risk, we want to create an issues template for each anticipated repo that
includes comprehensive information about what the ask is, what success looks like, and the
anticipated time it will take to complete the work. This will also help set individual team
members up for success in completeing the task without having to chase down additional
context.
