# Nina Carducci - Photographer Website Optimization

## Overview

This project focuses on optimizing the website for Nina Carducci (https://jju87.github.io/Carducci-OpenClassroomss/), a photographer, to enhance both performance and SEO. The optimizations include image compression, script and library optimizations, accessibility improvements, and additional features requested by the client.

## Before and After Comparison

### Lighthouse Scores

- **Before Optimization:**
  - Mobile: https://drive.google.com/file/d/1kg8Jd6PB-HmfpQMgBQxJhqPTVgyiWUdm/view?usp=sharing

- **After Optimization:**
  - Mobile: https://drive.google.com/file/d/1VvaAL6mjRNLmk15k71WZgcgWtcVOsnlH/view?usp=sharing
  - Desktop: https://drive.google.com/file/d/1P2NLdyRdvkiSvOfq7mjZHecP46y2GyPT/view?usp=sharing

## Optimization Details

### 1. Images

- Resized and converted images to WebP format.
- Implemented Content Delivery Network (CDN) for specific images.
- Significantly reduced total image weight, improving Largest Contentful Paint (LCP) in mobile view.

### 2. Bootstrap/Jquery

- Replaced local scripts with CDN-hosted versions to enhance loading speed.

### 3. Scripts

- Moved scripts to the end of the page for faster perceived loading time.
- Minified CSS and JavaScript files for reduced file size.

### 4. Accessibility

- Added title tag for SEO focus.
- Specified language in HTML tag.
- Added "alt" attributes for images, including the Instagram logo/link.
- Improved heading structure and added semantic HTML tags.
- Corrected contrast issues.

### 5. Additional Client Requests

#### SEO Optimization

- Researched relevant keywords for SEO using KWFinder.
- Prioritized long-tail and local keywords.
- Optimized meta description and integrated Schema.org tags for rich snippets.
- Enhanced Google Rich Snippet with business information and pricing.

#### Social Media Integration

- Added metadata for Twitter Cards and Open Graph.
- Improved appearance of links when shared on social media platforms.
- Tested and previewed metadata on various platforms.

## Bug Fixes

- Fixed navigation issues in the gallery modal.
  - Previous and next image buttons now work as expected.
- Improved visibility of selected image filter in the gallery.

## View on gh-pages

https://jju87.github.io/Carducci-OpenClassroomss/
