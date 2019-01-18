---
layout: default
section: "Site Admin/Developer Functions"
title: Adding Users to the Site
---

User management is designated to the "Developer" role only and can be accessed at `/admin/people`

## User Fields

A user should be given at the minimum a username and a password, and can also be designated with an email

The Site language should be set to the default language in which the user will publish content, and the timezone should be set to the user's timezone.


## User Roles

There are three roles that are active on the site:

- **Developer**: This role has access to all site settings and actions. It is a high-level privilege and should only be given to highly-trusted individuals. Because it has the ability to set the site domain and unpublish/delete a country team, this role is capable of taking a site offline.

- **Content Editor**: This role is for site admins who are to have all control over content on the site. They can:
    - create, edit, delete and publish content
    - manually sync content (SDGs and Contacts)
    - edit most Country Team settings and set featured and homepage content

- **Content Creator**: This role is for writers of content. They can create and edit their own content and save as drafts (but not publish).

## Adding a User to a Country Team

In order to work with content for a particular country team, a user needs to be added to that team. A user can be part of one or more country teams. Users with the "developer" role have default access to all groups.

Group membership to the country team is controlled on the "Group" tab on the Country Team admin page.

{% include media.html
   image_path="assets/images/country-group.jpg"
%}

From the Group tab, click on "Members", then "Add Members" and add users to the country team group using the dialogue.

{% include media.html
   image_path="assets/images/add-member.jpg"
%}

Users do not need to have a role in the group to be able to view and edit content for the country team.
