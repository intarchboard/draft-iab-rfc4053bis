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

Most organizations have a process to send liaison
statements that simply provides a more formal way of communication, beyond 
just sending an informal email. However, every organization has 
slightly different procedures to handle the sending and receiving of liaison
statements. The IETF process is intended to be as simple as possible
while still accommodating the process or format requirements of various
other SDOs. One key property of the IETF liaison statement handling process
is the requirement to record all sent and received liaison statements in
a publicly accessible central location, which makes its more formal
than other direct communications. However, liaison statements do not
have any special standing within the IETF process otherwise. This means
that any input provided through a liaison statement, even if that statement
reflects consensus in the other organisation, does not have a different
standing in the IETF process than other (individually-provided) inputs.

Further, liaison statements that are sent by the IETF do not always
pass though the normal IETF consensus process, e.g. in an IETF-wide
last call, and therefore do generally not represent IETF consensus. Depending
on the nature of the liaison statement, it might refer to existing
IETF consensus as documented in IETF-stream RFCs or working group chairs
might ask for working group consensus on technical matter not (yet)
documented in an RFC. However, just the existence of a formal liaison
statement does not automatically imply any form of consensus within the IETF process.
When sending a liaison statement, it is highly recommended for senders on the IETF side to clearly indicate
any level of consensus or non-consensus as part of the liaison statement content.

The exchange of liaison statements does not require a formal liaison
relationship (see {{?RFC4052}}).  The procedures described in this
document encompass all liaisons statements received from SDOs,
whether or not a formal liaison arrangement is in place between the
SDO and the IETF.

Receive of a liaison statement does not automatically
impose an obligation of sending a response by the other party. The decision
to send a response depends on the content and kind of request. However,
if a formal liaison relationship exists, it is the responsibility
of the liaison manager to ensure appropriate communication
between the organisations (see {{Section 3 of RFC4052}}) even if no response is sent.

## Changes compared to RFC4053

The mayor change in this revision of the document is that all tooling details have been removed.
Particularly some text in the introduction, Section 3.1.1. (Liaison Statement Submission),
Section 3.1.2. (Mechanism for Displaying Liaison Statements), Section 3.2.2.4. (Generating Liaison Statements)
and the appendix have been removed.

Further the following guidance has been updated in the -00 version:

1. A shorter abstract and introduction as well as a clarification in the introduction about obligations to send replies.
2. Removal of the definition section (2.1) as "assignee" is not used anymore and the "addressee" is now simply called receiver.
3. The section on "Content of a Liaison Statement" has been revised to
    - be less detailed about tooling, e.g. not talking about concrete fields anymore,
    - introduce a new concept to handle contact information, replacing "Response Contact" and
     "Technical Contact" as well as additional fields ("CC", "From Contact", "To Contact") that exists in the tooling
     but are actually not specificed in {{?RFC4053}} and therefore often caused confusion,
    - add new address information ("Send Reply To"/"Send To") that can be used to support processes
     where one central address is used to receive all liaison statements. This is also the process preferred now by the IETF
     where the central address is either the liaison mananager or the IAB coordination contact.
4. The purpose "For comment" has been removed as either "For information" or "For Action" can be used instead;
  depending if a deadline is needed or not. In the current record of statements "For comment" has been rarely used
  indicating that this purpose is not needed or at least its meaning was not clear.
5. New section on "Recording Liaison Statements" that replaces Section 2.4. on "Lifetime of a Liaison Statement"
  to underline how important the public record of a liaison statement is and clarify the responsibility of the receiver
  to ensure that all incoming statements get appropriately recorded.
6. Section 4 from {{RFC4052}} on "Approval and Transmission of Liaison Statements" has been moved to this document, without modification so far.

Changes in the -01 version:
1. Minor wording adjustments to avoid tooling implications
2. New text in intro on "no special standing" and consensus

#  Content of Liaison Statements

A Liaison Statement is a business letter sent by one standards
organization to another. These organizations may be at any level
(WG, Area, etc.). Generally, the sender and receiver are peer
organizations. A liaison statement may have any purpose, but
generally the purpose is to solicit information or
request an action, like share a document, or ask for a review or a technical question.

Liaison statements may be very formal or informal, depending on the
rules of the body generating them.  Any liaison statement, however,
will always contain certain information, much as an business letter
does. In order to be able to process and record these statements
in the IETF, the information should include the following:

##  Contact Information

The following contact information are expected to be part of a liaison statement:

From:
: The statement needs to indicate from what body it originates; for
   example, it may be from, an IETF Area or WG, an ITU-T Study Group,
   Working Party, or Question, etc. A statement may be sent from more than one group, e.g. multiple IETF
   working groups, but usually all groups are from the same organization.

From-Contact:
: One or more electronic mail addresses belonging to the "From" body.
   This includes the addresses associated with the "From" group(s),
   e.g. in the IETF these are the working group chairs, working group mailing lists, and Area Director(s), and
   contacts that are required for the management of the liaison, like the
   liaison manager (if one exists) and/or an IAB liaison contact in case of statements sent by
   the IETF or the staff person from the external organisation that has sent the incoming
   liaison by mail, as well as any additional technical experts that should be informed.

From-Liaison-Contact ("Send Reply to"):
: An explicit "Send Reply To" address may be provided that is used for processing
   the liaison statement reply. This address is usually not a personal address but rather a generic
   address associated to a role or process. For liaison statements sent by the IETF, this address should be the alias
   of the liaison manager, if applicable, or an address maintained by the IAB for liaison
   management such as liaison-coordination@iab.org. If a "Send Reply To" address is provided the expectation is that a statement
   sent in reply will only be sent to this address and will then be distributed
   accordingly internally in the receiving organisation follow their internal process.

To:
: The statement needs to indicate to which body it is sent. A statement may be sent to multiple bodies or
   groups within one body.

To-Contact:
: One or more electronic mail addresses from the receiving body to which this
   statement should be sent. Similar as the "From-Contact" this includes all addresses
   associated with the "To" information, addional contacts that are required for liaison management,
   as well as any additional experts.

To-Liaison-Contact ("Send to"):
: If this address is present, the liaison statement is only sent to this address and not
   to the addresses in the "To-Contact". If a liaison statement is a reply, this "Send to" address is
   the "Send Reply To" address provided by the other organisation in the original statement.
   This supports processes where an organisation has a central contact address to receive statements
   and then distributes the statement using their own process to the approrpiate groups and persons internally.

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
      frame. This is also used if a document is sent out for comment and
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

Usually the statement also contains a short (usually single line) title
providing a statement of its context and content.

Attachments, if enclosed, may be in the form of documents sent with
the liaison statement or may be URLs to similar documents including
Internet Drafts.

IETF participants use a wide variety of systems, thus document
formats that are not universally readable are problematic. As a
result, documents enclosed with the body or attachments should be in
PDF, W3C HTML (without proprietary extensions), or UTF-8 encoded
plain/text format.
If they were originally in a proprietary format such as Microsoft
Word, the file may be sent, but should be accompanied by a generally
readable file.

Different organisation have different requirements on the format of
liaison statements. There are no requirements from the IETF on the format
of the actual liaison statement, however, we require
the metadata (address information and purpose) as indicated in the previous
section to be recorded explicitly. As such when receiving statement from other organisation
these metadata should be extracted. Further, the content of the statement must be recorded. This content may be recorded by archiving a received document in its original format, such as PDF or word, or may be transformed into an another format, such as plain text or markdown, when it is reasonable to do so.

For statements sent from the IETF, it is recommended to provide the content
in plain text but also provide an attachment following the formatting requirements
of the receiving organisation if possible. If cases where we have a
liaison manager, it is the responsiblity of the liaison to check or convert
the formatting requirements. It is further recommended to convert received
documents in proprietary formats into PDF and upload both version as
attachments.

This ensures that our process can comply with all formatting requirements
from other organisations.

#  Responsibilities when Receiving a Liaison Statement

   The responsibilities of the receiver of a liaison statement are the
   same as the responsibilities of any business letter.  A liaison
   statement calls for appropriate consideration of its contents, and if
   a reply is requested and an appropriate relationship exists, a
   courteous authoritative reply within the expected time frame.  The
   reply may be that the information was useful or not useful, that the
   requested action has been accomplished, it will be accomplished by a
   specified date, it will not be done for a specific reason, an answer
   to a question posed, or any other appropriate reply.

   A liaison statement, just like any other input into the IETF process, must be
   considered for its relevance, importance, and urgency.

   One hopes that a liaison statement will be sent to the right
   organization, but this cannot be assured.  An SDO might send a
   liaison statement to a specific IETF Area whose Area Director (AD)
   deems it better handled by one of the WGs, or it might be sent to one
   WG when it should have gone to another.  If a liaison statement
   arrives that appears misdirected, the receiver should promptly ask
   the liaison manager to redirect it appropriately.  In some cases, a
   liaison statement may require consideration by multiple groups within
   the IETF; in such cases, potentially multiple chair and area directors
   have to coordinate but ideally one of them takes the lead and
   responsibility for developing a response.

   Liaison Statements are always important to the body that sent them.
   Having arrived at the appropriate body, the liaison statement may be
   more or less important to the receiver depending on its contents and
   the expertise of the sender.  If the liaison statement seeks to
   influence the direction of a WG's development, it should receive the
   same consideration that any input document receives.  The WG
   chair may request the sender to make their case to the
   IETF WG in the same manner that an author of an internet draft makes
   his or her case.

   The urgency of a liaison statement is usually reflected in its
   deadline.  A liaison statement for informational purposes has no
   deadline; in such a case, a courteous "thank you" liaison statement
   may be sent to inform the sender that the liaison statement was
   received.  A liaison statement specifying a deadline, however,
   gives the receiver a finite opportunity to influence the activity of
   another body; if it fails to react in a timely fashion, it may miss
   the opportunity.

#  Recording Liaison Statements

For the IETF, a liaison statement is a message that was sent or received
(usually an email or some kind of formal letter)
that is recorded in our liaison management tool,
i.e. the value of sending a liaison statement for an organization compared to a mail,
is that it will officially be recorded and the public record will attest
that certain information has been communicated between the organizations.

## Incoming Liaison Statements from Other SDOs

The IETF will record any received liaison statement and make it publicly available.
For received liaison statement with a formal liaison relationship, it is the responsibility
of the liaison manager to create that public record. However, even if a
formal liaison relationship exists, it is possible that liaison statements arrive
without knowledge of the liaison manager, therefore it is generally the
responsibility of the receiver to ensure a public record is created.

## Outgoing Liaison Statements from the IETF

IETF participants (usually WG chairs or ADs) can
send liaison statements to other SDOs, and all sent liaison statements
must be publicly recorded. Therefore,
it is recommended to use a IETF provided tool to send liaison
statements, rather then send them directly by email and record
them after the fact. This approach is possible e.g. if a certain form
of submission other than email is required by the other organization.

#  Sending Liaison Statements from the IETF

##  Communicating IETF Information to Other SDOs, Consortia, and Fora

   Liaison Statements can be generated at a WG, Area, or IETF level to
   another organization.  The respective (co)chair(s) are responsible
   for judging the degree of consensus for sending the particular
   liaison statement and deciding the content.  The amount of consensus
   required to send a liaison statement varies greatly depending on its
   content.  This section gives some rough guidance about how much
   consensus should be sought before sending a liaison statement to
   another organization.

##  Transmitting IETF Documents to Other Organizations {#transmit-docs}

   The simplest case of approving sending of a liaison statement from
   IETF is when the information being transmitted consists of an IETF
   document that has some level of agreement within the IETF.  The
   process that the document has already gone through to achieve its
   current status assures the necessary level of consensus.  Any
   Standards Track RFC (Draft Standard, Proposed Standard, Internet
   Standard, BCP), and any WG document expected to be placed on the
   standards track, may be transmitted without concern.

   Informational documents may also be exchanged readily when they
   represent a WG position or consensus, such as a requirements or
   architecture document.

   In all cases, the document status must be appropriately noted.  In
   the case of a WG Internet Draft, it must be clear that the existence
   of the draft only indicates that the WG has accepted the work item
   and, as the standard disclaimer says, the actual content can be
   treated as nothing more than Work in Progress.

   Individually submitted Internet Drafts, Experimental or Historical
   RFCs, and non-WG informational documents should not be transmitted
   without developing further consensus within the relevant group, as
   these documents cannot be truthfully represented as any kind of IETF
   position.

##  Requests for Information

   Another type of liaison statement that can be generated without the
   need for extensive consensus building on the email list is a request
   for information.  The (co)chairs(s) can generate such a liaison
   statement when they recognize, from the activities of the group, that
   some additional information is helpful, for example, to resolve an
   impasse (i.e., don't waste time arguing over what the real meaning or
   intent of another SDOs document is, just ask the other SDO and base
   further work on the "official" answer).

   Other requests for information may request access to certain
   documents of other organizations that are not publicly available.

##  Requesting Comments on Work in Progress

   There may be cases when one feels that a document under development
   in the IETF may benefit from the input of experts in another relevant
   SDO, consortium, or forum.  Generally, this is done before the text
   is "fully cooked" so that input from experts in another organization
   can be included in the final result.  Comments would generally be
   solicited for a standards track WG Internet Draft and some level of
   consensus should be reached on the WG or other open mailing list that
   it is appropriate to ask another organization for comments on an IETF
   draft.

##  Requests for Other Actions (Besides Comments on IETF Drafts)

   There are many other kinds of actions that might reasonably be
   requested of another organization:

   o  In the case of overlapping or related work in another
      organization, a request could be made that the other organization
      change something to align with the IETF work.

   o  A request could be made for another organization to start a new
      work item (on behalf of IETF).

   o  A request could be made for another organization to stop a work
      item (presumably because it overlaps or conflicts with other work
      in the IETF).

   These kinds of requests are quite serious.  They can certainly be
   made when appropriate, but should only be made when there is the
   clearest possible consensus within the particular WG, Area, or within
   the IETF at large.

#  Responding to Incoming Liaison Statements


   Any incoming liaison statement that indicates that it is for
   "Action" expects a response by the deadline.
   It is the responsibility of the (co)chair(s) of
   the addressed group to ensure that a response is generated by
   the deadline if a respone is intended.

   If no response to an incoming liaison statement is provided, this
   does not imply agreement or consensus on the topic raised to
   the IETF. IETF positions require community rough consensus
   via processes managed by the Internet Engineering Steering Group (IESG).

##  Responding to Requests for Information

   If another organization requests information that can be found in an
   IETF document, this can be
   transmitted by the (co)chair(s) of the addressed group, indicating
   the level of agreement for the relevant document, as also discussed
   in {{transmit-docs}}.

## Responding to Requests for Comments

   If an incoming liaison statement requests comments on a document from
   another organization, a discussion will occur on the mailing list
   where participants can provide their comments.

   If a clear consensus is evident from the pattern of comments made to
   the mailing list, the (co)chair(s) can summarize the conclusions in a
   reply liaison statement back to the originating organization.

   If no clear consensus is evident from the pattern of comments on the
   mailing list, or if there is no further discussion, a response is
   still anticipated to the originator.  A summary of the email comments, or
   lack of interest in the issue, can be created and sent to the
   originator, and represented as "collected comments" rather than a
   consensus of the IETF group to which the liaison statement was
   addressed.  It is possible to send this kind of a reply even if some
   of the comments are contradictory.

##  Responding to Request for Action

A request for Action is a fairly serious thing.  Examples of the
kinds of actions that may be expected are:

- In the case of overlapping or related work in another
  organization, another organization may request that the IETF align
  its work with that of the other organization.
- A request could be made for IETF to undertake a new work item.
- A request could be made for IETF to stop a work item (presumably
   because it overlaps or conflicts with other work in the
  originating organization).

Consensus of the receiving group within IETF is clearly necessary to
fulfill the request.  Fulfilling the request may require a great deal
of time and multiple steps, for example, if initiating or stopping a
work item requires a charter change.

There is, of course, no requirement that IETF perform the action that
was requested.  But the request should always be taken seriously, and
generally a response is anticipated.  The originating organization should always be
informed of what, if anything, the IETF has decided to do in response
to the request.  If the IETF decides not to honor the request, or to
honor it with modifications, the response should include the reasons
and, if applicable, the alternate course of action.

For tasks that require a great deal of time, it may be necessary that
several liaison statements be sent back to the originating
organization to report the status of the work and the anticipated
completion time.  The first of these liaison statements should be
generated by the deadline indicated in the incoming liaison
statement.

# Approval and Transmission of Liaison Statements

It is important that appropriate leadership review be made of
proposed IETF liaison statements and that those writing such
statements, who claim to be speaking on behalf of a group in the IETF, are truly
representing IETF views.

For a liaison statement generated on behalf of an IETF WG, the WG
chair(s) must create a statement based on appropriate discussions
within the WG to ensure working group consensus for the position(s)
presented.  The chair(s) must have generated or must agree with the
sending of the liaison statement, and must advise the AD(s) that the
liaison statement has been sent by copying the appropriate ADs on the
message.

For a liaison statement generated on behalf of an IETF Area, the
AD(s) must have generated or must agree with the sending of the
liaison statement.  If the liaison statement is not sent by the ADs,
then their agreement must be obtained in advance and confirmed by
copying the ADs on the message.

For a liaison statement generated on behalf of the IETF as a whole,
the IETF Chair must have generated or must agree with the sending of
the liaison statement.  If the liaison statement is not sent by the
IETF Chair, then his or her agreement must be obtained in advance and
confirmed by copying the IETF Chair on the message.

For a liaison statement generated by the IAB, the IAB Chair must have
generated or must agree with the sending of the liaison statement.
If the liaison statement is not sent by the IAB Chair, then his or
her agreement must be obtained in advance and confirmed by copying
the IAB Chair on the message.

In cases where prior agreement was not obtained as outlined above,
and the designated authority (AD, IETF Chair, or IAB Chair) in fact
does not agree with the message, the designated authority will work
with the liaison manager or IAB to follow up as appropriate, including
emitting a revised liaison statement if necessary.  Clearly, this is
a situation best avoided by assuring appropriate agreement in advance
of sending the liaison message.


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
   able to accept liaison statements whether or not a liaison
   relationship exists, so authentication of submitters is not an
   effective control.


# IANA Considerations

This document has no IANA actions.

# Acknowledgments
{:numbered="false"}

{{RFC4053}} was authored by Stephen Trowbridge, Scott Bradner, Fred Baker.
The text in RFC4053 further has been prompted by discussions with numerous individuals
within IETF and other SDOs and fora, including Gary Fishman and Bert
Wijnen.  It has been developed in cooperation with {{RFC4052}}, which
is to say with the express cooperation of the chair of the IAB at that time,
Leslie Daigle.

This document contain parts of text from {{RFC4053}}, however, all tooling
details were removed and the remaining text will be reworked step by step with
the goal to end up with a shorter and clear document that outlines requirements
and gives high-level guidance to people sending and receiving liaison statements.

--- back
