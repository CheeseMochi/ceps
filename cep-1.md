<table>
<tr><td> Title </td><td> CEP Purpose and Guidelines </td>
<tr><td> Status </td><td> Proposed </td></tr>
<tr><td> Author(s) </td><td> Jannis Leidel &lt;jleidel@anaconda.com&gt;</td></tr>
<tr><td> Created </td><td> Jun 29, 2021</td></tr>
<tr><td> Updated </td><td> Jun 29, 2021</td></tr>
<tr><td> Discussion </td><td> NA </td></tr>
<tr><td> Implementation </td><td> NA </td></tr>
</table>

# Abstract

CEPs are the manner in which the Conda project community suggests changes
to the software project, and outlines how the suggested changes are reviewed.
This document provides details on what a CEP is, how to author one,
and the workflow used to review these proposals.

# What is a CEP

CEP stands for Conda Enhancement Proposal. A CEP is a document which
outlines a suggested change to how the project works. These changes may be
technical in manner or may deal with social aspects of the project including
governance and conduct. The CEP should provide a concise description of the
proposed change as well as the rationale for the change.

CEPs are intended to be the primary mechanism for proposing major changes to
how Conda works and for documenting both the changes themselves and the
decision making process.

CEPs are maintained as text files using Markdown for formatting in the
[conda/ceps](https://github.com/conda/ceps) repository. Their revision
history is a historic record of the proposed change.

# Workflow

The CEP process begins with an idea for a change in how the Conda project
works. Theses change can be technical or address the social aspects of the
project. Small changes often do not need a CEP and can be discussed on the
[conda issue tracker](https://github.com/conda/conda/issues).

More involved or controversial changes should be submitted as CEPs.
When it is unclear if a change requires a CEP, ask in a ticket in the
Conda issue tracker and the Conda core team should be able to provide
guidance. The Conda core team may solicit CEPs on topics of
concern to the community. CEPs should focus on a single issue; broad changes
should be split into multiple well-focused CEPs.

Each CEP must have a champion or champions -- someone who will write the
CEP in the format described below, submit the CEP as a pull request,
follow the discussion on the pull request, and answer questions. Before
beginning to write a proposal, it is best to ascertain if the idea is CEP-able.
A discussion on the
[conda-forge mailing list](https://groups.google.com/forum/#!forum/conda-forge),
or as part of a Conda community meeting is the best way to go about this.

Once the champion has asked the Conda community as to whether an idea
has any chance of acceptance, a draft CEP should be written following the
template in [CEP 0](cep-0.md) and described below.

While working on the CEP prior to submission please set its Status to Draft.

## Submission

Once complete, this draft should be submitted as a pull request to the
[conda/ceps](https://github.com/conda/ceps) repository with the Status
changed to Proposed. At this point, members of the Conda community will
review the submission.

## Review

CEP review will begin once a pull request has been made. All members of the
Conda community are welcome and encouraged to participate in the review
of CEPs in a civil and respectful manner. The CEP champion(s) should be
prepared to answer questions on the proposal and make updates to the
proposal as recommended by the community.

## Resolution

All CEPs will be resolved as either *Rejected*, *Accepted* or *Deferred*
depending on the consensus of the community. Once the community has reached a
consensus, a Conda maintainer will update the Status of proposal, add a
link to the discussion in the table and, regardless of the resolution, merge
the pull request with these updates.

## CEP Maintenance

For *Rejected* CEPs, no modifications are made after the pull request is merged.
*Accepted* CEPs should be updated with a link to the pull request(s) of the
implementation and the status changed to *Implemented* when the proposed
changes have been implemented. *Deferred* CEPs can be re-submitted in a new
pull request if the circumstances that justified deferring instead of
accepting or rejecting have changed.

# CEP Content

All CEPs should begin with a top level table with the following information:

<table>
<tr><td> Title </td><td> A short title of the proposal </td>
<tr><td> Status </td><td> Draft | Proposed | Accepted | Rejected | Deferred | Implemented </td></tr>
<tr><td> Author(s) </td><td> Full Name &lt;full.name@gmail.com&gt;</td></tr>
<tr><td> Created </td><td> Aug 30, 2016</td></tr>
<tr><td> Updated </td><td> Aug 30, 2016</td></tr>
<tr><td> Discussion </td><td> link to the issue where the CEP is being discussed, NA before submission </td></tr>
<tr><td> Implementation </td><td> link to the PR for the implementation, NA if not available </td></tr>
</table>

This table should be followed by a **Abstract** section and then
additional sections as needed by the proposal. Some section that may be
included if appropriate for the proposal include.

    * Specification -- The technical details of the proposed change.
    * Motivation -- Why the proposed change is needed.
    * Rationale -- Why particular decisions were made in the proposal.
    * Backwards Compatibility -- Will the proposed change break existing
      packages or workflows.
    * Alternatives -- Any alternatives considered during the design.
    * Sample Implementation -- Links to prototype or a sample implementation of
      the proposed change.
    * FAQ -- Frequently asked questions (and answers to them).
    * Resolution -- A short summary of the decision made by the community.
    * Reference -- Any references used in the design of the CEP.

A final **Copyright** section is also required.

## Pronunciation

CEP is to be pronounced `/sep/`.

If you have doubts about how to actually pronounce it, here you have a reference (we accept UK and US pronunciations): https://dictionary.cambridge.org/dictionary/english/cep

## References

Much of this document was adapted from [CFEP 1 - Purpose and Guidelines](https://github.com/conda-forge/cfep/blob/master/cfep-01.md) and
[PEP 1 -- PEP Purpose and Guidelines](https://www.python.org/dev/peps/pep-0001/), both have been placed in the public domain.
The [IPEPs: IPython Enhancement Proposals](https://github.com/ipython/ipython/wiki/IPEPs:-IPython-Enhancement-Proposals) was also referenced for inspiration.

## Copyright

This document is [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).
