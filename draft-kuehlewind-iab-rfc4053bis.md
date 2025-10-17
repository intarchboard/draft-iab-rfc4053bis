---
title: "Procedures for Handling Liaison Statements to and from the IETF"
abbrev: "Handling of Liaison Statements"
category: info

docname: draft-kuehlewind-iab-rfc4053bis-latest
submissiontype: IAB
obsoletes: 4053
date:
v: 3
venue:
  group: "Internet Architecture Board"
  type: "Internet Engineering Task Force"
  mail: "iab@iab.org"
  github: "intarchboard/draft-iab-rfc4053bis"

author:
 -
    fullname: Mirja Kuehlewind
    organization: IAB
    email: ietf@kuehlewind.net
    role: editor
 -
    fullname: Suresh Krishnan
    organization: IAB
    email: suresh.krishnan@gmail.com
 -
   fullname: Qin Wu
   organization: IAB
   email: bill.wu@huawei.com

normative:

informative:


--- abstract

This document describes the procedures for generating and handling
liaison statements between the IETF and other SDOs, so that the IETF can
effectively collaborate with other organizations in the international
standards community.


--- middle

# Introduction

This document describes the procedure for generating and handling
liaison statements between the IETF and other SDOs, so that the IETF can
effectively collaborate with other organizations in the international
standards community.

Most organizations have a process to send liaison statements that simply
provides a more formal way of communication, beyond just sending an informal
email. However, every organization has slightly different procedures to
handle the sending and receiving of liaison statements. In some cases
sending formal liaison statements might be the only way of
communicating with a certain organization.
The IETF process
is intended to be as simple as possible while still accommodating the process
or format requirements of various other SDOs. One key property of the IETF
liaison statement handling process is the requirement to record all sent
and received liaison statements in a publicly accessible central location,
which makes its more formal than other direct communications. However,
liaison statements do not have any special standing within the IETF process
otherwise. This means that any input provided through a liaison statement,
even if that statement reflects consensus in the other organisation, does
not have a different standing in the IETF process than other
(individually-provided) inputs.

Further, liaison statements sent by the IETF usually do not go
though the normal IETF consensus process (e.g. an IETF-wide last call)
and therefore do not automatically represent IETF consensus. Depending on the
nature of the liaison statement, it might refer to existing IETF consensus
as documented in IETF-stream RFCs or working group chairs might ask for
working group consensus on a technical matter not (yet) documented in an RFC.
While the existence of a formal liaison statement does not automatically
imply any form of consensus within the IETF process, liaison statements still
reflect an official position supported by leadership approval and particularly
underline when the stated position is based on existing community consensus.
When sending a liaison
statement from the IETF, it is highly recommended to clearly
indicate any level of consensus or non-consensus as part of the liaison
statement content.

The exchange of liaison statements does not require a formal liaison
relationship (see {{?I-D.krishnan-iab-rfc4052bis}}).  The procedures described in this
document encompass all liaisons statements received from SDOs,
whether or not a formal liaison arrangement is in place between the
SDO and the IETF.

Receive of a liaison statement does not automatically
impose an obligation of sending a response by the other party. The decision
to send a response depends on the content and kind of request.
A liaison statement, just like any other input into the IETF process, is
considered for its relevance, importance, and urgency. However,
if a formal liaison relationship exists, it is the responsibility
of the liaison manager to ensure appropriate communication
between the organisations (see {{Section 3 of I-D.krishnan-iab-rfc4052bis}}) even if no response is sent.

If no response to an incoming liaison statement is provided, this does not
indicate agreement or consensus on the topic raised to
the IETF. IETF positions require community rough consensus
via processes managed by the working group chairs and the Internet Engineering Steering Group (IESG).

Sometimes liaison statements sent from other SDOs may cover topics
that are relevant for research done in the IRTF. In this case the IAB
consults with the IRTF chair who might choose to forward them
to any relevant IRTF research group(s). The IRTF chair as a member of IAB
can work with the IAB, as well as specific research group chairs,
to decide whether a response to the liaison statement is needed. Research groups
do not initiate sending of liaison statements.

## Changes compared to RFC4053

The major change in this revision of the document is that all tooling details have been removed.
Particularly, some text in the introduction, Section 3.1.1. (Liaison Statement Submission),
Section 3.1.2. (Mechanism for Displaying Liaison Statements), Section 3.2.2.4. (Generating Liaison Statements)
and the appendix have been removed.

Further, the following guidance has been updated in the -00 version:

1. A shorter abstract and introduction, as well as a clarification in the introduction about obligations to send replies.
2. Removal of the definition section (2.1) as "assignee" is not used anymore, and the "addressee" is now simply called the receiver.
3. The section on "Content of a Liaison Statement" has been revised to
    - be less detailed about tooling, e.g. not talking about concrete fields anymore,
    - introduce a new concept to handle contact information, replacing "Response Contact" and
     "Technical Contact" as well as additional fields ("CC", "From Contact", "To Contact") that exist in the tooling
     but are actually not specified in {{?RFC4053}} and therefore often caused confusion,
    - add new address information ("Send Reply To"/"Send To") that can be used to support processes
     where one central address is used to receive all liaison statements. This is also the process preferred now by the IETF,
     where the central address is either the liaison manager or the IAB coordination contact.
4. The purpose "For comment" has been removed as either "For information" or "For Action" can be used instead;
  depending if a deadline is needed or not. In the current record of statements, "For comment" has been rarely used
  indicating that this purpose is not needed or at least its meaning was not clear.
5. New section on "Recording Liaison Statements" that replaces Section 2.4. on "Lifetime of a Liaison Statement"
  to underline how important the public record of a liaison statement is and clarify the responsibility of the receiver
  to ensure that all incoming statements get appropriately recorded.
6. Section 4 from {{?RFC4052}} on "Approval and Transmission of Liaison Statements" has been moved to this document, without modification so far.

Changes in the -01 version:

1. New text in intro on "no special standing" and consensus
1. Minor wording adjustments to avoid tooling implications
2. Merge section 3 (Responsibilities when Receiving a Liaison Statement) into Section 4 (Recording) and 6 (Responding)

#  Content of Liaison Statements

A Liaison Statement is a business letter sent by one standards
organization to another. These organizations may be at any level
(WG, Area, etc.). Generally, the sender and receiver are peer
organizations. A liaison statement may have any purpose, but
generally the purpose is to solicit information or
request an action, like share a document, or ask for a review or a technical question.

Liaison statements may be very formal or informal, depending on the
rules of the body generating them.  Any liaison statement, however,
will always contain certain information, much as a business letter
does. In order to be able to process and record these statements
in the IETF, the information should include the following:

##  Contact Information

The following contact information are expected to be part of a liaison statement:

From:
: The statement needs to indicate from what body it originates; for
   example, it may be from an IETF Area or WG, an ITU-T Study Group,
   Working Party, or Question, etc. A statement may be sent from more than one group, e.g. multiple IETF
   working groups, but usually all groups are from the same organization.

From-Contact:
: One or more electronic mail addresses belonging to the "From" body.
   This includes the addresses associated with the "From" group(s),
   e.g. in the IETF these are the working group chairs, working group mailing lists, and Area Director(s), and
   contacts that are required for the management of the liaison, like the
   liaison manager (if one exists) and/or an IAB liaison contact in case of statements sent by
   the IETF or the staff person from the external organisation that has sent the incoming
   liaison by mail, as well as any additional technical experts who should be informed.

From-Liaison-Contact ("Send Reply to"):
: An explicit "Send Reply To" address may be provided that is used for processing
   the liaison statement reply. This address is usually not a personal address but rather a generic
   address associated with a role or process. For liaison statements sent by the IETF, this address should be the alias
   of the liaison manager, if applicable, or an address maintained by the IAB for liaison
   management such as liaison-coordination@iab.org. If a "Send Reply To" address is provided, the expectation is that a statement
   sent in reply will only be sent to this address and will then be distributed
   accordingly internally in the receiving organisation follow their internal process.

To:
: The statement needs to indicate to which body it is sent. A statement may be sent to multiple bodies or
   groups within one body.

To-Contact:
: One or more electronic mail addresses from the receiving body to which this
   statement should be sent. Similar as the "From-Contact" this includes all addresses
   associated with the "To" information, additional contacts that are required for liaison management,
   as well as any additional experts.

To-Liaison-Contact ("Send to"):
: If this address is present, the liaison statement is only sent to this address and not
   to the addresses in the "To-Contact". If a liaison statement is a reply, this "Send to" address is
   the "Send Reply To" address provided by the other organisation in the original statement.
   This supports processes where an organisation has a central contact address to receive statements
   and then distributes the statement using their own process to the appropriate groups and persons internally.

## Purpose

A liaison statement generally has one of three purposes and should
clearly state its purpose using one of the following labels:

For Information:
: The liaison statement is to inform the receiving body of
      something and expects no response. This includes calls for review
      comments if the expected response is optional.

For Action:
: The liaison statement requests that the receiving body does
      something on the sender's behalf, usually within a stated time
      frame. This is also used if a document is sent out for comment, and
      the review feedback is expected in the stated time frame.

In Response:
: The liaison statement includes a response to a liaison
      statement from the peer organization on one or more of its
      documents and expects no further response.

Liaison statements that request action indicate a deadline when
the action is required.  If the receiving body cannot
accomplish the request within the stated period, courtesy calls for a
response offering a more doable deadline or an alternative course of
action.

## Body, Title, and Attachments

As with any business letter, the liaison statement contains
appropriate content explaining the issues or questions at hand.

Usually, the statement also contains a short (single line) title
providing a statement of its context and content.

Attachments, if enclosed, may be in the form of documents sent with
the liaison statement, or may be URLs to similar documents, including
Internet Drafts.

IETF participants use a wide variety of systems, thus document
formats that are not universally readable are problematic. As a
result, documents enclosed with the body or attachments should be in
PDF, W3C HTML (without proprietary extensions), or UTF-8 encoded
plain/text format.
If they were originally in a proprietary format, such as Microsoft
Word, the file may be sent, but should be accompanied by a generally
readable file.

Different organisation have different requirements on the format of
liaison statements. There are no requirements from the IETF on the format
of the actual liaison statement; however, we require
the metadata (address information and purpose) as indicated in the previous
section to be recorded explicitly. As such, when receiving statement from other organisation
these metadata should be extracted. Further, the content of the statement must be recorded. This content may be recorded by archiving a received document in its original format, such as PDF or word, or may be transformed into another format, such as plain text or markdown, when it is reasonable to do so.

For statements sent from the IETF, it is recommended to provide the content
in plain text, but also provide an attachment following the formatting requirements
of the receiving organisation if possible. If cases where we have a
liaison manager, it is the responsibility of the liaison to check or convert
the formatting requirements. It is further recommended to convert received
documents in proprietary formats into PDF and upload both versions as
attachments.

This ensures that our process can comply with all formatting requirements
from other organisations.

#  Recording Liaison Statements

For the IETF, a liaison statement is a message that was sent or received
(usually an email or some formal letter)
that is recorded in our liaison management tool,
i.e. the value of sending a liaison statement for an organization compared to a mail,
is that it will officially be recorded, and the public record will attest
that certain information has been communicated between the organizations.

## Incoming Liaison Statements from Other SDOs

The IETF will record any received liaison statement and make it publicly available.

For a received liaison statement with a formal liaison relationship, it is the responsibility
of the liaison manager to create that public record. However, even if a
formal liaison relationship exists, it is possible that liaison statements arrive
without knowledge of the liaison manager, therefore it is generally the
responsibility of the receiver to ensure a public record is created.

Liaison statements that are sent to the IETF without a liaison manager
are generally handled by the IAB. Ideally, statements are sent to a contact point
appointed by the IAB, who record them and further distributes them within the IETF to the
right groups and experts. This enables a better control to ensure that
liaison statement are received by the relevant parties.

However, it is hard to ensure that liaison statements will always be sent to the right
group or person, as statements are sometimes sent directly to WG mailing lists or
individuals. E.g an SDO might send a liaison statement to a specific IETF
Area whose Area Director (AD) deems it better handled by one of the WGs,
or it might be sent to one WG when it should have gone to a different, more relevant one.
If a liaison statement arrives that appears misdirected, it is recommended
to manually forward it to the right groups and inform the liaison manager or
the IAB so that informal feedback can be provided to the sender for the future.

## Outgoing Liaison Statements from the IETF

IETF participants (usually WG chairs or ADs), of course adhering to the requirements
on approval and consensus as outlined in the next section, can
send liaison statements to other SDOs, and all sent liaison statements
must be publicly recorded. Therefore,
it is recommended to use an IETF-provided tool to send liaison
statements, rather than send them directly by email and record
them after the fact. This approach is possible e.g. if a certain form
of submission other than email is required by the other organization.

#  Sending Liaison Statements from the IETF

There are different reasons for an IETF group to send a liaison statement
to another organization such as

* A working group might request additional information from another organization,
  for example, to resolve an impasse (i.e., don't waste time arguing over what the real meaning or
  intent of another SDOs document is, just ask the other SDO and base
  further work on the "official" answer).
* A working group might request comments for a document under development
  in the IETF that would benefit from the input of experts in another relevant
  SDO, consortium, or forum.  Generally, this is done before the text
  is "fully cooked" so that input from experts in another organization
  can be included in the final result.
* In the case of overlapping or related work in another organization,
  a request could be made that the other organization
  change something to align with the IETF work.
* A request could be made for another organization to start a new
  work item (on behalf of IETF).
* A request could be made for another organization to stop a work
  item (presumably because it overlaps or conflicts with other work
  in the IETF).

Further, a group might reply to an incoming liaison statement, as in more detail
discussed in the next section, however, of course, the same requirements
on consensus and approval as discussed in this section are applied.

Liaison Statements can be generated at a WG, Area, or IETF level to another
organization. The respective (co)chair(s) or Area Director (AD) are responsible
for deciding the content and judging the level of consensus that is needed
for sending the respective content. This section outlines approval
requirements and gives guidance about the level of consensus that should be
sought before sending a liaison statement to another organization.

Generally, it is recommended to base liaison statements
on existing consensus (in the form of references to RFCs or other IETF documents)
or focus on information sharing related to e.g. process like expected timelines,
rather than aiming to communicate technical matters beyond the active work
of the respective group. Further, the level of consensus implied or not
implied by the liaison statement should be spelled out clearly in the
liaison statement itself, as this provides the most clarity and avoids potential
confusion.

## Approval

All liaison statements sent by any group in the IETF
need AD approval to ensure that those writing such
statements, who claim to be speaking on behalf of a group in the IETF, are truly
representing IETF views. This does not include statements sent by the IAB,
which require IAB approval instead, based on the judgment
of the IAB Chair. Statements sent from an area,
respectively, need approval by at least one of the responsible ADs.
Statements sent by the IETF or IESG require IETF Chair approval.

Sometimes it is beneficial or required to send a statement that indicates
the IETF as the originator rather than a specific working group or
area. This might be the case e.g. for questions related to the scope
of work of the IETF as a whole rather than a specific chartered group.
In this case, approval of the IETF Chair is required; however, it is usually expected
that other matter experts, sometimes from the IESG or IAB, are involved
in generating the content of the statement.

Statements sent by the IESG do not have different approval requirements
than statements sent by the IETF, which require IETF Chair approval.
This is to avoid heavy processes when sending liaison statements,
however, statements from the IESG might imply there is consensus
among the IESG and, as recommended earlier in this document,
it is best to clarify in the statement itself if that is
intended or not.

In cases where prior approval was not obtained as outlined above,
and the designated authority (AD, IETF Chair, or IAB Chair) in fact
does not agree with the message, the designated authority will work
with the liaison manager or IAB to follow up as appropriate, including
emitting a revised liaison statement if necessary.  Clearly, this is
a situation best avoided by assuring appropriate agreement in advance
of sending the liaison message.

## Level of Consensus {#consensus-sending}

A liaison statement does not automatically imply any level of consensus
and as such it is the responsibility of the chairs or the responsible AD to
figure out if a working groups consensus should be strived for before
sending a liaison statement.

The simplest case of sending a liaison statement from
IETF is when the information being transmitted is based on
already existing IETF consensus, such as an IETF
document that has some level of agreement within the IETF
or general information about the process or (WG) scope.
When sending such statements for pure information sharing
purposes, the chairs or AD might not reach out for consensus.

Further, requests for information from the other organization,
including requests for access to certain documents of other
organizations that are not publicly available, may be initiated by
the chair if the additional input is considered helpful for the group's
progress.

Other requests, that might often be initiated by a specific group discussion,
such as soliciting comments for a standards track WG Internet Draft,
usually benefit from some level of consensus to be reached in the WG, or
another appropriate, open mailing list.

Generally, it is recommended to inform the respective group or individuals
before transmitting a statement to create early awareness
as the recording and sending of the statement must be announced to the originating group.

## Transmitting (references to) documents {#transmit-docs}

Any Standards Track RFC (Draft Standard, Proposed Standard, Internet
Standard, BCP), and any WG document expected to be placed on the
standards track, may be transmitted without concern. Informational
documents may also be exchanged readily when they
represent a WG position or consensus, such as a requirement or
architecture document.

Individually submitted Internet Drafts, Experimental or Historical
RFCs, and non-WG informational documents should not be transmitted
without developing further consensus within the relevant group, as
these documents cannot be truthfully represented as any kind of IETF
position.

In all cases, the document status must be appropriately noted.  In
the case of a WG Internet Draft, it must be clear that the existence
of the draft only indicates that the WG has accepted the work item
and, as the standard disclaimer says, the actual content can be
treated as nothing more than as 'Work in Progress'.


#  Receiving and Responding to Incoming Liaison Statements

The responsibilities of the receiver of a liaison statement are the
same as the responsibilities of any business letter.  A liaison
statement calls for appropriate consideration of its contents.
Liaison Statements are always important to the body that sent them.
Having arrived at the appropriate body, the liaison statement may be
more or less important to the receiver depending on its contents and
the expertise of the sender.

If the liaison statement seeks to influence the direction of a WG's
development, it should receive the same consideration as any
input document receives. This could be the case if a liaison statement
provides input to a working group document, requests modifications, or
new work, or comments on the scope of work. The WG
chair may request the sender to make their case to the
IETF WG in the same manner that an author of an Internet-Draft makes
their case.

If a reply is requested (usually marked as "For Action"),
the originating organziation expects a response by the deadline.
The urgency of a liaison statement is usually reflected in its
deadline. A liaison statement specifying a deadline
gives the receiver a finite opportunity to influence the activity of
another body; if it fails to react in a timely fashion, it may miss
the opportunity.

Examples of the kinds of actions that may be requested are:

* Access to documents or information about the process and timelines.
* Comments on a document of another organisation.
* Technical questions related to an RFC or working group document.
* A request for the IETF to align its work with that of the other
  organization, in the case of overlapping or related work.
* A request for the IETF to undertake a new work item.
* A request for the IETF to stop a work item (presumably because it overlaps
  or conflicts with other work in the originating organization).

The originating organization should always be
informed of what, if anything, the IETF has decided to do in response
to the request, either by sending a formal liaison statement back or
utilizing information communication, like a simple email reply, if
appropriate. If a formal liaison relationship with a liaison manager exists,
it is the responsibility of the liaison manager to ensure appropriate communication.
Otherwise, the IAB can be consulted and should be integrated into any additional
informal communication.

There is, of course, no requirement that IETF perform the action that
was requested.  But the request should always be taken seriously, and
generally, a response is anticipated. The reply may be that the information
was useful or not useful, that the requested action has been accomplished,
it will be accomplished by a specified date, it will not be done for a
specific reason, an answer to a question posed, or any other appropriate reply.
If the IETF decides not to honor the request, or to
honor it with modifications, ideally, the response should include the reasons
and, if applicable, an alternate course of action.

It is the responsibility of the (co)chair(s) of
the addressed group, supported by the liaison manager if one exists,
to ensure that a response is generated by the deadline if a response is intended.
In some cases, a liaison statement may require consideration by multiple groups within
the IETF; in such cases, potentially multiple chairs and area directors
have to coordinate, but ideally one of them takes the lead and
responsibility for developing a response.

## Level of Consensus When Sending a Response

As discussed in {{consensus-sending}}, it is the chairs' and AD's
responsibility to decide about the necessary  level of consensus needed
for a certain response. This section adds additional consideration
when replying to a request from another organization.

As also discussed in {{transmit-docs}}, if another organization
requests information that can be found in an IETF document, this can be
transmitted by the (co)chair(s) of the addressed group, indicating
the level of agreement for the relevant document.

If an incoming liaison statement requests information that goes beyond
what is documented in existing IETF documents, such as asking for comments
on a document from another organization or a specific technical question
not addressed in existing RFCs, the chairs should seek for group input.
Usually, such a request is received on the mailing list of a group,
a discussion will occur on the mailing list where participants can provide
their comments.

If a clear consensus is evident from the pattern of comments made to
the mailing list, the (co)chair(s) can summarize the conclusions in a
reply liaison statement back to the originating organization.

If no clear consensus is evident from the pattern of comments on the
mailing list, or if there is no further discussion, a response is
still anticipated to the originator.  A summary of the email comments, or
lack of interest in the issue, can be created and sent to the
originator, and represented as "collected comments" rather than a
consensus of the IETF group to which the liaison statement was
addressed.  It is possible to send this kind of reply even if some
of the comments are contradictory.

For other requests for actions, for example, if initiating or stopping a
work item requires a charter change, the consensus of the receiving group
within IETF or even IETF-wide consensus is clearly necessary to fulfill
the request. However, as already indicated, a liaison statement has no
special standing and should be considered equal to all other inputs.
Still, if there is a need for this work by the other organization the request
should be considered seriously. Usually, it is appropriate for the chairs
to send a response (by the deadline) and explain the process, or invite experts
of the other organization to participate directly,
even if the request itself cannot be fulfilled  by the deadline.
Potential follow-up liaison statements might be sent to provide a status update,
e.g. when a document gets adopted or is ready for publication.


# Security Considerations

   One of the key considerations in developing this process has been the
   possibility of a denial of service attack on the IETF and its
   processes.  Historically, the IETF has not always handled liaison
   statements effectively, resulting in people working in other
   organizations becoming frustrated with it.  Various organizations
   have also used the liaison statement process to impose deadlines on
   IETF activities, which has been frustrating for all concerned - the
   IETF because it does not accept such deadlines, and other
   organizations because they feel ignored. While the IETF
   cannot rate-limit the submitters, it can manage its internal
   pipelines.

   This issue is exacerbated by the lack of any authentication on the
   part of the submitter.  However, the IAB considers it important to be
   able to accept liaison statements, whether or not a liaison
   relationship exists, so authentication of submitters is not an
   effective control.


# IANA Considerations

This document has no IANA actions.

# Acknowledgments
{:numbered="false"}

{{RFC4053}} was authored by Stephen Trowbridge, Scott Bradner, Fred Baker.
The text in RFC4053 further has been prompted by discussions with numerous individuals
within IETF and other SDOs and fora, including Gary Fishman and Bert
Wijnen.  It has been developed in cooperation with {{?RFC4052}}, which
is to say with the express cooperation of the chair of the IAB at that time,
Leslie Daigle.

This document contain parts of text from {{RFC4053}}, however, all tooling
details were removed and the remaining text will be reworked step by step with
the goal to end up with a shorter and clear document that outlines requirements
and gives high-level guidance to people sending and receiving liaison statements.

--- back
