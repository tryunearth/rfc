# Unearth RFCs

**RFCs (request for comments) for changes to Unearth.**

The RFC process is intended to provide a consistent and controlled path for new
features to enter the project.

The Gatsby team said it best and we at Unearth believe the same:

> Many changes, including bug fixes and documentation improvements can be
> implemented and reviewed via the normal GitHub pull request workflow.
>
> Some changes though are "substantial", and we ask that these be put through a
> bit of a design process and produce a consensus among the Gatsby core team.

## When to follow this process

You should consider using this process if you intend to make "substantial"
changes to Unearth or its documentation. Some examples that would benefit from an
RFC are:

- A new feature that creates a new API surface area, and would require a feature
  flag if introduced.
- The removal of features that already shipped as part of the release channel.
- The introduction of new idiomatic usage or conventions, even if they do no
  include code changes to Unearth itself.

The RFC process is a great opportunity to get more eyeballs on your proposal
before it becomes a part of a released version of Unearth. Quite often, even
proposals that seem "obvious" can be significantly improved once a wider group
of interested people have a chance to weigh in.

The RFC process can also be helpful to encourage discussions about a proposed
feature as it is being designed, and incorporate important constraints into the
design while it's easier to change, before the design has been fully implemented.

## What the RFC process is

The Unearth RFC process is a bit simpler than Unearth's in which we utilize GitHub
Issues rather than PRs to encourage discussions. To get started:

- [Create a new issue](https://github.com/tryunearth/rfcs/issues/new?assignees=cedricium&labels=help+wanted%2C+discussion&template=rfc-template.md&title=RFC%3A+%3Cdescription+of+changes%3E)
  in this repo using the RFC Template
- Fill in the RFC. Put care into the details: RFCs that do not present
  convincing motivation, demonstrate an understanding of the impact of the
  design, or are disingenuous about the drawbacks or alternatives tend to be
  poorly-received.
- Submit the issue. As an issue, the RFC will receive design feedback from the
  larger community (Cedric for now), and you as the author should be prepared
  to revise it in response.
- Build consensus and integrate feedback. RFCs that have broad support are much
  more likely to make progress than those that don't receive any comments.
- Eventually, the team will decide whether the RFC is a candidate for inclusion
  in Unearth.

## Implementing an RFC

The author of an RFC is by no means obligated to implement it. Of course, the
RFC author (like any other developer) is welcome to post an implementation for
review after the RFC has been accepted.

If you are interested in working on the implementation for an 'active' RFC, but
cannot determine if someone else is already working on it, feel free to ask
(e.g. by leaving a comment on the associated issue).

## Credit

Unearth's RFC process owes its inspiration to the
[Gatsby RFC process](https://github.com/gatsbyjs/rfcs).
