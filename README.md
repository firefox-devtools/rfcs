# DevTools RFCs

Most changes to our tools, including bug fixes and documentation improvements, can be implemented and reviewed via the normal GitHub pull request workflow.

Some changes though are "substantial", and we ask that these be put through a bit of a design process and produce a consensus among the [DevTools core team].

The "RFC" (request for comments) process is intended to provide a consistent and controlled path for new features to enter the framework.

[Active RFC List]

## When you need to follow this process

You need to follow this process if you intend to make "substantial" changes to DevTools or its documentation. What constitutes a "substantial" change is evolving based on community norms, but may include the following.

   - The removal of features that already shipped as part of the release
     channel.
   - The introduction of new idiomatic usage or conventions, even if they
     do not include code changes (React, Redux, etc).

Some changes do not require an RFC:

   - Rephrasing, reorganizing or refactoring
   - Changing the default set of panels
   - Additions that strictly improve objective, numerical quality
criteria (speedup, better browser support)

If you submit a pull request to implement a substantial change without going through the RFC process, it may be closed with a polite request to submit an RFC first.

## Gathering feedback before submitting

It's often helpful to get feedback on your concept before diving into the level of API design detail required for an RFC. **You may open an issue on this repo to start a high-level discussion**, with the goal of eventually formulating an RFC pull request with the specific implementation design.

[Active Feedback List]

## What the process is

In short, to make a major change to DevTools, one must first get the RFC merged into the RFC repo as a markdown file. At that point the RFC is 'active' and may be implemented with the goal of eventual inclusion into all of DevTools.

* Fork the RFC repo http://github.com/devtools-html/rfcs
* Copy `0000-template.md` to `text/0000-my-feature.md` (where 'my-feature' is descriptive. don't assign an RFC number yet).
* Fill in the RFC. Put care into the details: **RFCs that do not present convincing motivation, demonstrate understanding of the impact of the design, or are disingenuous about the drawbacks or alternatives tend to be poorly-received**.
* Submit a pull request. As a pull request the RFC will receive design feedback from the larger community, and the author should be prepared to revise it in response.
* Build consensus and integrate feedback. RFCs that have broad support are much more likely to make progress than those that don't receive any comments.
* Eventually, the [DevTools core team] will decide whether the RFC is a candidate for inclusion in DevTools.
* RFCs that are candidates for inclusion in DevTools will enter a "final comment period" lasting 7 days. The beginning of this period will be signaled with a
comment and tag on the RFC's pull request. Furthermore, an email will be sent out the to [DevTools Developer List][dev-developer-tools] to indicate to the broader community that this has entered the final phase.
* An RFC can be modified based upon feedback from the [core team] and community. Significant modifications may trigger a new final comment period.
* An RFC may be rejected by the [DevTools core team] after public discussion has settled and comments have been made summarizing the rationale for rejection. A member of the [DevTools core team] should then close the RFC's associated pull request.
* An RFC may be accepted at the close of its final comment period. A [DevTools core team] member will merge the RFC's associated pull request, at which point the RFC will
become 'active'.

## The RFC life-cycle

Once an RFC becomes active then authors may implement it and submit the feature as a pull request to the DevTools repos. Becoming 'active' is not a rubber stamp, and in particular still does not mean the change will ultimately be merged; it does mean that the core team has agreed to it in principle and are amenable to the direction.

Furthermore, the fact that a given RFC has been accepted and is 'active' implies nothing about what priority is assigned to its implementation, nor whether anybody is currently working on it.

Modifications to active RFC's can be done in followup PR's. We strive to write each RFC in a manner that it will reflect the final design of the change; but the nature of the process means that we cannot expect every merged RFC to actually reflect what the end result will be at the time of the next major release; therefore we try to keep each RFC
document somewhat in sync with the change as planned, tracking such changes via followup pull requests to the document.

## Implementing an RFC

The author of an RFC is not obligated to implement it. Of course, the RFC author (like any other developer) is welcome to post an implementation for review after the RFC has been accepted.

If you are interested in working on the implementation for an 'active' RFC, but cannot determine if someone else is already working on it, feel free to ask (e.g. by leaving a comment on the associated issue).

## Reviewing RFC's

Each week the [DevTools core team] will attempt to review some set of open RFC pull requests.

We try to make sure that any RFC that we accept is accepted at the Tuesday team meeting, and reported in [DevTools weekly meeting notes][devtools-weekly-meetings]. Every accepted feature should have a core team champion, who will represent the feature and its progress.

**DevTools' RFC process owes its inspiration to the [Ember RFC] and [Rust RFC] processes**

[Rust RFC]: https://github.com/rust-lang/rfcs
[Ember RFC]: https://github.com/emberjs/rfcs
[DevTools core team]: https://github.com/orgs/devtools-html/teams/devtools-core
[Active RFC List]: https://github.com/devtools-html/rfcs/pulls
[Active Feedback List]: https://github.com/devtools-html/rfcs/issues
[dev-developer-tools]: https://groups.google.com/forum/#!forum/mozilla.dev.developer-tools
[devtools-weekly-meetings]: https://docs.google.com/a/mozilla.com/document/d/1pUx9xq6L7bonSrDpyUNTQkQxTxAsULLu4kkHZLMEq6w/edit?usp=drive_web
