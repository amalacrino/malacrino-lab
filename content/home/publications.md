---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: Recent Publications
subtitle: '{{% callout note %}}
This is a list of selected recent papers. Please, {{< staticref "https://scholar.google.com/citations?hl=en&user=_ghEdkYAAAAJ&view_op=list_works&sortby=pubdate" "newtab" >}}visit my Google Scholar profile{{< /staticref >}} for a full list of my publications.
{{% /callout %}}'

content:
  # Filter on criteria
  filters:
    folders:
      - publication
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: false
    exclude_future: false
    exclude_past: false
  # Choose how many pages you would like to display (0 = all pages)
  count: 5
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc
design:
  # Choose a view for the listings:
  view: 4
  columns: '2'
---