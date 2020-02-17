---
name: RFC Template
about: Template to be used when creating a new RFC (request for comment).
title: 'RFC: <description of changes>'
labels: help wanted, discussion
assignees: cedricium

---

---
Start Date: YYYY-MM-DD (replace with today's date)
Unearth Issue: issue \# in main Unearth repo if applicable, else leave blank
---

## Summary

Brief explanation of the feature.

## Basic Example

If the proposal involves a new or changed API, include a basic code example.
Omit this section if it's not applicable.

## Motivation

Why are we doing this? What use cases does it support? What is the expected
outcome?

Please focus on explaining the motivation so that if this RFC is not accepted,
the motivation could be used to develop alternative solutions. In other words,
enumerate the constraints you are trying to solve without coupling them too
closely to the solution you have in mind.

## Detailed Design

This is the bulk of the RFC. Explain the design in enough detail for somebody
familiar with Unearth to understand, and for somebody familiar with the
implementation to implement. This should get into specifics and corner-cases,
and include examples of how the feature is used. Any new terminology should be
defined here.

## Drawbacks

Why should we not do this? Please consider:

- implementation cost, both in term of code size and complexity
- whether the proposed feature can be implemented in user space
- the impact on teaching people Unearth
- integration of this feature with other existing and planned features
- cost of migrating existing Unearth applications (is it a breaking change?)

There are tradeoffs to choosing any path. Attempt to identify them here.

## Alternatives

What other designs have been considered? What is the impact of not doing this?

## Adoption Strategy

If we implement this proposal, how will existing Unearth developers adopt it? Is
this a breaking change?

## How We Teach This

What names and terminology work best for these concepts and why? How is this
idea best presented? As a continuation of existing Unearth patterns?

Would the acceptance of this proposal mean the Unearth documentation must be
re-organized or altered? Does it change how Unearth is taught to new developers
at any level?

How should this feature be taught to existing Unearth developers?

## Unresolved Questions

Optional, but suggested for first drafts.

## What parts of the design are still TBD?
