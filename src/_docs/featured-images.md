---
layout: default
section: "Media Handling"
title: "Selecting Featured Images"
---

Featured images appear as part of some content types (Articles and Publications) and are used in the listings and on the detail page for the content.

## How To

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

- After uploading the image or selecting an existing image, you can choose the focal point of image by selecting the edit tool:

{% include media.html
   image_path="assets/images/featured-image.jpg"
   class="half"
%}

- And setting the crosshair on the focal point:

{% include media.html
   image_path="assets/images/focal-point.jpg"
   class="half"
%}

The selected image will be cropped according to the content type with the selected focal point at the center.

## Notes
- Featured images have different ratios according to their content type across the site. You should refer to the section of creating/editing content for a particular content type to check the proper ratio.

- Images will be scaled down but not up, so it is important to choose an image size that is at least as big as the dimensions defined in the content type.
