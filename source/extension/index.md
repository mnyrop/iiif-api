---
title: Registry of Extensions
layout: spec
tags: [annex, service, services, specifications]
cssversion: 2
editors:
  - name: Michael Appleby
    orchid: https://orcid.org/0000-0002-1266-298X
    institution: Yale University
  - name: Tom Crane
    orchid: https://orcid.org/0000-0003-1881-243X
    institution: Digirati
  - name: Robert Sanderson
    orchid: https://orcid.org/0000-0003-4441-6852
    institution: J. Paul Getty Trust
  - name: Jon Stroop
    orchid: https://orcid.org/0000-0002-0367-1243
    institution: Princeton University Library
  - name: Simeon Warner
    orchid: https://orcid.org/0000-0002-7970-7855
    institution: Cornell University
hero:
  image: ''
---

## Status of this Document
{:.no_toc}

This document is not subject to [semantic versioning][notes-versioning].
Changes will be tracked within the document.

**Editors:**

{% include api/editors.md editors=page.editors %}

{% include copyright.md %}

## Abstract
{:.no_toc}
This is one of a number of [IIIF registries][registry]. It lists a set of extension properties and classes that have been identified as useful for implementations, across the APIs.  They may be defined by the IIIF community, or outside of it.

Please send feedback to [iiif-discuss@googlegroups.com][iiif-discuss]


## 1. Introduction

This is one of a number of [IIIF registries][registry]. It lists a set of extension properties and classes that have been identified as useful for implementations, across the APIs.  They may be defined by the IIIF community, or outside of it.

### 1.1. Disclaimer

The inclusion of entries in this document that are outside of the IIIF domain _MUST NOT_ be interpreted as endorsement, support, or approval from the editors, the IIIF community or any individual. This annex is provided as a registry to advertise the existence of these extensions and attempt to ensure some consistency between implementations for common but not universal requirements.

### 1.2. Inclusion Process

The process for having a new entry added to this registry is [described here][registry-process].

## 2. Requirements for Inclusion

## 3. Registry

This table summarizes the known extensions available, for use with the [Presentation API][prezi-api].

| Extension                       |
| ------------------------------ |
| [Text Granularity Extension][text-granularity] |
{: .api-table}


## Appendices

### A. Acknowledgements

Thanks to the members of the [IIIF community][iiif-community] for their continuous engagement, innovative ideas and feedback.

### B. Change Log

| Date       | Description                                        |
| ---------- | -------------------------------------------------- |
| 2020-05-20 | Adding the Text Granularity Extension |

{% include acronyms.md %}
{% include links.md %}
