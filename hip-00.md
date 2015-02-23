```
HIP:01
Title: HIP Purpose and Guidelines
Type: Process
Id: $id$
Author: Morgan Gangwere <morgan.gangwere@gmail.com>
Created: 2015-02-23
Status: Draft
Requires: None
History:
	2015-02-23: Created
Original-HIP: quelab/00
```


What is a HIP?
==============

A Hackerspace Improvement Proposal (HIP) is a means to Get Things Done and codify things within a hackerspace. The HIP should provide a concise specification of the actions, details or policies held within it.

We intend HIPs to be a means for a hackerspace to codify and make "real" things that are often taken for granted, and a primary mechanism for proposing changes to the functioning of a hackerspace. The HIP author is responsible for building concensus within the community and documenting dissenting opinions.

Because HIPs are maintained as text files in a versioned repository, their version history is intended to be a historical record of their lifetime.

HIP types
=========

There are three kinds of HIP:

1. A **Policy** HIP describes a policy which affects the running or management of the space, resources, processes, etc. They are rules which define how something should happen or act on a high level.

2. An **Informational** HIP describs an issue or detail, or provides clarification for a priorr HIP. Informational HIPs do not neccesarily represent a conscensus or reccomendation. There are cases where Informational HIPs may be ignored.  

3. A **Process** HIP describes a process within the space, or proposes a change to (or an event in) a process. Process HIPs propose an implementation, be it of a particular sequence (e.g. business related processes or space usage processes) or a policy (i.e. how a particular policy is effected). Examples include procedures, guidelines, tool usage steps.

A policy HIP which specifies that an action must be taken *must* require an HIP to describe the process of that action, its prequisites, etc. A Meta-HIP may be implemented to "bind" the two together.

HIP workflow
============

The Board
---------

There are several references in this HIP to 'The Board' -- This group of idividuals are considered the ultimate deciders on certain policies that the space implements. They are referenced for completeness.

The Editors
-----------

The Editors (or HIP editors) are individuals responsible for the administrative and editorial aspects of the HIP workflow (e.g. assigning HIP numbers and changing their status).

These are made up of the space officers.

The HIP editorship is extended, by invitation, to those interested within the space. The mailing list "hips" should be used to discuss the administrativia of managing HIPs (such as requesting HIP numbers or providing an updated version of a PEP for posting). Cross-Posting is verboten.

Submitting a HIP
----------------

The HIP process begins with a new idea for the space. It is highly recommended that a single HIP contain a single key proposal or new idea. Small enhancements or patches do not need an new HIP, and could possibly be maintained as a patch against an existing HIP. The HIP editors reserve the right to reject HIP proposals if they appear too unfocused or broad. When in doubt, two HIPs would probably be better than one.

Each HIP must have a champion -- one member who writes the HIP in the style and format described within this HIP, sheperds discussion in the appropriate venues and attempts to build community consensus around the idea. The HIP champion (nee author) should first attempt to ascertain if the idea is HIP-able. Posting to the mailing list for the space or bringing it up in person is the most-best way of going about this.

Vetting an idea publicly before going as far as writing a HIP is meant to save potential authors and contributors time. Many ideas have been brought forward for the management of hackerspaces; many of these have been rejected for various reasons. Asking the community first if an idea is original helps prevent too much time spent on something that is guaranteed to be rejected based on prior discussions (searching the internet does not always do the trick). It helps make sure ideas are applicable towards the membership base and not just the author. Just because an idea sounds good to the author does not mean it will work well for the membership at large.

Once the champion has asked the community as to if the idea has any chance of acceptance, a draft HIP should be presented to the membership via email, printed copy or discussion, whichever the author feels is the best option to get their details heard. This gives the author a chance to flesh out the draft HIP to make sure it is properly formatted, high quality, and addresses the intial concerns about the proposal.

Following a discussion (preferrably on multiple medias), the proposal should be sent as a draft to the editors. The draft must be written in the style described below, else it will be sent back without further regard to until proper formatting rules are followed (minor errors should however be corrected by the editors).

If the HIP editors approve, they will assign the HIP a number, in the format of a two (or three) digit value, a hyphen, and a two to four letter identifier that identifies the space itself (e.g. 00-QLAB, 99-LHS, or 22-NSBG for quelab, London Hack Space, and Noisebridge, respectively).

Once approved, the HIP editors will label it as Informational, Policy, or Process, assign it the "Draft" status, and check-in the initial draft of the HIP. The HIP editors will not unreasonably deny an HIP. Reasons for denying the HIP status include duplication of effort, being technically or legally unsound, not including proper motifvatin or adressing concerns of safety, or not keeping in line with the mission of the space. The Board can be consulted during the approval phase, and is the final arbiter of the draft's HIP-ablility.

Members with git push privledges for the 'HIP Repository' may claim HIP numbers directly by creating and committing a new HIP. When doing so, the member must handle the tasks that would normally be taken care by the HIP editors (see "HIP editor responsibilities & workflow"). This includes ensuring the intial version meets expected standards for submitting an HIP. Alternatively, members with this access may still go through the process of consulting the HIP editors and working through the entire beginning process, but may update the HIP later on directly.

As updates are necessary, the HIP author can check in new versions of they (or a collaborating member) have git push privledges, or else they can email new HIP versions to the HIP editors for publication.

After a HIP number has been assigned, a draft HIP may be discussed further on appropriate medias with the membership. Getting an HIP number assigned early is useful for ease of reference, if multiple HIPs are being discussed at the same time.

Policy HIPs consist of two parts: The policy text and an implementation of that policy. It is generally recommended that the process HIP associated with the policy be presented along side the policy HIP, to avoid confusion of the effecting of the policy.

HIP review and resolution
-------------------------

Once the authors have completed an HIP, they may request a review for style and consistency from the HIP editors. However, the content and final acceptance of the HIP must come from the membership. HIPs are reviewed by the membership, who may accept or reject an HIP.

Acceptance of an HIP must come from, at minimum, 10 non-author members of the space. The suggested guideline should be that twice the number of authors, or 10, whichever is higher, must approve the conent of the HIP.

In cases where there is a limited number of people who inhabit the space on a common basis during regular space-regulation meetings, a minimum number should exceed no more than 25% of the active membership.

For an HIP to be accepted it must meet certain minimum criteria: It must be a clear and complete description of the proposed improvement. With Policy HIPs, the proposed implementation, must be complete and described in adequate detail. The poposed implementation must be as well "hacker-friendly - that is, it must be described in enough clarity that as few alternate interpretations as possible may be taken. 

Once an HIP is accepted, it is given the status "Accepted", and discussion may be closed on it, and any immediate effects of the HIP should be effected.

If a reference implementation is required, it must be approved separately from its policy. Once both are approved, both are given the status of "Final".

If an HIP is rejected, it is given the status "Rejected". Perhaps, after all is said and done, it was not a good idea. It is still important to record this fact; The HIP retains its number and is noted as being "rejected".

An HIP may be, should the authors feel the need, "Withdrawn" - The HIP authors themselves decided that the HIP is in reality a bad idea, or has accepted that a competing proposal is a better idea, or moots the need for their HIP.

Whenever an HIP is Accepted, Rejected or Withdrawn, the HIP should be updated accordingly. In addition to updating the status field, at the very least a history line should be added to the HIP denoting the date of change.

HIP Maintenance
---------------

In general, Policy HIPs are no longer modified. Process HIPs may be updated to reflect changes within the sapce. Informational HIPs should be amended with either a small patch or, in certain cases where the information is honestly new, a new HIP should be placed into the cycle.

What belongs in a successful HIP?
=================================

Each HIP should contain the following:

1. Preamble - An RFC 822 set of headers containing meta-data bout the HIP, including HIP number, a short descriptive title ( no greater than 20 words ), the names and optionally in the contact information, history, etc.

2. Abstract -- A short (approx 200 word) description of the issue being addressed.

3. Copyright/Public domain. Each HIP must be explicitly listed as being Public Domain or placed onder a Creative Commons license.

4. Specification -- the details decribing the problem at hand.

5. Rationale -- The reasonaing behind why this HIP is neccesary, and how it affects the space. Rationale should provide evidence of conscensus withi nthe membership and discuss important concerns raised during discussion. 

8. Reference implementation: In Policy HIPs, a reference implementation *must* be given, unless rationale for its omission is presented and approved.

HIP formats
===========

HIPs should be written in plain text. Any markup should conform to the [Common Markdown](http://commonmark.org/) standard.

HIP Preamble
============

Each HIP must begin with an RFC 822 style header preamble, wrapped in a backtick code block, as defined by the Common Markdown specification. The hreaders must appear in the following order. Headers marked with `*` are optional. All other fields are 

```
HIP: <HIP Number>
Title: <HIP Title>
Type: <Process|Informational|Policy>
Author: < List of author's names, optionally including email addresses. >
Created: <Date of original creation>
Status: <Draft | Accepted | Rejected | Final | Superseded >
*Replaces: < HIP number(s) which are rendered Superseded by this HIP >
*Superseded-By: <HIP number which makes this HIP superceded >
*Requires: < HIP numbers that are required by this HIP. >
History:
	<history blocks; see below>
* Original-HIP: < attribution URL for an HIP from another space >
*Id: $id$
```

The Author header lists names, and optionally email addresses of the authors/owners of an HIP. They should follow the format

``` Random J. user <address@dom.ain>```

or, omitting address,

``` Random J. Anon ```


The History header is made up of multiple lines of history blocks. History blocks are defined as

```
<TAB> YYYY-MM-DD: <event name>
```

They are listed in reverse chronological order (most recent first).

The `id` header is reserved for version control systems. It should be maintained by the HIP maintainers, or omitted for clarity.

The Original-HIP header attributes the work taken from another hackerspace, in the case that a hackerspace has copied the work of another, modifying to their needs.

HIP Editor responsibilities & workflow
======================================

An HIP editor must subscribe to the HIP editor mailing list. All correspondence related to HIP administration should be sent/forwarded to the list. Cross-Posting is verboten.

For each new HIP that comes in, an editor does the following:

* Read the HIP to check if it's ready: functionally sound and complete. The ideas must make technical sense, even if they don't seem likely to be accepted.

* check that the title must accurately decribe the content

* check that a policy HIP has a process or rational for the lack of process that is logical to the editor.

* edit the HIP for language (spelling, grammar, structure, etc.) markup (that it contains no egregious errors in Markdown), and any cultural style (esp. for importend HIPs).

If the HIP isn't ready an editor will send it back to the author for revision, with specific instructions.

Once the HIP is ready for the repository, an HIP editor will:

* Assign an HIP number (almost always the first available number. Exceptions follow.)

* Add the HIP to a local clone of their repository (or edit it via a web interface)

* Send email to the HIP author with next steps (post to the main membership mailing list, and assure that it gets on the next general meeting agenda)

Updates to existing HIPs are also send to the list. many HIP authors are not going to have commit access. The HIP eitors do commits on their behalf.

Editors do not pass judgement on HIPs: They merely do the administration and editorial part, which is genrally a low volume task.

Exceptions to the "next-available" rule
---------------------------------------

Exceptions should be made; Humerous HIPs should be given an appropriate number (They will exist!). Other exceptions include:

* Policy HIPs that include an implementation are given a `-a` and `-b` suffix, respectively.
* Informational HIPs begin at 1000
