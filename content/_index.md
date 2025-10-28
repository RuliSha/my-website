---
# Leave the homepage title empty to use the site title
title: Ariel Shaulker
date: 2025-10-28
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Ariel Shaulker
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: card
#  - block: collection
#    id: talks
#    content:
#      title: Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
  
---
