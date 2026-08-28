# Lumina Theme Framework for OJS

**A modern, modular theme framework for Open Journal Systems (OJS).**

Lumina is designed to give academic journals and publishing platforms a
modern, responsive, and configurable presentation while remaining
integrated with the standard OJS publishing workflow.

It provides multiple visual experiences for individual journals and, in
the Pro edition, a dedicated publisher portal experience for
multi-journal OJS installations.

------------------------------------------------------------------------

## Overview

Lumina Theme Framework extends the presentation layer of Open Journal
Systems without replacing the core OJS publishing workflow.

The framework is designed around several principles:

-   Modern academic publishing interface
-   Multiple visual experiences from a shared framework
-   Responsive layouts for desktop, tablet, and mobile
-   Configuration through standard OJS administration
-   Semantic palette and design-token architecture
-   Modular components
-   Accessibility-conscious interaction patterns
-   Compatibility with OJS journal data and workflows
-   Clean separation between journal experiences and publisher portal
    presentation

### Current Compatibility

  Lumina    OJS
  --------- -------------
  2.0.0.0   OJS 3.5.0.3

Additional OJS versions may be evaluated and documented separately as
compatibility testing progresses.

------------------------------------------------------------------------

## Experiences

Lumina provides several distinct visual experiences built on the same
theme framework.

### Zenith

**Available in Free and Pro**

Zenith is a clean editorial experience designed for academic journals
that want a modern publication-oriented interface while keeping journal
content at the center of the design.

It supports journal content such as:

-   Current issue
-   Published articles
-   Announcements
-   Journal information
-   Editorial content
-   Search and archives
-   Submission information
-   Configurable footer content
-   Journal branding and navigation

#### Preview

*Zenith screenshots will be added as part of the public release
presentation.*

### Vanguard

**Available in Pro**

Vanguard provides a more distinctive and contemporary visual direction
for journals that want stronger branding and a different presentation
from the editorial character of Zenith.

It uses the same Lumina framework and OJS content while providing its
own layout composition and visual identity.

#### Preview

*Vanguard screenshots will be added as part of the public release
presentation.*

### Pinnacle

**Available in Pro**

Pinnacle is an alternative premium journal experience with its own
layout composition and presentation style.

It is intended for journals that want a visually differentiated
interface while retaining the same underlying OJS publishing workflow
and Lumina configuration architecture.

#### Preview

*Pinnacle screenshots will be added as part of the public release
presentation.*

### IndexSite Publisher Portal

**Available in Pro**

IndexSite is Lumina's publisher-level experience for multi-journal OJS
installations.

Instead of representing a single journal, IndexSite provides a portal
for presenting and discovering journals hosted within an OJS
installation.

Depending on the available OJS data and configuration, the portal can
present journal discovery, publishing information, platform statistics,
navigation, and other publisher-level content.

#### Preview

*IndexSite screenshots will be added as part of the public release
presentation.*

------------------------------------------------------------------------

## Free and Pro Editions

Lumina is distributed in Free and Pro editions.

  Feature                       Free   Pro
  ---------------------------- ------ -----
  Zenith                         ✓      ✓
  Vanguard                      ---     ✓
  Pinnacle                      ---     ✓
  IndexSite Publisher Portal    ---     ✓
  Responsive Layout              ✓      ✓
  Palette System                 ✓      ✓
  OJS Theme Configuration        ✓      ✓
  Journal Branding               ✓      ✓
  Lumina Component Framework     ✓      ✓
  Pro Experience Package        ---     ✓

The Free distribution contains the functionality intended for the Free
edition.

The Pro distribution additionally contains the Pro experiences and
associated components.

Commercial entitlement records may accompany officially supplied Pro
distributions for customer, release, and support identification. They
are not presented here as a mechanism for overriding the software
freedoms applicable to conveyed GPL-covered code.

------------------------------------------------------------------------

## Theme Configuration

Lumina integrates with the OJS theme configuration system.

Configuration is intended to be performed through the OJS administration
interface rather than by requiring journal administrators to edit PHP or
CSS files for normal theme operation.

Configuration areas may include:

-   Active Lumina experience
-   Color palette
-   Journal branding
-   Hero presentation
-   Navigation presentation
-   Homepage sections
-   Footer configuration
-   Contact information
-   Social links
-   Attribution
-   Other experience-specific presentation options

Available settings can vary by edition, experience, and Lumina version.

------------------------------------------------------------------------

## Palette System

Lumina uses a semantic token-based palette architecture.

The currently provided palette families are:

-   Blue
-   Emerald
-   Purple
-   Rose
-   Amber
-   Slate

Experiences consume shared semantic design tokens instead of depending
on journal-specific hardcoded colors.

This allows the same experience to adapt to different journal identities
while preserving the intended visual hierarchy of the framework.

------------------------------------------------------------------------

## Responsive Design

Lumina is designed for use across desktop, tablet, and mobile displays.

Development and visual verification include representative viewport
sizes such as:

    Viewport Typical Use
  ---------- ------------------------
       320px Narrow mobile
       390px Mobile
       768px Tablet
      1024px Laptop / small desktop
     1440px+ Desktop

Responsive behavior may differ between experiences where their layout
composition requires it.

------------------------------------------------------------------------

## Accessibility

Accessibility is considered throughout Lumina's component and
interaction design.

The framework uses techniques including:

-   Semantic HTML structure
-   Keyboard-accessible interactive controls
-   Visible focus states
-   Appropriate ARIA attributes where required
-   Responsive navigation
-   Meaningful link and control states
-   Contrast-aware use of the Lumina palette system

Accessibility is an ongoing engineering and verification concern.
Specific compliance claims should be evaluated against the deployed
journal content, selected palette, configuration, and OJS environment.

------------------------------------------------------------------------

## Installation

Lumina is distributed as an installable OJS theme plugin package.

A typical installation consists of:

1.  Obtain the appropriate Lumina distribution.
2.  Verify the release checksum when one is provided.
3.  Install the theme through the supported OJS plugin installation
    workflow.
4.  Enable Lumina for the intended journal or site context.
5.  Select the desired Lumina experience.
6.  Configure the available theme options through OJS administration.
7.  Review the journal on desktop and mobile before production use.

Detailed installation instructions are provided with official release
packages.

------------------------------------------------------------------------

## Release Integrity

Official Lumina release artifacts may be accompanied by SHA-256
checksums.

For example, on Windows PowerShell:

``` powershell
Get-FileHash .\lumina-pro-2.0.0.0.zip -Algorithm SHA256
```

On Linux:

``` bash
sha256sum lumina-pro-2.0.0.0.zip
```

The calculated value should be compared with the checksum published for
the specific release artifact from the official Lumina distribution
source.

A checksum verifies that the artifact being checked matches the artifact
represented by that checksum. Users should obtain release artifacts and
their authoritative verification information from trusted Lumina
distribution channels.

------------------------------------------------------------------------

## Documentation

Official Lumina distributions may include customer-facing documentation
such as:

-   Installation Guide
-   User Guide
-   Upgrade Guide
-   Delivery / Release Information
-   Third-Party Notices

Internal development, release-engineering, security-operation, and owner
documentation are maintained separately and are not part of customer
release packages.

------------------------------------------------------------------------

## Third-Party Components

Lumina uses a limited set of third-party assets and components where
appropriate.

The authoritative attribution and licensing information for components
actually included in a release is provided in:

`THIRD_PARTY_NOTICES.md`

The contents of that document should be treated as the release-specific
source of truth for bundled third-party materials.

------------------------------------------------------------------------

## Licensing

Lumina is developed for Open Journal Systems and its conveyed PHP/plugin
code is distributed consistently with the applicable GNU General Public
License requirements.

### Free Edition

The Free edition provides the Lumina functionality included in the Free
distribution.

Recipients should refer to the licensing information accompanying the
distributed package for the applicable terms.

### Pro Edition

The Pro edition contains additional Lumina experiences and components
that are not physically included in the Free distribution.

Commercial terms may govern how an official Pro distribution is obtained
and the associated customer relationship, support, maintenance, and
release entitlement.

Those commercial arrangements do not remove the software freedoms that
apply to GPL-covered code conveyed to a recipient.

For authoritative licensing information, always refer to the
documentation accompanying the specific Lumina distribution.

------------------------------------------------------------------------

## Support and Maintenance

Support and maintenance arrangements depend on the edition and
commercial arrangement under which Lumina is provided.

For Pro customers, reasonable product support and maintenance may be
provided according to the applicable commercial terms.

Genuine Lumina product defects may be addressed as product maintenance.
Work involving substantial customization, integration, migration, or
customer-specific development may require a separately agreed scope.

Public contact and support channels will be documented here as they
become available.

------------------------------------------------------------------------

## Screenshots

Official screenshots are being prepared for the public project
presentation.

Planned previews include:

### Zenith

*Desktop and mobile preview*

### Vanguard

*Desktop and mobile preview*

### Pinnacle

*Desktop and mobile preview*

### IndexSite

*Publisher portal preview*

Screenshots will represent actual Lumina runtime interfaces rather than
conceptual mockups.

------------------------------------------------------------------------

## Security

Security issues should not be disclosed through a public issue if doing
so would expose a vulnerability before it can be reviewed.

A dedicated private security contact or reporting channel will be
published when available.

------------------------------------------------------------------------

## Project Status

**Current Lumina Version:** `2.0.0.0`

**Current verified development target:** `OJS 3.5.0.3`

Lumina 2 is currently undergoing final release and real-environment
verification.

Public release information, screenshots, checksums, and distribution
details will be updated as release certification is completed.

------------------------------------------------------------------------

## About This Repository

This repository is the public information and documentation home for the
Lumina Theme Framework.

It is intended for:

-   Product information
-   Public documentation
-   Experience previews
-   Release information
-   Compatibility information
-   Public announcements about Lumina

This repository is not intended to expose private development
infrastructure, owner release tooling, customer-specific information,
signing material, or internal operational documentation.

------------------------------------------------------------------------

## Acknowledgements

Lumina is built for the Open Journal Systems ecosystem.

Open Journal Systems is developed by the Public Knowledge Project (PKP).

------------------------------------------------------------------------

**Lumina Theme Framework**\
*Modern experiences for academic publishing.*
