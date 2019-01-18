---
layout: default
section: "Country Settings and Content"
title: Syncing Media Contacts and Authors
---

Author and Contact information is manually synced from the UNInfo API. A sync can be performed on the Authors and Media Contacts page (`/admin/content/authors`)

{% include media.html
   image_path="assets/images/migrate-authors.jpg"
%}

After performing the sync, data from the UNInfo API will be displayed on the same page and those people will be available as media contacts and authors on various content types.

## Manually Adding an Author or Media Contact

A content editor can create and author or media contact who does not exist in the API by clicking "Add Author on this page"

## Editing an Author or Media Contact

Authors and Contacts can be edited to change or add information (such a picture). Any details that are edited may be overwritten by the next sync (if there is updated or different information in the API)

## Designating Author or Media Contact for Display

Authors and Contacts can be displayed on "Our Team" or "Media Contact" pages by checking the appropriate checkbox on the AUTHOR TYPE field.

{% include media.html
   image_path="assets/images/author-type.jpg"
   class="half"
%}
