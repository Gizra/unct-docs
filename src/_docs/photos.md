---
layout: default
section: "Creating and Editing Content"
title: Photo Stories
---

Photo Stories populate the **Photo Stories** content of the website and are intended for including Flickr albums from the country team.

## Fields

- **TITLE**: The title of the title of the content which will appear in listings and as the header at the top of the content.

- **FLICKR URL**: The URL of the album to share. This is not the generated social share link for the album, but rather the actual URL from the album page (no trailing slash).


### Correct URL

{% include media.html
   image_path="assets/images/flickr-url-good.jpg"
%}


### Incorrect URL

{% include media.html
   image_path="assets/images/flickr-url-bad.jpg"
%}

- **TEXT INTRO**: A short description of the article which appears along with the title in most listings on the site. This field is limited to plain text and 160 characters.

- **DATE**: The date which the content was authored - this shows on most listings on the site and provides the order (most recent first) of the listings. The field defaults to today's date, but can be changed to a date in the past or future. The pop-up calendar allows you to scroll by month or reset to today's date.

{% include media.html
   image_path="assets/images/calendar.jpg"
   class="half"
%}

- **SAVE AS**: Depending on your role on the site you can save the article as:
  - _Draft_: to indicate that the content it is ready to be reviewed by and editor.
  - _Revised Draft_: to indicate that it has been revised after review.
  - _Published_: to make the content visible to an anonymous visitor of the website.


## Photo Story Detail page

  {% include media.html
     image_path="assets/images/photo-detail.jpg"
  %}

## Photo Stories Listing


Shows the most recent albums.

{% include media.html
   image_path="assets/images/photo-listing.jpg"
%}
