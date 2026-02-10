---
title: 'Coughlin Research Lab'
date: 2024-05-20
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections  
sections:
  - block: hero
    content:
      title: |
        The Coughlin Laboratory
      text: |
        The **University of Colorado Anschutz** is a state-of-the-art research campus uniting three hospitals: University of Colorado Hospital, Children’s Hospital of Colorado, and the Rocky Mountain Regional Veterans Affairs Medical Center, multiple centers and institutes, and administrative, research, and educational facilities.
      primary_action:
        text: Contact us
        url: '#contact'
        icon: hero/phone
      secondary_action:
        text: Coughlin lab overview
        url: '#equipment'
        icon: hero/document-text
    design:
      css_class: ""
      background:
        gradient_mesh:
          enable: true
          style: "orbs"
          animation: "pulse"
          intensity: "medium"
          colors:
            - "blue-600/25"
            - "indigo-600/20"
            - "purple-600/15"

  - block: stats
    content:
      items:
        - statistic: "7.41M"
          description: Square foot campus
          icon: hero/building-office
        - statistic: "4500"
          description: Students across 40 programs
          icon: hero/academic-cap
        - statistic: "$704M"
          description: Research funding
          icon: hero/currency-dollar
        - statistic: "$8.5B"
          description: to the Colorado economy
          icon: hero/currency-dollar
    design:
      layout: compact
      css_class: "bg-gray-50 dark:bg-gray-900"

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: campus.jpg
          filters:
            brightness: 1
          parallax: false
          position: top
          size: cover
          text_color_light: true
      spacing:
        padding: ['200px', '0', '200px', '0']
      css_class: fullscreen

  - block: cta-image-paragraph
    content:
      items:
        - title: 'Spectroscopy Equipment'
          text: |
            Many of our research questions foucs on the association between the abnormal metabolism and disaese phenotype. This requires accurate measurement of several biomakers through approaches such as liquid chromatography tandem mass spectrometry (LC-MS/MS). Our spectroscopy equipment is the heart and soul of our laboratory. This work has led to the identificaition and clinical validation of novel biomakers, and demonstration that treatment can improve the abnormal biochemistry in various model systems.
          image: kristie_ms.jpg
          feature_icon: hero/beaker
          features:
            - 'Waters H-Class UPLC system'
            - 'Waters TQD Triple Quadrupole MS'  
            - 'Waters Tunable UV (TUV) detector'
            - 'Waters Fluorescence (FLR) detector'
          button:
            text: 'Active Research Projects'
            url: '/projects'

        - title: 'Disease Model Systems'
          text: |
            Our reserach has primarly foucsed on two rare diseases: pyridoxine-dependent epilepsy (PDE-ALDH7A1) and glutaric aciduria type 1 (GA1). To study PDE-ALDH7A1 we utize both e.coli-based expression system to evalute the impact of genetic variants and animal models to answer complex questions about diease mechanism.   
          image: nicole_bench.jpg
          feature_icon: hero/beaker
          features:
            - 'Samples from study participants'
            - 'E.coli-based expression system for ALDH7A1'
            - 'Mouse model of PDE-ALDH7A1'
            - 'Zebrafish models of PDE-ALDH7A1 and GA1'
          button:
            text: 'Active Research Projects'
            url: '/projects'

        - title: 'Patient Engagement'
          text: |
            Patient engagement is as important to our reserach as any laboratory equipment or model system.  We are greatful the support from various patient organizations and familys over the last 10+ years. In fact our initial PDE-ALDH7A1 newborn screening study was funded through a 5k in 2014. In addition to the financial support, we are grateful that familys share their storied with us are we consider each one an extended member of our team. 
          image: Jen_PDE.jpg
          feature_icon: hero/user-group
          features:
            - 'Patients and Families'
            - 'PDE Foundation'
            - 'CurePDE Foundation'
            - 'Organic Acidemia Association'
          button:
            text: 'See our publications'
            url: '/publications'
    design:
      css_class: "bg-white dark:bg-gray-800"
 
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: denver.jpg
          filters:
            brightness: 1
          parallax: false
          position: top
          size: cover
          text_color_light: true
      spacing:
        padding: ['200px', '0', '200px', '0']
      css_class: fullscreen

  - block: features
    id: equipment
    content:
      title: Coughlin Research Laboratory Overview 
      text: We are a translational research laboratory. We combine rigorous scientic methods with patient engagement approaches. 
      items:
        - name: 'Natural History Studies'
          description: 'Clincical outcomes help us prioritze reserch goals and provide critical control data in clincial trials'
          icon: emoji/clipboard
          
        - name: 'Record of Collaboration'
          description: 'Collaboration with clinican-scientists advance research goals and speed translation of results to the bedside'
          icon: emoji/hospital
          
        - name: 'Enagement Stratagies'
          description: 'Partnerships with families help enusre our reserach goals are patient-centered and clinically meaningful'
          icon: emoji/family_man_man_girl_boy
          
        - name: 'Model Systems for Rare Disease'
          description: 'Animal (zebrafish, mice) and human model systems to interrogate mechansim and novel treatments'
          icon: emoji/mouse2
          
        - name: 'Omics Expertise'
          description: 'Exerpience in  genonmics, metabolomics, and proteomics with a focus on disease mechanism'
          icon: emoji/dna
          
        - name: 'Spectroscopy Laboratory'
          description: 'Analytical instrumententaion with a focus on quantiative mass spectrometry approaches'
          icon: emoji/microscope
    design:
      css_class: "bg-gradient-to-b from-gray-50 to-white dark:from-gray-900 dark:to-gray-800"

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
      email: 'coughlin.lab@gmail.com'
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
