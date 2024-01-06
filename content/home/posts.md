---
# An instance of the Featured widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: featured

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 60

title: Recent Posts
subtitle: Highlights

content:
  # Page type to display. E.g. post, talk, publication...
  page_type: post
  # Choose how many pages you would like to display (0 = all pages)
  count: 6
  # Filter on criteria
  filters:
    author: ""
    category: ""
    publication_type: ""
    tag: ""
    exclude_featured: false
    exclude_future: false
    exclude_past: false
  # Page order: descending (desc) or ascending (asc) date.
  order: desc
  archive:
    enable: true
    # link: "publicationlist/"
    # text: "bla bla bla"

design:
  # Choose a view for the listings:
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view: 2
---
