---
title: Blog
view: landing

design:
  # Default section spacing
  spacing: "6rem"

# Page sections
sections:
  # - block: markdown
  #   content:
  #     title: 'My title'
  #       subtitle: 'My subtitle'
  #       text: 'Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!'
  - block: collection
    content:
        title: 'Postagens'
        text: 'Costumo escrever coisas a sobre física e tecnologia, mas também escrevo algumas coisas aleatórias.'
        filters:
            folders:
            - post
    design:
        view: article-grid
        fill_image: false
        columns: 1
  - block: collection
    id: news
    content:
        title: Postagens
        subtitle: 'Costumo escrever coisas a sobre física e tecnologia, mas também escrevo algumas coisas aleatórias.'
        text: ''
        # Page type to display. E.g. post, talk, publication...
        page_type: post
        # Choose how many pages you would like to display (0 = all pages)
        count: 5
        # Filter on criteria
        filters:
            author: ""
            category: ""
            tag: ""
            exclude_featured: false
            exclude_future: false
            exclude_past: false
            publication_type: ""
        # Choose how many pages you would like to offset by
        offset: 0
        # Page order: descending (desc) or ascending (asc) date.
        order: desc
    design:
        # Choose a layout view
        view: date-title-summary
        # Reduce spacing
        spacing:
            padding: [0, 0, 0, 0]
  # - block: tag_cloud
  #     content:
  #       title: My title
  #       subtitle: My subtitle
  #       text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
  #       # Choose a taxonomy from the `taxonomies` list in `config.yaml` to display (e.g. tags, categories, authors)
  #       taxonomy: tags
  #       # Choose how many tags you would like to display (0 = all tags)
  #       count: 20
  #     design:
  #       # Minimum and maximum font sizes (1.0 = 100%).
  #       font_size_min: 0.7
  #       font_size_max: 2.0
---

