# Release Notes Guidelines

## Developer Studio Release Notes

Developer Studio arranges release notes into three section: 

  * what's new
  * enhancements
  * fixed.

**What's new** section is telling the user about the new feature(s) in terms of performance or functionality, the thought behind it, and the intended use.

**Enhancement** describes any change in Developer Studio that improves performance or capabilities of the existing functionality.

**Fixed** section lists uninteded application behaviour that Developer Studio engineers have pattched or found a work-arround to correct.


The eveloper writing release notes needs to describe the change in terms of application behaviour as it would appear to the use avoiding confusing implementation details.


## Tenant Release Notes

It is a Developer Studio **requirement** all tenants to have release notes to document onboarding and ongoing changes to the content.

  * github structure for release notes
  * location of release notes in document tree
  * release notes sections


**GitHub structure** for release notes is *tenant-name/docs/release-notes/year/month.md*. Developer Studio began mandating the specific location in order to make it uniform across all tenants and to index release notes in the future and 

    developer-studio-support/docs/release-notes/2022/april.md
  

**The left navigation** structure for tenant documents is defined by *tenant-name/config/document-explorer-definition.yaml* file.

    developer-studio-support/config/document-explorer-definition.yaml


The requirement is to have Release notes section at the top tier of the document tree

    - sections:
      - title: Getting Started
        link: docs/getting-started.md

    - sections:
      - title: Release notes
        sections:
        - title: May 2022
          link: docs/release-notes/2022/may.md

**Release notes sections** are described in [release notes template](./release-notes-template.md).

When creating release notes please include the following information:

  * Title of the document, the header (H1), is always *Release Notes*
  * Publication date, in format: Month date, year
  * Version of openAPI document is in header H3
  * Possible sections, in H2:
    - What's new
    - Enhancements
    - Fixed
    - Know Issues
    - Deprecated 

It is a requirement to have published release notes in order for a Tenant to be promoted to higher environments: 

  * QA
  * Stage
  * Production


Any changes to the content after the initial release should go into release notes with updates to doc tree.
