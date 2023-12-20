---
zcip: 1
title: ZCred Improvement Proposals (ZCIP)
author: Pavel Deshevov (@pavelgoodpal), Sergey Ukustov (@ukstv)
status: Living
type: Meta
created: 2023-12-20
updated: 2023-12-20
---

## Abstract

ZCred Improvement Proposals (ZCIPs) serve as standards aimed at 
enhancing the ZCred ecosystem, encompassing core protocol
specifications. These proposals enable broad participation,
allowing anyone to contribute to the development of the ZCred
ecosystem and the standards associated with it.

## Motivation

Here are some of the reasons why ZCred needs a ZCIP process:

- To define an explicit governance process for ZCred ecosystem upgrades
- To make it easy for community members to contribute to the development of the protocol
- To provide a way to discover implementation standards accepted by the community
- To provide a vehicle for community discussion around important topics


## Specification

### ZCIP Formats and Templates

ZCIPs should be written in markdown format according to 
[template](../zcip-template.md). Image files should be included in
a subdirectory of the `assets` folder for that ZCIP as follows:
`assets/zcip-N` (where **N** is to be replaced with the ZCIP number). 
When linking to an image in the ZCIP, use relative links such as `../assets/caip-1/image.png`.

### ZCIP Terms

#### Types

There are three types of ZCIP:

- `Standard` - describes any change or specification that affects ZCred protocol.

- `Meta` describes a process surrounding ZCred or proposes a change to (or an event in) a process.

- `Informational` describes an ZCred design issue, or provides general guidelines or information to the ZCred community, but does not propose a new feature. 

#### Statuses

- `Idea` - An idea that is pre-draft. This is not tracked within the ZCIP Repository.

- `Draft` -  The first formally tracked stage of an ZCIP in development. An ZCIP is merged by an ZCIP Editor into the ZCIP repository when properly formatted.

- `Review` - An ZCIP Author marks an ZCIP as ready for and requesting Peer Review.

- `Last Call` - This is the final review window for an ZCIP before moving to Final. An ZCIP editor will assign Last Call status and set a review end date (`last-call-deadline`), typically 14 days later.

- `Final` - This ZCIP represents the final standard. A Final ZCIP exists in a state of finality and should only be updated to correct errata and add non-normative clarifications.
  - A PR moving an ZCIP from `Last Call` to `Final` SHOULD contain no changes other than the status update. Any content or editorial proposed change SHOULD be separate from this status-updating PR and committed prior to it.

- `Stagnant` - Any ZCIP in Draft or Review or Last Call if inactive for a period of 6 months or greater is moved to Stagnant. An ZCIP may be resurrected from this state by Authors or ZCIP Editors through moving it back to Draft or it's earlier status. If not resurrected, a proposal may stay forever in this status.

- `Withdrawn` - The ZCIP Author(s) have withdrawn the proposed ZCIP. This state has finality and can no longer be resurrected using this ZCIP number. If the idea is pursued at later date it is considered a new proposal.

- `Living` -  A special status for ZCIPs that are designed to be continually updated and not reach a state of finality. This includes most notably ZCIP-1

### ZCIP Process

The following is the standardization process for all ZCIPs in all tracks:

![ZCIP Status Diagram](../assets/zcip-1/ZCIP-process-update.jpg)

## Copyright

Copyright and related rights waived via [CC0](../assets/LICENSE-CC0.md).
