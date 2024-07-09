---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: Student Projects
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
  - name: All
    tag: '*'
  - name: Technical
    tag: Technical
  - name: Clinical
    tag: Clinical
  - name: Radiomics
    tag: Radiomics
  - name: Pathomics
    tag: Pathomics
  - name: AutoML
    tag: AutoML

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 2

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---

We work on various clinical applications with different clinicians, and thus also various technical solutions within medical image analysis & AI. Hence, there are usually too many projects to describe here: Currently, we do not have any predefined projects available, but feel free to contact me for more information if you are interested in an internship / thesis! For an overview of some past projects, please see https://bigr.nl/open-projects/.
