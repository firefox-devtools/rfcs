# DevTools RFCs

Some changes to DevTools need feedback from the team and community to reach a consensus. In such cases we should use the RFC process to discuss the proposed changes.

We aim for the process to be lightweight and focused on conversations. Therefore opening a DevTools RFC is as easy as opening an issue in this repository.

The [DevTools RFC team][] will be ultimately responsible for accepting or rejecting proposals, but the discussion is open to everybody.

The list of RFCs currently under discussion can be found at [Active RFCs][].

## What kind of changes should be discussed?

We aim to discuss specific and actionable changes, i.e. we aim to answer questions about work you're doing or about to do either on the DevTools codebase or on something that *interacts* with DevTools. For example:

* you're working on a DevTools bug, and you believe the fix involves making a change that affects a number of panels or doing something that is very different from the existing conventions, and you would like feedback on the solution you came up with.
* you are about to make a breaking change on an essential API we interact with, and would like to discuss it and get feedback from us beforehand.

This distinction can be unclear at times, but we will try our best to discuss proposals, taking into account our own time limitations.

## Creating RFCs

* Create an issue detailing what you're seeking feedback on
* Get people's attention. Some options:
    * Send an email to [dev-developer-tools][]
    * Post on [Slack][] or on #devtools at irc.mozilla.org
    * mention relevant peers in the issue
* Gather feedback by discussing in the issue

## Reviewing RFCs

Each week the [DevTools RFC team][] will mention the open RFCs during the DevTools meeting, to bring relevant peers' attention to them (see archives for [devtools-weekly-meetings][]).

The team will send an email a few days prior to the review meeting to [dev-developer-tools][] to announce which RFCs are going to be reviewed, and encourage peers to comment if needed.

## Closing RFCs

After a proposal has been discussed and consensus has been reached, the DevTools core team will label the issue either as `accepted` or `rejected`, and will add a comment summarising the decision.

If the RFC is accepted, the team will also create an item in the appropriate medium (e.g. bugzilla bug, github issue, airtable item) to ensure the decision is adequately documented and the proposal is tracked.

The issue will then be closed, regardless of the accepted status. This ends the involvement of the team with regards to that RFC.

## RFC lifecycle

You can have a look at the following links to get an idea of which RFCs are in each state:
* [Active RFCs][]
* [Accepted RFCs][]
* [Rejected RFCs][]
* [Completed RFCs][]

[DevTools RFC team]: https://github.com/orgs/firefox-devtools/teams/devtools-rfc/members
[Active RFCs]: https://github.com/firefox-devtools/rfcs/issues?q=is%3Aopen+is%3Aissue
[Accepted RFCs]: https://github.com/firefox-devtools/rfcs/issues?q=is%3Aissue+label%3Aaccepted
[Rejected RFCs]: https://github.com/firefox-devtools/rfcs/issues?q=is%3Aissue+label%3Arejected
[Completed RFCs]: https://github.com/firefox-devtools/rfcs/issues?q=is%3Aclosed+is%3Aissue
[dev-developer-tools]: https://lists.mozilla.org/listinfo/dev-developer-tools
[devtools-weekly-meetings]: https://docs.google.com/document/d/1Gio9ypuBXG9YECMay2Fk0rEjrP16AF_ZR4UIJ7fic9g/edit?usp=sharing
[Slack]: https://devtools-html-slack.herokuapp.com/
