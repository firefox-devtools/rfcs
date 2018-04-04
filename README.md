# DevTools RFCs

TEST FOR CIRCLE

Some changes to DevTools need feedback from the team and community to reach a consensus. In such a case you should use this repository to discuss the change proposal.

The DevTools RFC process aims to be lightweight and focused on conversations. Therefore opening a DevTools RFC is as easy as opening an issue in this repository to discuss the proposal.

The [DevTools RFC team][] will be ultimately responsible for accepting or rejecting a change proposal, but the discussion is open to everybody.

The list of RFCs currently under discussion can be found at: [Active RFCs][].

## Creating RFCs

* Create an issue with the "proposal" label
* Get people's attention. Some options:
    * Send an email to [dev-developer-tools][]
    * Post on [Slack][] or on #devtools at irc.mozilla.org
    * mention relevant peers in the issue
* Gather feedback by discussing in the issue

## Reviewing RFCs

Each week the [DevTools RFC team][] will attempt to review some set of open RFC issues. Reviewed RFCs will also be mentioned in the weekly DevTools team meeting (see archives for [devtools-weekly-meetings][]).

The team will send an email a few days prior to the review meeting to [dev-developer-tools][] to announce which RFCs are likely to be reviewed, and encourage peers to comment if needed.

## Closing RFCs

After a proposal has been discussed and consensus has been reached, the DevTools core team will label the issue either as `accepted` or `rejected`, and will add a comment that summarizes the decision.

Accepted RFCs remain open until an item is created to track the implementation of the change. This item can be a bug in Bugzilla, an issue on another GitHub repository, etc…

Once an action has been logged, the accepted RFC is closed and labeled `in-progress`. The DevTools core team will try to regularly check accepted RFCs still marked as `in-progress` to see if they can be unblocked or need to be discussed again.

When the action is implemented, the `in-progress` label is removed and the RFC is considered as completed.

## RFC lifecyle

Checkout the issue lists below to see which RFCs are in each state:
* [Active RFCs][]
* [Rejected RFCs][]
* [Accepted RFCs waiting for action][]
* [Accepted RFCs in-progress][]
* [Completed RFCs][]

[DevTools RFC team]: https://github.com/orgs/devtools-html/teams/devtools-rfc
[Active RFCs]: https://github.com/devtools-html/rfcs/issues?q=is%3Aopen+is%3Aissue+label%3Aproposal
[Rejected RFCs]: https://github.com/devtools-html/rfcs/issues?q=is%3Aclosed+is%3Aissue+label%3Arejected
[Accepted RFCs waiting for action]: https://github.com/devtools-html/rfcs/issues?q=is%3Aopen+is%3Aissue+label%3Aaccepted
[Accepted RFCs in-progress]: https://github.com/devtools-html/rfcs/issues?q=is%3Aclosed+is%3Aissue+label%3Ain-progress
[Completed RFCs]: https://github.com/devtools-html/rfcs/issues?q=is%3Aclosed+is%3Aissue+-label%3Ain-progress+label%3Aaccepted
[dev-developer-tools]: https://lists.mozilla.org/listinfo/dev-developer-tools
[devtools-weekly-meetings]: https://docs.google.com/a/mozilla.com/document/d/1pUx9xq6L7bonSrDpyUNTQkQxTxAsULLu4kkHZLMEq6w/edit?usp=drive_web
[Slack]: https://devtools-html-slack.herokuapp.com/
