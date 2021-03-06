Product WG: Taxonomy Overview
=============================
The Product Working Group will help the community document requirements, in the form of user stories, for key barriers to adoption based on specific needs of special interests groups (SIGs) that are working as a part of the user committee organization.  While we will also accept user story submissions from individual members, it is highly encouraged that you join a Working Group that shares your interest and submit as a part of the group.  The main reason for encouraging this is because the group may already have plans that align to your needs and, if the user story resonates with the team, they can help it get greater visibility through the working group members.

Here is a list of all of the working groups that exist today, you can visit their wiki page for more information: `https://wiki.openstack.org/wiki/Category:Working_Groups <https://wiki.openstack.org/wiki/Category:Working_Groups>`_


The purpose of this document is to share the taxonomy/hierarchy used by the Product Working Group for generating, categorizing, and tracking user stories.

Agile Terms
-----------
The Product Working Group will follow agile terminology/methodology in a loose sense.  It is therefore important to cover some basic agile terms and process information before describing our manifestation of an agile-like process.  Please also keep in mind that most individuals and organizations tend to have *slightly* different interpretations of the concepts being discussed in this section, therefore do not consider this a definitive guide on themes, epics, user stories, features, etc.

**Theme**: An area of focus (grouping of user stories/epics).  It does not contain significant detail and is associated with a single product.   Normally either theme or epic is the top-level artifact when describing requirements.  A theme can span multiple sprints.

**Epic**: An epic is generally a larger, more broader, user story.  It may be the top level requirements artifact or can be one of many epics under a theme.  An epic will generally span multiple sprints; the user stories that are generated from the decomposed epic are the items that belong within the product backlog or sprint.

**User Story**: A user story can only belong to one epic at a time and can not span sprints.  The user story generally captures what the user wants using a format that captures an actor/role, objective, and benefit/reasoning.  This item is then broken into more-detailed tasks or features that describe the specific work that must be done to deliver the user story.  Most product backlogs prioritized work using user stories as the operational unit of ‘work’

**Feature**:  Feature is used by some as an alternative to user story and as an alternative to task by others.  For our terminology overview, we will consider feature and task as interchangeable terms.  Please see task for additional details.

**Scenario**: A scenario usually expands upon the user story to describes examples how the user story might be be interpreted or how the requirement being described is experienced by the user.  A good scenario can also act a way to validate that the goal of the user story was successfully achieved.

**Task**: A task is a lower-level requirements item that captures a sub-unit, or step, that is necessary to complete a user story.  Tasks are usually generated by the development team working on the user story.

.. image:: https://github.com/openstack/openstack-user-stories/doc/source/images/agile_overview.jpg

Good resources for additional information related to these terms:

`http://www.mountaingoatsoftware.com/blog/stories-epics-and-themes <http://www.mountaingoatsoftware.com/blog/stories-epics-and-themes>`_

`http://www.romanpichler.com/blog/agile-scenarios-and-storyboards <http://www.romanpichler.com/blog/agile-scenarios-and-storyboards>`_

Product WG Mapping
------------------
The Product WG will leverage agile terms to communicate and this section provides additional information on how these terms will be mapped inside the OpenStack community.

**Theme**: Themes will be very high-level categories that are agreed upon by the Product WG and OpenStack Foundation.  Generally, the themes will be areas such as resiliency, availability, performance, scalability, UX, etc.

**Epic**: Epics will be used to build topics within each theme that could be used to aggregate user stories.  For example, in the "availability" theme, we could have an epic for "service processes" and all of the user stories related to making services such as cinder, nova, keystone, etc. "highly available" would fall under this epic.

**User Story**: A user story can only belong to one epic at a time and *can* span sprints.  The user story generally captures what the user wants using a format that captures an persona/role, objective, and benefit/reasoning.  This item is then broken into more-detailed tasks or features that describe the specific work that must be done to deliver the user story.  The Product WG tracker will track user stories.

**Feature**:  Feature is used by some as an alternative to user story and as an alternative to task by others.  For our terminology overview, we will consider feature and task as interchangeable terms.  Please see task for additional details.

**Scenario**: A scenario usually expands upon the user story to describes examples how the user story might be be interpreted or how the requirement being described is experienced by the user.  A good scenario can also act a way to validate that the goal of the user story was successfully achieved.  The Product WG user story template requires an entry for usage scenarios to foster discussion of the user story.

**Task**: A task is a lower-level requirements item that captures a sub-unit, or step, that is necessary to complete a user story.  Tasks are usually generated by the development team working on the user story.  In our case, blueprints/specs that are related to a user story will be considered tasks.
