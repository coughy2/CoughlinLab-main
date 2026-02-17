---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: hero
    id: about
    content:
      title: |
        The Coughlin Laboratory
      text: |
        We focus on neurometabolic disorders. We aim to understand disease mechansims, develop novel therapies, and help implement proven treatments into clinical care. We believe in patient-centered research and combine rigorous scientific methods with patient engagement approaches.
      primary_action:
        text: Virtual Lab Visit
        url: '/facilities'
        icon: hero/map-pin
      secondary_action:
        text: View Our Publications
        url: '/publications'
        icon: hero/academic-cap
      announcement:
        text: ""
        link:
          text: ""
          url: ""
    design:
      # For full-screen, add `min-h-screen` below
      css_class: ""
      background:
        # Option A: Modern gradient mesh (recommended for 2025/2026)
        gradient_mesh:
          enable: true
          style: "waves"
          animation: "pulse"
          intensity: "medium"
          colors:
            - "primary-500/30"
            - "blue-600/20"
            - "indigo-600/15"
        
        # Option B: Team/lab image (uncomment to use instead of gradient mesh)
        # image:
        #   filename: "team-lab-hero.jpg"
        #   filters:
        #     brightness: 0.6
        #     contrast: 1.1

  - block: markdown
    content:
      title: 
      subtitle: ''
      text: 
    design:
      columns: '1'
      background:
        image: 
          filename: pde_fam.jpg
          filters:
            brightness: 1
          parallax: false
          position: top
          size: cover
          text_color_light: true
      spacing:
        padding: ['200px', '0', '200px', '0']
      css_class: fullscreen

  - block: research-areas
    content:
      title: Research Focus Areas
      subtitle: " "
      text: As a translational research lab, we aim to make real world impact by moving through the various stages of research including basic science, preclincial studies, and clinical application. 
      items:
        - name: Rare Disease Studies 
          description: Natural history studies enhance our understanding of disease, set research priorities, and provide historical data for clincial trials  
          icon: emoji/hospital
          gradient: from-green-400 to-emerald-600 
          status: enrolling
          topics:
            - Clinical outcomes
            - Study design 
          team_size: 5
          publications: 70+
          funding: NIH/Philanthropy
          cta:
            text: Learn more or enroll 
            url: /research/natural-history

        - name: Disease Mechanisms
          description: Patient samples and model systems help us study the underlying disease cause. Biochemical studies identify biomakers for diagnosis & treatment
          icon: emoji/dna
          gradient: from-purple-400 to-pink-600
          status: active
          topics:
            - Metabolomics
            - Genomics
            - Proteomics  
          team_size: 5
          publications: 70+
          funding: NIH/Philanthropy
          cta:
            text: Explore Projects
            url: /projects
            
        - name: Therapeutic Advances 
          description: Preclinical models are used to study genetic based treatments. We partner with scientists and pharma companies also focused on rare diseases
          icon: emoji/pill
          gradient: from-blue-400 to-indigo-600
          status: active
          topics:
            - Preclinical studies
            - Genetic therapies
          team_size: 5
          publications: 70+
          funding: NIH/Philanthropy
          cta:
            text: Explore Projects
            url: /projects
      cta:
        text: Active Research Projects
        url: /#projects
        icon: hero/arrow-right
    design:
      layout: cards
      css_class: "bg-gradient-to-b from-gray-50 to-white dark:from-gray-900 dark:to-gray-800"
      spacing:
        padding: ["5rem", 0, "5rem", 0]

  - block: team-showcase
    id: team
    content:
      title: Meet Our Team
      subtitle: 'A dedicated group of scientists focused on rare disease'
      text: 
      user_groups:
        - Researchers
        - Graduate Students
        - Alumni
      sort_by: 'Params.last_name'
      sort_ascending: true
      cta:
        text: Team Member News
        url: /blog
        icon: user-group
    design:
      show_role: true
      show_organizations: false
      show_interests: true
      show_social: true
      # Section background color
      css_class: "bg-gray-50 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["3rem", 0, "3rem", 0]

  - block: collection
    id: projects
    content:
      title: Active Research Projects
      subtitle: ''
      text: ''
      filters:
        folders:
          - projects
      count: 0  # Number of items to show (0 = all)
      # Default filter UI (for future release)
      #default_button_index: 0
      # Filter toolbar (optional)
      # Add or remove as many filters as you like
    #   buttons:
    #     - name: All
    #       tag: '*'
    #     - name: Machine Learning
    #       tag: ML
    #     - name: Biology
    #       tag: Biology
    #     - name: Materials
    #       tag: Materials
    design:
      view: article-grid
      columns: 2

  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
      count: 5
    design:
      view: citation

  - block: collection
    id: news
    content:
      title: Lab News & Updates
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 2
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: article-grid
      columns: 2

  - block: collection
    id: events
    content:
      title: Events
      subtitle: Join Us for Research Presentations & Seminars
      text: Stay connected with our research community through talks, workshops, and collaborative events
      filters:
        folders:
          - events
        exclude_past: false  # Show both past and future events
      count: 2
      sort_by: Date
      sort_ascending: false
    design:
      view: article-grid
      # columns: 2
      show_date: true
      show_read_time: false
      show_read_more: true
      css_class: "bg-gradient-to-b from-white to-gray-50 dark:from-gray-800 dark:to-gray-900"
      spacing:
        padding: ["4rem", 0, "4rem", 0]

  - block: logos
    content:
      title: Collaborators & Partners
      subtitle: Leading the way together
      text: We work with family advocacy groups, interntional consoritums, top universities, research institutes, and industry leaders to advance scientific discovery
      logos:
        - name: Charlie
          image: partners/charlie-logo.png
          url: https://www.charlie.science/
          external: true
          description: Changing rare disorders of lysine metabolism
        - name: CurePDE
          image: partners/curepde-logo.png
          url: https://curepde.org/
          external: true
          description: CurePDE Foundation
        - name: OAA
          image: partners/oaa-logo.png
          url: https://oaanews.org/
          external: true
          description: Organic Acidemia Association
        - name: PDE consorium 
          image: partners/pde-logo.png
          url: http://wwws.pdeonline.org/
          external: true
          description: International PDE Consortium 
        - name: ROAR
          image: partners/roar-logo.png
          url: 
          external: true
          description: Rare Organic Acidemia Research
        - name: UCDC
          image: partners/ucdc-logo.png
          url: https://ucdc.rarediseasesnetwork.org/
          external: true
          description: Urea Cycle Disorders Consorium
      cta:
        text: Become a Partner
        url: /#contact
        icon: hero/user-plus
    design:
      display_mode: grid
      show_pattern: true
      css_class: "bg-gradient-to-b from-white to-gray-50 dark:from-gray-800 dark:to-gray-900"
      spacing:
        padding: ["4rem", 0, "4rem", 0]

  - block: contact-info
    id: contact
    content:
      title: Contact Us
      subtitle: ''
      visit_title: 'Mailing Address'
      connect_title: 'Connect'
      address:
        lines:
          - University of Colorado Anschutz 
          - 12800 E. 17th Ave
          - RC1 North, P18-3401A
          - Mail stop 8313
          - Aurora, CO 80045
      Univerity of Colorado Anschutz:
      email: 'Coughlin.Lab@CUAnschutz.edu'
      phone: '+1 (303) 724.3814'
      social:
        - icon: brands/facebook
          url: https://www.facebook.com/coughlin.pde.lab/
        - icon: brands/linkedin
          url: https://www.linkedin.com/in/curtiscoughlinii/
      map_url: 'https://maps.app.goo.gl/qEkYNTcJFVFUEwco9'
      show_form: false
    design:
      css_class: "bg-gradient-to-b from-gray-50 to-white dark:from-gray-900 dark:to-gray-800"
      spacing:
        padding: ["5rem", 0, "5rem", 0]
---