-   Start Date: 2017-08-23
-   RFC PR: (leave this empty)
-   Related Issue: (leave this empty)

## Summary

This change is about removing the DevTools hotreload feature.

### Motivation

This feature was introduced 18 months ago, and adds some hotreloading for DevTools development. It works with CSS files and React components. To enable it, one has to set the `devtools.loader.hotreload` preference to true in about:config.

This feature is not tested or maintained.
The only documentation is a mention at http://docs.firefox-dev.tools/frontend/react-tips.html
On the latest mozilla-central enabling it can easily break the debugger & netmonitor.

## Proposal

Remove the feature and all the related code.

### Unresolved questions

We don't have actual data to tell us if users are relying on the feature. The goal of this
RFC is also to get feedback from potential users.
