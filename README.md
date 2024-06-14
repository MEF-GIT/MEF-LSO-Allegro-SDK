# MEF-LSO-Allegro-SDK Haley Release

## Download Link

Download the entire repository by clicking
[here](https://github.com/MEF-GIT/MEF-LSO-Allegro-SDK/releases/download/haley/MEF-LSO-Allegro-SDK-haley.zip)

## Overview

This repository contains the release of the Allegro SDK. The SDK includes APIs
for Performance Monitoring, and Streaming Management functions of the
Service Orchestration Functionality (SOF) at the LSO Allegro Interface
Reference Point (IRP) as defined in the MEF LSO Reference Architecture.

Also included are Service schemas and Performance Monitoring definitions.

## High-level release notes

- Updated documents:
  - MEF 128.1 - LSO API Security Profile

## Scope

It includes API definitions for the following functional areas:

- Performance Monitoring
- Streaming Management

The MEF LSO Allegro SDK is released under the Apache 2.0 license.

More information about the LSO Allegro API reference point and its roadmap can
be found here:

https://wiki.mef.net/display/CESG/LSO+Allegro

## Maturity Level

The API files contained in this SDK are evolving and subject to change. They
are based on documents that are either work in progress or draft standards that
have not yet completed the review cycles and approvals necessary to achieve the
status as a MEF standard. MEF is making these publicly available at this time
to invite wider industry review.

The maturity per functionality is presented as follows:

(\*) is used to mark an item that changes its maturity compared to the previous
release.

SOAM:

- MEF 133 - Allegro, Interlude and Legato Fault Management and Performance
  Monitoring BR&UC - **Published Standard**
- MEF W133.1 - Allegro, Interlude and Legato Fault Management and Performance
  Monitoring BR&UC - **early draft version, CfC#1**
- MEF 136 - Service Function Testing Business Requirements and Use Cases -
  **Published Standard**
- MEF W143 - Performance Monitoring API and Developer Guide - **work in
  progress - CfC#2**
- MEF W147 - Streaming Management API and Developer Guide - **work in
  progress - CfC#2**
- Performance Monitoring reports and statistics definitions for Carrier
  Ethernet and IP - **early draft version, schemas only**

- Security:
  - *MEF 128.1 - **Published Standard**

## Contents

This SDK contains the following items:

- `COPYRIGHT` - Copyright 2024 MEF Forum
- `LICENSE` - Contains a copy of the Apache 2.0 license
- `README` - This file
- `serviceApi` - Definitions of the APIs are found in this directory, provided
  as yaml files.
- `serviceSchema` - Contains JSON schema (draft 7) files for service
  specifications.
- `documentation` - documentation including API/Schema developer guides and
  openapi-tools generated API descriptions in markdown format
  - `supportingStandards` - The rest of the documents and standards.
- `generated`
  - `security` - A not normative version of the standard APIs including the
    security profiles as required by MEF 128.1. Provided for evaluation.

## Issues, questions, and Feedback

Issues should be reported with the use of GitHub issues. Questions and feedback
should be asked either at
[Allegro SDK Discussions](https://github.com/MEF-GIT/MEF-LSO-Allegro-SDK/discussions)
or directly to community_manager@mef.net.

**NOTE:** All artifacts included in this repository have line numbers. When
referring to specific content in any of these artifacts, please quote the line
numbers to which you are referring.

## Copyright

© MEF Forum 2024. All Rights Reserved.

## Disclaimer

The information in this publication is freely available for reproduction and
use by any recipient and is believed to be accurate as of its publication date.
Such information is subject to change without notice and MEF Forum (MEF) is not
responsible for any errors. MEF does not assume responsibility to update or
correct any information in this publication. No representation or warranty,
expressed or implied, is made by MEF concerning the completeness, accuracy, or
applicability of any information contained herein and no liability of any kind
shall be assumed by MEF as a result of reliance upon such information.

The information contained herein is intended to be used without modification by
the recipient or user of this document. MEF is not responsible or liable for
any modifications to this document made by any other party.

The receipt or any use of this document or its contents does not in any way
create, by implication or otherwise:

(a) any express or implied license or right to or under any patent, copyright,
trademark or trade secret rights held or claimed by any MEF member which are or
may be associated with the ideas, techniques, concepts or expressions contained
herein; nor

(b) any warranty or representation that any MEF member will announce any
product(s) and/or service(s) related thereto, or if such announcements are
made, that such announced product(s) and/or service(s) embody any or all of the
ideas, technologies, or concepts contained herein; nor

(c) any form of relationship between any MEF member and the recipient or user
of this document.

Implementation or use of specific MEF standards, specifications, or
recommendations will be voluntary, and no Member shall be obliged to implement
them by virtue of participation in MEF Forum. MEF is a non-profit international
organization to enable the development and worldwide adoption of agile, assured
and orchestrated network services. MEF does not, expressly or otherwise,
endorse or promote any specific products or services.
