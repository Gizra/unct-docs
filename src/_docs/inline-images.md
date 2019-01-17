---
layout: default
section: "Media Handling"
title: "Selecting Inline Images"
---

## Inline Image Types

You can insert two types of images inline into any body text area of the site:

- **Full screen:** image will appear across the whole screen and should be high resolution (at least 1200px width) and will appear best if very landscape oriented.

- **Regular image:** image will fit within the text container - should be at least 800px width and can accommodate either landscape or portrait orientation.


## How To

To insert inline images:

- Click on the image button.

{% include media.html
   image_path="assets/images/image-button.jpg"
   class="half"
%}

- Choose to select an existing image or upload a new image

{% include media.html
   image_path="assets/images/select-media.jpg"
   class="half"
%}

- If selecting an existing image, click on the image, scroll to the bottom, and click "Select image." If uploading a new image, use the select dialogue or drag and drop an image into the field.

- If uploading a new image, you must provide a name (by which the image will be identified in the media system) and can optionally provide:
  - an alternative title (for accessibility)
  - a caption - to appear under the image
  - a copyright - to identify the photographer or copyright holder.
  - a revision log message - to describe the media in any way (not presented on screen).

- After uploading the image or selecting an existing image, you have the option to choose the display type (full screen or regular image) and to override the existing caption.

{% include media.html
   image_path="assets/images/embed-media.jpg"
   class="half"
%}

## Full-Width Image

{% include media.html
   image_path="assets/images/full-width-image.jpg"
%}

## Regular Image

{% include media.html
   image_path="assets/images/regular-image.jpg"
%}
