::

  This work is licensed under a Creative Commons Attribution 3.0
  Unported License.
  http://creativecommons.org/licenses/by/3.0/legalcode

.. _`tag-tc-approved-release`:

=====================
 tc-approved-release
=====================

.. NOTE(dhellmann): I don't especially like the name of this tag, but
   I decided its use would be more easily communicated if we stuck
   with the designation from the bylaws rather than making up a
   different name.

This tag is used to indicate the projects the TC recommends to the
OpenStack Foundation Board as candidates for trademark use under the
OpenStack Foundation trademark policy.


Application to current projects
===============================

.. tagged-projects:: tc-approved-release


Rationale
=========

The "OpenStack TC Approved Release" is used as the superset of
projects used by the OpenStack Foundation when creating commercial
trademark programs. A commercial trademark program would not be able
to have any requirements for code or functionality outside of what is
included in this group. The foundation may choose to create trademark
programs only related to a subset of the projects.

The projects included in this group should generally represent the
most mature OpenStack projects. OpenStack Foundation commercial
trademark programs use criteria developed by the DefCore subcommittee
of the Foundation board of directors. This criteria is partially based
on a set of capabilities provided by OpenStack Projects. The
capabilities adopted by DefCore are ones that are mature, well
adopted, and not expected to change in the near future.

This tag is applied to projects the TC considers suitable to be
included in the set of "Trademark Designated OpenStack Software" as
defined in the Foundation bylaws. Applying the tag is an indication
that the TC is including the project in the "OpenStack TC Approved
Release", following the guidelines laid out in sections 4.1 and 4.13
of `the OpenStack Foundation Bylaws`_.

.. _the OpenStack Foundation Bylaws: http://www.openstack.org/legal/bylaws-of-the-openstack-foundation

Requirements
============

A project that receives the "tc-approved-release" tag should at a
minimum meet the following requirements:

* The TC approves the request for the tag to be applied to a project.

*Additional criteria for applying this tag will be worked out at a
future date.*

Tag application process
=======================

The sole purpose of this tag is defining the pool of projects that
could be used for the OpenStack Trademark program. It is the role of
the Board (as well as working groups like DefCore) to best understand
the demand for the commercial trademark by OpenStack users and
vendors.

As such changes to this tag are expected to come from the DefCore
committee based on their judgment that that the marketplace has
evolved and a new set of projects should be listed. They should
propose adding or removing this tag to a project by proposing a change
to the openstack/governance repository. The change is reviewed by the
Technical Committee and approved using standard resolution approval
rules, including discussion at at least one Technical Committee public
IRC meeting.



Deprecation
===========

Deprecation of the use of this tag is governed by the bylaws, the
trademark policy set out by the board, and the procedures the Board
and TC have agreed to follow for communicating changes to the
"Trademark Designated OpenStack Software".

.. note::

   We need a reference to that agreement, when we have it. We also
   need a reference to the deprecation policy the Board adopts, since
   that will influence our policy by at least setting a minimum.
