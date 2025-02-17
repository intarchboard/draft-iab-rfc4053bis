---
title: "Procedures for Handling Liaison Statements to and from the IETF"
abbrev: "Handling of Liaison Statements"
category: info

docname: draft-kuehlewind-iab-rfc4053bis-latest
submissiontype: IAB
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

normative:

informative:


--- abstract

This document describes the procedure for generating and handling
liaison statements between the IETF and other SDOs, so that IETF can
effectively collaborate with other organizations in the international
standards community.


--- middle

# Introduction

This document describes the procedure for generating and handling

Liaison statements between the IETF and other SDOs, so that IETF can
effectively collaborate with other organizations in the international
standards community.

Exchange of liaison statements does not require a formal liaison
relationship (see {{?RFC4052}}).  The procedures described in this
document encompass all liaisons statements received from SDOs,
whether or not a formal liaison arrangement is in place between the
SDO and the IETF. Receive of a liaison statement does not automatically
impose an obligation of sending a response by the other party. The decision
to send a response depends on the content and kind of request. However,
if a formal liaions relationship exists it is the responsibility
of the liaison manager to ensure appropriate communication
between the organisations (see {{Section 3 of RFC4052}}) even if no response is sent.

   The implementation of the procedure and supporting tools is occurring
   in a minimum of three phases.  The initial phase has been the
   development of a prototype (in the best tradition of "rough consensus
   and running code"), by Sunny Lee of Foretec, in parallel with the
   development of this specification.  The second phase is the
   conversion of that prototype to an operational tool.  This
   operational tool lacks an automated tracking tool; rather, the
   liaison manager implements it in his or her own way.  The third phase
   will include that tracking tool.

   The specific supporting tools and their functionality described in
   this document are one possible way of providing automated support for
   the processes described in this document.  Because specific tools and
   their functionality will change over time, the descriptions in this
   document are to be considered examples only and are not a normative
   part of this specification.

# Liaison Statements and Their Handling

   Let us first define what a liaison statement is (and is not), and set
   reasonable expectations.  The expectations in this section are
   normative for a liaison statement sent by any SDO to the IETF.

##  Definitions

For purposes of clarity, we use the following definitions:

Addressee:
: The Working Group(s) (WG) or other party(s) in the IETF to
      whom a liaison statement is addressed.

Assignee:
: The person responsible to act on a liaison statement,
      initially either the person to whom it was addressed or the chair
      of the group to which it was addressed.  The task may be
      reassigned to another person in the same or a different group as
      appropriate.

Liaison manager:
: A person designated to act as a manager of the
      relationship between the IETF and a peer organization to ensure
      that communication is maintained, is productive, and is timely, as
      defined by sections 2.2 and 3 in {{RFC4052}}.

Liaison statement:
: A letter as described in this document, exchanged
      between organizations.

##  Liaison Statements

A Liaison Statement is a business letter sent by one standards
organization to another.  These organizations may be at any level
(WG, Area, etc.)   Generally, the sender and receiver are peer
organizations.  A liaison statement may have any purpose, but
generally the purpose is to solicit information, make a comment or
request an action.

###  Contents of a Liaison Statement

Liaison statements may be very formal or informal, depending on the
rules of the body generating them.  Any liaison statement, however,
will always contain certain information, much as an business letter
does.  This information will include the following:

####  Contact Information

The following contact information are expected to part of a liaison statement:

From:
: The statement will indicate from what body it originates; for
   example, it may be from, an IETF WG or Area, an ITU-T Study Group,
   Working Party, or Question, etc.  In this document, this body is the
   "sender". A statement may be sent from more than one group, e.g. multiple IETF
   working groups, but usually all groups are from the same organisation.

From-Contact:
: One or more electronic mail addresses belong to the "From" body to which any
   response should be sent. This includes the addresses associated with the "From" group(s),
   e.g. in the IETF these are the working group chair, working mailing list, and Area Director(s), and
   contacts that are required for the management of the liaison, like the
   liaison manager if existant and/or an IAB liaison contact in case of statements sent by
   the IETF or the staff person from the external organisation that has sent the incoming
   liaison by mail, as well as any additional technical experts that should be informed.
   This is often also called the "Response Contact".

To:
: The statement will indicate to which body it is.  In this document,
   this body is the "addressee". A statement may be sent to multiple bodies or
   groups within one body.

To-Contact:
: One or more electronic mail addresses from the receiving body to which this
   statement should be sent. Similar as the "From-Contact" this includes addresses
   associated with the "To" information, contacts that are required for liaison management,
   as well as any additional experts.

In addition an explicit "Send Reply To" address may be provided that is used for processing
the liaison statement. This address is usually not a personal address but rather a generic
address associated to a role. If such a "Send Reply To" address is provided the expectation is that a statement
send in reply will only be send to this address from the respective organisation and will then be distributed
accordingly internally in the receiving organisation by that person.

For liaison statements sent by the IETF, this address should be the alias
of the liaison manager, if applicable, or an address maintained by the IAB for liaison
management such as liaison-coordination@iab.org. Having these more central contact points to
send liaison statements to, helps to ensure that all statements get recorded correctly and
are addressed to the appropriate groups. Note that when the liaison statement gets recorded,
still all addresses in the "From-Contact" should be notified to acknowledge the recording.

For statements send from other organisations
there is usually also such an generic address or the person from the sending organisation
who sent out the email to someone within the IETF may be listed here. If that person is, however,
already listed in the "From Contacts" part, this information can also be omitted for incoming statements.

#### Purpose:

A liaison statement generally has one of three purposes and will
clearly state its purpose using one of the following labels:

For Information:
: The liaison statement is to inform the addressee of
      something and expects no response. This includes calls for review
      comments if the expected response is optional.

For Action:
: The liaison statement requests that the addressee do
      something on the sender's behalf, usually within a stated time
      frame. This is also used if a document is sent out for comment and
      the review feedback is expected in the stated time frame.

In Response:
: The liaison statement includes a response to a liaison
      statement from the peer organization on one or more of its
      documents and expects no further response.

Liaison statements that request action indicate a deadline when
the action is required.  If the addressee cannot
accomplish the request within the stated period, courtesy calls for a
response offering a more doable deadline or an alternative course of
action.

#### Liaison Content, Title, and Attachments

As with any business letter, the liaison statement contains
appropriate content explaining the issues or questions at hand.

Usually the statement will contain a short (usually single line) title
providing a statement of its context and content.

Attachments, if enclosed, may be in the form of documents sent with
the liaison statement or may be URLs to similar documents including
Internet Drafts.

IETF participants use a wide variety of systems, thus document
formats that are not universally readable are problematic.  As a
result, documents enclosed with the body or attachments should be in
PDF, W3C HTML (without proprietary extensions), or ASCII text format.
If they were originally in a proprietary format such as Microsoft
Word, the file may be sent, but should be accompanied by a generally
readable file.

Different organisation have different requirements on the format of
liaison statement. There are no requirements from the IETF on the format
of the actual content of the liaison statement, however, we require
the metadata (address information and purpose) as indicated in the previous
section to be recorded. As such when receiving statement from other organisation
these metadata should be extracted and recorded. However if content of the
statement is not sent in plain text, the plain text content record field may
be empty and the received laision statement is uploaded as attachement.

For statement sent from the IETF it is recommended to provide the content
in plain text but also provide an attachement following the formating requirements
of the receiving organisation if possible. If cases where we have a
liaison manager, it is the responsiblity of the liaison to check or convert
the formating requirements. It is further recommended to convert received
document in proprietary formats into PDF and upload both version as
attachments.

This ensures that our process can comply with all formating requirements
from other organisations.

##  Addressee Responsibilities

   The responsibilities of the addressee of a liaison statement are the
   same as the responsibilities of any business letter.  A liaison
   statement calls for appropriate consideration of its contents, and if
   a reply is requested and an appropriate relationship exists, a
   courteous authoritative reply within the expected time frame.  The
   reply may be that the information was useful or not useful, that the
   requested action has been accomplished, it will be accomplished by a
   specified date, it will not be done for a specific reason, an answer
   to a question posed, or any other appropriate reply.

   A liaison statement, like any other temporary document, must be
   considered for its relevance, importance, and urgency.

   One hopes that a liaison statement will be sent to the right
   organization, but this cannot be assured.  An SDO might send a
   liaison statement to a specific IETF Area whose Area Director (AD)
   deems it better handled by one of the WGs, or it might be sent to one
   WG when it should have gone to another.  If a liaison statement
   arrives that appears misdirected, the assignee should promptly ask
   the liaison manager to redirect it appropriately.  In some cases, a
   liaison statement may require consideration by multiple groups within
   the IETF; in such cases, one assignee takes the lead and
   responsibility for developing a response.

   Liaison Statements are always important to the body that sent them.
   Having arrived at the appropriate body, the liaison statement may be
   more or less important to the addressee depending on its contents and
   the expertise of the sender.  If the liaison statement seeks to
   influence the direction of a WG's development, it should receive the
   same consideration that any temporary document receives.  The WG
   chair may request the sender's contacts to make their case to the
   IETF WG in the same manner that an author of an internet draft makes
   his or her case.

   The urgency of a liaison statement is usually reflected in its
   deadline.  A liaison statement for informational purposes may have no
   deadline; in such a case, a courteous "thank you" liaison statement
   is necessary to inform the sender that the liaison statement was
   received.  The WG may then inform itself of the contents and close
   the document.  A liaison statement specifying a deadline, however,
   gives the addressee a finite opportunity to influence the activity of
   another body; if it fails to react in a timely fashion, it may miss
   the opportunity.

##  Lifetime of a Liaison Statement

   A liaison statement is a temporary document, much like an internet
   draft.  If it affects IETF output, the normal expectation is that the
   resulting RFC will contain relevant information that remains
   pertinent.  Retaining liaison statements that have been completely
   dealt with mostly serves to hide new ones and create the appearance
   of not dealing with them.

   However, unlike an internet draft, liaison statements are often the
   only record the IETF has of the communication with the peer SDO.  As
   such, some liaison statements are referred to for relatively long
   periods of time.

   As a result, the IETF will archive liaison statements that have been
   fully dealt with, along with any attachments that may have been
   relevant, but do so in a manner obviously distinct from current
   liaison statements.

#  Tools for Handling Liaison Statements

   Some tools have been developed for the IETF.  Development is expected
   to continue.  This section describes the basic tool and its intended
   use.

##  Liaison Statements from Other SDOs, Consortia, and Fora to IETF

   The process of handling a liaison statement is more weighty than
   handling a business letter because it is important to a relationship
   with another SDO established by the IAB.  To manage liaison
   statements, the IETF will offer three electronically accessible
   facilities: a form for submission of liaison statements, a mechanism
   organizing their contents and making them accessible, and a tracking
   system.  Initially, the tracking system will be a manual procedure
   used by the liaison manager; in the future, this should be automated.

###  Liaison Statement Submission

   The IETF Secretariat will provide an electronic method for submission
   of liaison statements.

   The liaison statement submission mechanism is a form that requests
   the information listed in Section 2.2.1 from the user.

   Submission of that information results in the following actions:

   o  creation of a display mechanism containing the envelope data in
      Section 2.2.1.1 and URLs pointing to the items from
      Section 2.2.1.2, an indication whether the liaison statement has
      been replied to, and if so, on what date,

   o  the addition of a URL to the "outstanding liaison statements"
      summary mechanism,

   o  when an automated tracking system has been implemented, a tickler/
      status entry in the tracking system, assigned to the relevant
      chair or AD,

   o  an email to the assignee copying

      *  the liaison statement's technical contacts

      *  The supervisor of the assignee (if it is to a WG, the relevant
         ADs; if to an AD, the IETF Chair),

      *  The liaison manager for the sending SDO,

      *  an alias associated with the assignee (WG/BOF or other open
         mailing list, Area Directorate, IESG, IAB, etc.)

      This email should contain the URL to the liaison statement
      mechanism, text indicating that the liaison statement has arrived,
      requests appropriate consideration, and if a deadline is
      specified, a reply by the deadline.

   The assignee has the capability of interacting with the liaison
   manager and the tracking system (once implemented), including
   replying, changing dates, reassignment, closing the liaison statement
   process, etc.

   The liaison manager or tracking system's "tickle" function
   periodically reminds the assignee by email that the liaison statement
   has not yet been closed.  This tickle email copies all of the above
   except the associated mailing alias.

###  Mechanism for Displaying Liaison Statements

   The IETF site contains a section for current liaison statement
   activity.  This consists of:

   o  A submission mechanism,

   o  A status/management mechanism for each active or recently closed
      liaison statement, and zero or more associated files.

   The status/management mechanism contains a simple frame, showing the
   title of the liaison statement, the URL for its mechanism, and the
   organizations it is from and to.

   The display for liaison statement itself contains:

   o  the liaison statement envelope information (Section 2.2.1),

   o  direct content (Section 2.2.1),

   o  URLs for the various associated files

   o  current status of the liaison statement: to whom it is assigned,
      its due date, and its status,

   o  pointer to the liaison manager and tracking system entry for the
      liaison statement.

   o  reply-generation mechanism (see Section 3.2.2.4)

##  Communicating IETF Information to Other SDOs, Consortia, and Fora

   This includes liaison statements sent in reply to liaison statements
   sent by other bodies, and liaison statements being originated by the
   IETF.

###  Spontaneously Generating Liaison Statements to Other Organizations

   Liaison Statements can be generated at a WG, Area, or IETF level to
   another organization.  The respective (co)chair(s) are responsible
   for judging the degree of consensus for sending the particular
   liaison statement and deciding the content.  The amount of consensus
   required to send a liaison statement varies greatly depending on its
   content.  This section gives some rough guidance about how much
   consensus should be sought before sending a liaison statement to
   another organization.

####  Transmitting IETF Documents to Other Organizations

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

####  Requests for Information

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

####  Requesting Comments on Work in Progress

   There may be cases when one feels that a document under development
   in the IETF may benefit from the input of experts in another relevant
   SDO, consortium, or forum.  Generally, this is done before the text
   is "fully cooked" so that input from experts in another organization
   can be included in the final result.  Comments would generally be
   solicited for a standards track WG Internet Draft and some level of
   consensus should be reached on the WG or other open mailing list that
   it is appropriate to ask another organization for comments on an IETF
   draft.

####  Requests for Other Actions (Besides Comments on IETF Drafts)

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

###  Responding to Incoming Liaison Statements

   Any incoming liaison statement that indicates that it is for
   "Comment" or for "Action" requires a response by the deadline.
   It is the responsibility of the (co)chair(s) of
   the addressed organization to ensure that a response is generated by
   the deadline if a respone is intended.

####  Responding to Requests for Information

   If another organization requests information that can be found in an
   IETF document of the types indicated in Section 3.2.1.1, this can be
   transmitted by the (co)chair(s) of the addressed group, indicating
   the level of agreement for the relevant document.

#### Responding to Requests for Comments

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

####  Responding to Request for Action

   A request for Action is a fairly serious thing.  Examples of the
   kinds of actions that may be expected are:

   o  In the case of overlapping or related work in another
      organization, another organization may request that the IETF align
      its work with that of the other organization.

   o  A request could be made for IETF to undertake a new work item.

   o  A request could be made for IETF to stop a work item (presumably
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

####  Generating Liaison Statements

   IETF participants, usually WG chairs, ADs, or other officials, need
   to be able to send liaison statements to other SDOs.  The mechanism
   described in Section 3.1.2, listing appropriate contacts in other
   SDOs with which the IAB has established liaison relationships,
   provides that capability.

   As a convenience, the liaison statement page described in
   Section 3.1.2 may be used to generate a reply.  If a person (usually
   a WG chair or an AD) selects "reply", a new liaison statement page is
   generated from the existing one, reversing the addressing
   information.  IETF documents should be referenced by URL, such as
   http://www.ietf.org/internet-drafts/>file< or
   ftp://ftp.rfc-editor.org/in-notes/>file<.

   The process of generating and approving transmission of liaison
   statements is a matter of IETF process and is specified in {{RFC4052}}.

# Approval and Transmission of Liaison Statements

It is important that appropriate leadership review be made of
proposed IETF liaison statements and that those writing such
statements, who claim to be speaking on behalf of IETF, are truly
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
with the liaison manager to follow up as appropriate, including
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
   organizations because they feel ignored.

   For this reason the submission process is automated.  While the IETF
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

   This text has been prompted by discussions with numerous individuals
   within IETF and other SDOs and fora, including Gary Fishman and Bert
   Wijnen.  It has been developed in cooperation with {{RFC4052}}, which
   is to say with the express cooperation of the chair of the IAB,
   Leslie Daigle.  Personal experiences and some "miscues" in
   coordinating work across ITU-T Study Group 15 and the IETF Sub-IP
   Area have also motivated this work.  Some drafts addressing
   individual problems (for example, RFC 3427) make it clear that a more
   general, consistent solution is needed for dealing with outside
   organizations.  Certain ideas have been borrowed from these texts.

   Barbara Fuller, Sunny Lee, and Michael Lee developed a prototype and
   commented in detail on the document.  Their inputs directly resulted
   in the appendices describing the implementation road map.

--- back

# Implementation Road Map

   This section documents the development program as of the time of the
   writing of this document.  It is not normative.

## Phase I: Initial Implementation

### Displays

   The descriptions of the required displays in Section 3.1.1 and
   Section 3.1.2 call for two sets of displays: one for the public (for
   viewing liaison statements), and one for submitters (for managing
   liaison statements).

   Displays for public view of liaison statements include:

   o  A Liaison Statements Web page that lists all incoming and outgoing
      liaison statements (specific fields TBD).  The title of each
      liaison statement is a link to the details page for that liaison
      statement.

   o  A detail page for each liaison statement that contains:

      *  All of the information specified in the subsections of
         Section 2.2.1.

      *  Links to all attachments that accompanied the liaison statement
         or to documents that are mentioned in the statement but were
         not provided as part of the submission.

      *  Links to all related liaison statements (e.g., replies).

   Displays for submitting and managing liaison statements include:

   o  A summary page that offers mechanisms for:

      *  Creating and submitting a new liaison statement.

      *  Editing a liaison statement that the user has previously
         created and submitted.

      *  Acting on a liaison statement that has been assigned to the
         user.

   o  A template for creating and submitting a liaison statement.  This
      template allows the user to enter the information specified in
      Section 2.2.1.  The user is able to access the template at any
      time (from a list of liaison statements that the user has
      previously created and submitted), and update and resubmit the
      information.

   o  A detail page for managing a liaison statement assigned to the
      user.  This page is similar to the details page available to the
      public.  However, it also includes:

      *  A mechanism for replying to the liaison statement (initial
         implementation)

      *  A link to a liaison statement tracking mechanism (future
         implementation)

###  Actions on Submission

   Submission of a liaison statement results in the following actions:

   o  The information is uploaded to the database.

   o  An e-mail message with the content specified in Section 3.1.1 is
      sent to the addressee with copies to the addresses specified in
      Section 4.1, and to the Secretariat (as specified in {{RFC4052}}).

   o  The liaison statement is added to the list on the Liaison
      Statements Web page.

   o  Two detail pages are created for the liaison statement: one for
      the public (to view the liaison statement), and one for the sender
      and the assignee (to manage the liaison statement).

   As specified in Section 3.2.2.4, when a user selects reply on the
   details page of a liaison statement, a template for creating and
   submitting a new liaison statement is generated from the existing one
   that copies "From" to "To" and specifies the respondent as the
   individual the response is coming "From".  Submission of this reply
   liaison statement results in the same set of actions as submission of
   any new liaison statement.  In addition, a link to the details page
   of this liaison statement is added to the list of related liaison
   statements on the details pages (both public and management) of the
   original liaison statement (i.e., the one to which the user replied).

# Phase II: Additional Instrumentation and Responses to Usage Experience

   This section is for information, and is not normative.

   The intended features of the future liaison statement tracking system
   are discussed in Section 3.1.  They include mechanisms for:

   o  Designating an assignee; the assignee is initially a person
      associated with the body (IAB, IESG, Area, WG, etc.) to which the
      liaison statement is addressed, but may subsequently be changed by
      an IETF participant.

   o  Indicating the status of the liaison statement (e.g., actions
      required, actions taken, etc.  Specific options TBD).

   o  Sending ticklers to the assignee when action is required (with
      copies to whomever is appropriate).

   o  Changing the status of the liaison statement, the deadline, or
      other attributes.

   o  Reassigning responsibility.

   o  Closing the liaison statement.

