---
layout: default
section: "Creating and Editing Content"
title: Articles
---

Articles populate the **Stories** content of the website and are intended for news from the country team.

## Fields

- **TITLE**: The title of the title of the content which will appear in listings and as the header at the top of the content.

- **TEXT INTRO**: A short description of the article which appears along with the title in most listings on the site. This field is limited to plain text and 160 characters.

- **DATE**: The date which the content was authored - this shows on most listings on the site and provides the order (most recent first) of the listings. The field defaults to today's date, but can be changed to a date in the past or future. The pop-up calendar allows you to scroll by month or reset to today's date.

{% include media.html
   image_path="assets/images/calendar.jpg"
   class="half"
%}

- **FEATURED IMAGE:** This image will be displayed with most site listings and will be the header image (below the title and text intro) on the article page. This image should be landscape oriented and at least 500px wide. You can select an exiting image or upload a new image - for more information see the <a href="/featured-images">"Select a featured Image"</a> entry of the Media section.

- **BODY:** The main body text of the article with no limit on the number of character or words. The body field uses a WYSIWYG editor - for more information see the <a href="/using-wysiwyg">"Using the WYSIWYG Editor"</a> entry of the Creating/Editing Content section. You can also include "inline" images in the body field - for more information see the <a href="/featured-images">"Inserting Inline Images"</a> entry of the Media section.

- **PULLOUT TEXT:** This field is currently not used.

- **WRITTEN BY** This field allows you to indicate which of the site-wide authors and contacts (up to 5) can be assigned as the author of the article. It is shown on the article detail page only. This field is intended to be the original author of the content, not the content creator adding it to the CMS.

- **GOALS WE ARE SUPPORTING THROUGH THIS INITIATIVE:** You can choose the Sustainable Development Goals that are relevant to this article - as many as are relevant - using the checkboxes.

- **UN AGENCIES INVOLVED IN THIS INITIATIVE:** You can choose the UN Agencies that are relevant to this article - as many as are relevant - using the checkboxes.

- **SAVE AS**: Depending on your role on the site you can save the article as:
  - _Draft_: to indicate that the content it is ready to be reviewed by and editor.
  - _Revised Draft_: to indicate that it has been revised after review.
  - _Published_: to make the content visible to an anonymous visitor of the website.

## Article Detail page

  {% include media.html
     image_path="assets/images/article-detail.jpg"
  %}

## Article Listings

### Article Listing on the Stories Page

Shows three articles from the most recent.

{% include media.html
   image_path="assets/images/article-listing.jpg"
%}

### Article Listing on the Homepage
Shows four articles from the most recent - the first two in "full teaser" mode and the second two with title and date only.

{% include media.html
   image_path="assets/images/article-listing-homepage.jpg"
%}

### Article Listing for Related Stories
At the bottom of the Article detail page, shows three articles from the most recent that are related to the currently viewed article by Goals Supported.

{% include media.html
   image_path="assets/images/article-listing-homepage.jpg"
%}
