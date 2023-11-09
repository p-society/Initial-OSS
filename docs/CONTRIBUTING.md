# Contributing to Repositories Under Initial OSS

First off, thanks for taking the time to contribute!
We are so happy to have you! :tada:

There are opportunities to contribute to Initial OSS at ANY level.
It doesn't matter if you are just getting started with Tech or are the most
weathered expert, we can use your help.

**No contribution is too small and all contributions are valued.**

This guide will help you get started.
**Do not let this guide intimidate you.**
It should be considered a map to help you navigate the process.

You can also get help with contributing on our [Discord server][discord]
Please join us!

[discord]: https://discord.gg/5Tj7DEED

## Code of Conduct

The Initial OSS project adheres to the [Contributor-Convenant][cc].
This describes the _minimum_ behavior expected from all contributors.

For a Basic Outline,Check out [p-society's repo] related to the development 💻 practices to be followed by the org.

[p-society's repo]: https://github.com/p-society/meta
[cc]: https://www.contributor-covenant.org/

## Contributing in Issues

For any issue, there are fundamentally three ways an individual can contribute:

1. By opening the issue for discussion: For instance, if you believe that you
   have discovered a bug in projects under Initial OSS, creating a new issue in the respective repository's issue section.

2. By helping to triage the issue: This can be done by providing supporting
   details (a test case that demonstrates a bug), providing suggestions on how
   to address the issue, or ensuring that the issue is tagged correctly.

3. By helping to resolve the issue: Typically this is done either in the form of
   demonstrating that the issue reported is not a problem after all, or more
   often, by opening a Pull Request that changes some bit of something in
   the project.

**Anybody can participate in any stage of contribution**.
We urge you to participate in the discussion around bugs and participate in
reviewing PRs.

### Asking for General Help

If you have reviewed existing documentation and still have questions or are
having problems, you can asking for help at [p-society's discord server].

In exchange for receiving help, we ask that you contribute back a documentation
PR that helps others avoid the problems that you encountered.

[p-society's discord server]: https://discord.gg/5Tj7DEED

### Submitting a Bug Report

When opening a new issue in the Initial OSS issue tracker, you will be presented
with a basic template that should be filled in.
If you believe that you have uncovered a bug, please fill out this form,
following the template to the best of your ability.
Do not worry if you cannot answer every detail, just fill in what you can.

The two most important pieces of information we need in order to properly
evaluate the report is a description of the behavior you are seeing and a simple
test case we can use to recreate the problem on our own.
If we cannot recreate the issue, it becomes impossible for us to fix.

See [How to create a Minimal, Complete, and Verifiable example][mcve].

[mcve]: https://stackoverflow.com/help/mcve

### Triaging a Bug Report

Once an issue has been opened, it is not uncommon for there to be discussion
around it.
Some contributors may have differing opinions about the issue, including whether
the behavior being seen is a bug or a feature.
This discussion is part of the process and should be kept focused, helpful, and
professional.

Short, clipped responses — that provide neither additional context nor
supporting detail — are not helpful or professional.
To many, such responses are simply annoying and unfriendly.

Contributors are encouraged to help one another make forward progress as much as
possible, empowering one another to solve issues collaboratively.
If you choose to comment on an issue that you feel either is not a problem that
needs to be fixed, or if you encounter information in an issue that you feel is
incorrect, explain why you feel that way with additional supporting context, and
be willing to be convinced that you may be wrong.
By doing so, we can often reach the correct outcome much faster.

### Resolving a Bug Report

In the majority of cases, issues are resolved by opening a Pull Request.
The process for opening and reviewing a Pull Request is similar to that of
opening and triaging issues, but carries with it a necessary review and approval
workflow that ensures that the proposed changes meet the minimal quality and
functional guidelines of the Initial OSS project.

## Pull Requests

Pull Requests are the way concrete changes are made to the code, documentation,
and dependencies in the Initial OSS repository.

Even tiny pull requests (e.g., one character pull request fixing a typo in API
documentation) are greatly appreciated.
Before making a large change, it is usually a good idea to first open an issue
describing the change to solicit feedback and guidance.
This will increase the likelihood of the PR getting merged.

### Commits

It is a recommended best practice to keep your changes as logically grouped as
possible within individual commits.
There is no limit to the number of commits any single Pull Request may have, and
many contributors find it easier to review changes that are split across
multiple commits.

Please adhere to the general guideline that you should never force push to a
publicly shared branch.
Once you have opened your pull request, you should consider your branch publicly shared.
Instead of force pushing you can just add incremental commits;
this is generally easier on your reviewers.
If you need to pick up changes from main, you can merge main into your branch.

A reviewer might ask you to rebase a long-running pull request
in which case force pushing is okay for that request.

Note that squashing at the end of the review process should also not be done,
that can be done when the pull request is integrated via GitHub.

## Reviewing Pull Requests

**Any Initial OSS community member is welcome to review any pull request**.

All Initial OSS contributors who choose to review and provide feedback on Pull
Requests have a responsibility to both the project and the individual making the
contribution.
Reviews and feedback must be helpful, insightful, and geared towards improving
the contribution as opposed to simply blocking it.
If there are reasons why you feel the PR should not land, explain what those are.
Do not expect to be able to block a Pull Request from advancing simply because
you say "No" without giving an explanation.
Be open to having your mind changed.
Be open to working with the contributor to make the Pull Request better.

Reviews that are dismissive or disrespectful of the contributor or any other
reviewers are strictly counter to the Code of Conduct.

When reviewing a Pull Request, the primary goals are for the codebase to improve
and for the person submitting the request to succeed.
**Even if a Pull Request does not land, the submitters should come away from the
experience feeling like their effort was not wasted or unappreciated**.
Every Pull Request from a new contributor is an opportunity to grow the
community.

### Review a bit at a time

Do not overwhelm new contributors.

It is tempting to micro-optimize and make everything about relative performance,
perfect grammar, or exact style matches.
Do not succumb to that temptation.

Focus first on the most significant aspects of the change:

1. Does this change make sense for Initial OSS?
2. Does this change make Initial OSS better, even if only incrementally?
3. Are there clear bugs or larger scale issues that need attending to?
4. Is the commit message readable and correct?
   If it contains a breaking change is it clear enough?

Note that only **incremental** improvement is needed to land a PR.
This means that the PR does not need to be perfect, only better than the status
quo.
Follow up PRs may be opened to continue iterating.

When changes are necessary, _request_ them, do not _demand_ them, and **do not
assume that the submitter already knows how to add a test or run a benchmark**.

Specific performance optimization techniques, coding styles and conventions
change over time.
The first impression you give to a new contributor never does.

Nits (requests for small changes that are not essential) are fine, but try to
avoid stalling the Pull Request.
Most nits can typically be fixed by the Initial OSS collaborator landing the
Pull Request but they can also be an opportunity for the contributor to learn a
bit more about the project.

It is always good to clearly indicate nits when you comment: e.g.
`Nit: change foo() to bar(). But this is not blocking.`

If your comments were addressed but were not folded automatically after new
commits or if they proved to be mistaken, please, [hide them][hiding-a-comment]
with the appropriate reason to keep the conversation flow concise and relevant.

### Be aware of the person behind the code

Be aware that _how_ you communicate requests and reviews in your feedback can
have a significant impact on the success of the Pull Request.
Yes, we may land a particular change that makes repositories under Initial OSS better, but the
individual might just not want to have anything to do with Initial OSS ever
again.
The goal is not just having good code.

_Adapted from the [Juspay/Hyperswitch Contributing.md][Juspay/Hyperswitch Contributing.md]._

[Juspay/Hyperswitch Contributing.md]: https://github.com/juspay/hyperswitch/blob/main/docs/CONTRIBUTING.md
