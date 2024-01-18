# LFGG1: Managing GoGoPool Improvement Proposals

# Summary

Defines an initial process for proposing, discussing, and finalizing improvements to the GoGoPool Protocol
using GoGoPool Improvement Proposals (LFGGs).

# Motivation

As Multisig Labs, Inc begins to share control over the development and management of the GoGoPool Protocol,
it's become clear we need a community-driven process for making changes to the protocol, network
configuration, and other shared concerns. Fortunately, we are not the first to experience this problem, and
this document draws heavily on the the Improvement Proposal processes of
[Ethereum](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1.md),
[Zcash](https://github.com/zcash/zips/blob/master/zip-0000.rst),
[GoGoPool](https://github.com/helium) and others.

This document aims to outline a process that is transparent and inclusive while remaining as
efficient and pragmatic as possible.

# Stakeholders

We plan to circulate these proposals in
[Discord](https://discord.gg/gogopool). We will also solicit specific
individuals for feedback, from both within the GoGoPool community and other crypto and open-source
projects.

# Detailed Explanation

## Overview

The LFGG process generally starts with an idea for improving the GoGoPool protocol or modifications to
protocol configuration values. 

The LFGG's author is responsible for building support and consensus for their proposal.

There are three major types of proposals:

- _Technical_ – network and protocol upgrades
- _Economic_ – modifications to rewards or incentive structures
- _Meta/Process_ – changes to the LFGG process itself; presumably would also include processes like
  the selection of committee members and the induction of core developers

We propose the creation of several roles to help facilitate this process: _LFGG Editors_, who
administer the LFGG process, and _Review Committees_, who serve as specialists for technical vs.
economic proposals and operate as a first line of feedback.

## Submitting a LFGG

In the earliest phases it's best to vet an idea with the GoGoPool community
[via Discord](https://discord.gg/gogopool). This is a good way to see if there is initial support for
the idea, or if it's been discussed before.

After vetting the idea, please write it up using this markdown-formatted
[LFGG template](https://github.com/multisig-labs/LFGG/blob/master/0000-template.md) and submit it as a pull
request to this repository (`multisig-labs/LFGG`). The current template is geared towards technical
proposals, but can be adapted for economic or meta proposals.

How to submit a pull request:

- Fork this repository (e.g. using the GitHub "Fork" button top-right) and checkout your fork
- Add your file and give it a title but do not allocate a number, e.g. `LFGG-my-proposal.md`
- Commit your changes (`git commit [filename] -m "Description of your changes"`) and push them to
  your fork (`git push origin master`)
- Submit your change as a [pull request](https://github.com/multisig-labs/LFGG/pulls)

Within a reasonable timeframe after you've submitted your PR, a LFGG Editor will review your pull
request.

The PR will be merged it if it adheres to the standards outlined in this document, which formally
opens it up for consideration.

If there are issues, the LFGG editor will provide feedback. The feedback at this stage is intended to
be logistical, rather than on the actual contents of the proposal.

## Discussion and approval process

- When ready, LFGG is scheduled for discussion on a community call.
- Comments should be put on the LFGG's associated GitHub discussion
- Approval is achieved through
  [rough consensus and running code.](https://en.wikipedia.org/wiki/Rough_consensus)
- LFGGs have a status: _Draft, In Discussion, Approved, Deployed, Rejected_
- If a LFGG goes stale and discussion is dormant, it should be closed.
- When rough consensus is achieved, a LFGG is marked `approved`
- When a LFGG has been merged and deployed, it is marked `deployed`.
- LFGG Editors are responsible for keeping `multisig-labs/LFGG` repository groomed and well-organized.

## LFGG Editors

As mentioned above, we'll need people to help organize and facilitate the LFGG process. This is an
administrative role, and Editors are not arbiters of what does or does not get approved.

Editors would be responsible for:

- Reviewing new LFGGs submitted to the GitHub repository
- Flagging issues related to formatting and structure, but not commentary on its substance; that
  should be reserved until after the LFGG's pull request has actually been merged.
- Evaluating community consensus and updating LFGG statuses accordingly

## Review Committees

We expect different stakeholders to be more interested in Technical vs. Economic proposals, and so
we suggest the formation of Review Committees for each of those tracks.

Review Committees would be expected to meet regularly and discuss LFGGs falling into their area, and
in conjunction with LFGG Editors, help keep the improvement process moving.

The committee is an informal group and anyone can join one of the calls and make their voice heard.

