---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Xueyue Liu (刘学悦)
      image:
        filename: back.png
      cta:
        label: '**CV**'
        url: https://econ.fudan.edu.cn/info/1028/17978.htm
      cta_alt:
        label: Contact me
        url: mailto:allenxyliu@gmail.com
      text: |-
        **Assistant Professor**
    
        **School of Economics, Fudan University**
    
        Research Interests: Innovation, Energy and Environmental Economics, Economics of Gender (I mainly use all kinds of firm- and individual-level data in China)
    
        Office Address: Room 310, Building  #11, 220 Handan Road, Shanghai, China
    
        Email: liuxueyue@fudan.edu.cn
        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#2C2C2C'
        gradient_start: '#7A7A7A' 
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: Stata
          description: 90%
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Python
          description: 60%
          icon: python
          icon_pack: fab
  
  
  
  - block: collection
    id: pub
    content:
      title: Publications
      filters:
        folders:
          - publication/journal-article
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
    design:
      columns: '2'
      view: citation
    
  - block: collection
    content:
      title: Working Papers
      filters:
        folders:
          - publication/preprint
    design:
      columns: '2'
      view: citation

  - block: accomplishments
    id: teaching
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Teaching'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_end: ''
          date_start: '2018-09-01'
          description: ''
          organization: Undergraduate level
          title: Industrial Economics
        - date_end: ''
          date_start: '2018-09-01'
          description: ''
          organization: Undergraduate level
          title: Development Economics
        - date_end: ''
          date_start: '2018-09-01'
          description: ''
          organization: Undergraduate level
          title: Softwares for Economic Analysis
        - date_end: ''
          date_start: '2018-09-01'
          description: ''
          organization: Graduate level
          title: Intermediate Microeconomics
    design:
      columns: '2'
  
---
