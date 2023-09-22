# Name of website
title: What is Your Goal?

# Your name to show in the footer
author: Dr. Kristen Boucher

# --- List of links in the navigation bar --- #

navbar-links:
  About Me: "aboutme"
  Resources:
    - Beautiful Jekyll: "https://beautifuljekyll.com"
    - Learn markdown: "https://www.markdowntutorial.com/"
  Author's home: "https://deanattali.com"

# --- Logo --- #

# Image to show in the navigation bar - works best with a square image
# Remove this parameter if you don't want an image in the navbar
avatar: "/assets/img/AED3E57B-5CD4-44B6-A250-5522590FB252.jpeg"

# By default, the image is cut into a circle. You can disable this behaviour by setting 'round-avatar: false'
round-avatar: false

# If you want to have an image logo in the top-left corner instead of having the title of the website,
# then specify the following parameter
#title-img: /path/to/image


# --- Footer social media links --- #

# Select the social network links that you want to show in the footer.
# Uncomment the links you want to show and add your information to each one.
social-network-links:
  email: "dr.kristen.boucher@gmail.com"
  facebook: "https://www.facebook.com/NVNGNutrition"
#  telephone: +13153734346
#  ORCID: your ORCID ID

# If you want to show a link to an RSS in the footer, add the site description here.
# If you don't want to show an RSS link, remove the following line.
rss-description: This website is dedicated to helping individuals obtain a healthy lifestyle

# --- General options --- #

# Select which social network share links to show in posts
share-links-active:
  twitter: false
  facebook: true
  linkedin: false
  vk: false

# How to display the link to your website in the footer
# Remove this if you don't want a link in the footer

# Excerpt word length - Truncate the excerpt of each post on the feed page to the specified number of words
excerpt_length: 50

# Whether or not to show an excerpt for every blog post in the feed page
feed_show_excerpt: true

# Whether or not to show a list of tags below each post preview in the feed page
feed_show_tags: true

# Add a search button to the navbar
post_search: true

# The keywords to associate with your website, for SEO purposes
#keywords: "health, nutrition, consulting, weight loss, healthy, lifestyle, diet, therapy, chiropractic, chiropractor"

# --- Colours / background image --- #

# Personalize the colours in your website. Colour values can be any valid CSS colour

navbar-col: "#FF7F50"
navbar-text-col: "#FFF8DC"
navbar-border-col: "#FFF8DC"
page-col: "#7FFFD4"
text-col: "#F0FFFF"
link-col: "#A9A9A9"
hover-col: "#A9A9A9"
footer-col: "#FF7F50"
footer-text-col: "#FFF8DC"
footer-link-col: "#A9A9A9"


# Suggest a colour for mobile browsers to use as the browser's theme. This is only supported by a few mobile browsers.
mobile-theme-col: "#7FFFD4"

# --- Misc --- #

# Ruby Date Format to show dates of posts
date_format: "%B %-d, %Y"

# Facebook App ID
#fb_app_id: ""

# --- You don't need to touch anything below here (but you can if you want) --- #

# Output options (more information on Jekyll's site)
timezone: "America/Toronto"
markdown: kramdown
highlighter: rouge
permalink: /:year-:month-:day-:title/
paginate: 5

kramdown:
  input: GFM

# Default YAML values (more information on Jekyll's site)
defaults:
  -
    scope:
      path: ""
      type: "posts"
    values:
      layout: "post"
      comments: true  # add comments to all blog posts
      social-share: true # add social media sharing buttons to all blog posts
  -
    scope:
      path: "" # any file that's not a post will be a "page" layout by default
    values:
      layout: "page"

# Exclude these files from production site
exclude:
  - CHANGELOG.md
  - CNAME
  - Gemfile
  - Gemfile.lock
  - LICENSE
  - README.md
  - screenshot.png
  - docs/

plugins:
  - jekyll-paginate
  - jekyll-sitemap

# Beautiful Jekyll / Dean Attali
# 2fc73a3a967e97599c9763d05e564189
