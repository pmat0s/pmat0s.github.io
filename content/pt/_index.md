---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-08-05
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: ../uploads/CV_LATTES_RESUMIDO.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 Um pouco mais sobre mim'
      subtitle: ''
      text: |-
        Pedro Davi Matos Pereira, bacharel (2017), licenciado (2018) e mestre (2021) em Física pela Universidade Federal da Bahia (UFBA), com ênfase em Física Atômica e Molecular. Tem experiência na área de educação, em escolas de ensino ensino médio, profissionalizante, bem como na formação de professores. Realiza pesquisas em Física Atômica e Molecular e Física Matemática, com ênfase em processo de espalhamento de elétrons por Moléculas, Mecânica Quântica no Espaço de Fase, Função de Wigner e Mecânica Quântica Simplética. Também desenvolve pesquisas em instrumentação para o ensino de física. É membro do Grupo de Pesquisa em Ensino de Ciências - Salgueiro. Atualmente é professor de Física no quadro efetivo do Ensino Básico, Técnico e Tecnológico (EBTT) do Instituto Federal de Educação, Ciência e Tecnologia do Sertão Pernambucano (IFSertãoPE) - Campus Salgueiro/PE. Possui interesse em ensino de física, instrumentação didática, arduíno, programação e cultura maker. 
        
        Entre em contato para colaborar 😃.
    design:
      columns: '1'
      spacing:
        padding: ['15px', '15px', '15px', '15px']
  - block: collection
    id: papers
    content:
      title: Publicações em destaque
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 1
  # - block: collection
  #   content:
  #     title: Trabalhos recentes
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation
  - block: collection
    id: talks
    content:
      title: Comunicações recentes
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: news
    content:
      title: Notícias recentes
      subtitle: ''
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
---
