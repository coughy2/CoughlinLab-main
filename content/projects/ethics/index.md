---
title: 'Ethics and Genetics (ELSI)'
date: 2025-07-17
type: landing

tags:
  - Bioethics
  - Pediatric ethics 
  - ELSI
  - Precision medicine
featured: true
summary: "Our research focuses on the intersection of genetics and ethics and equitable access to treatment for rare diseases"

design:
  # Section spacing
  spacing: '5rem'

# Page sections  
sections:
  - block: hero
    content:
      title: |
        **Ethics and Genetics**
      text: |
        Our ethics research is primarly focused on the ethical, legal, and social implications (ELSI) of genetics and genomics. Dr. Coughlin is a certified health ethics consultant (HEC-C) and also serves as a clinical bioethics. 
      primary_action:
        text: Contact us
        url: '#contact'
        icon: hero/phone
      secondary_action:
        text: Center for Bioethcs & Humanities
        url: 'https://www.cuanschutz.edu/centers/bioethicshumanities'
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

  - block: cta-image-paragraph
    content:
      items:
        - title: 'CADRe Framework'
          text: |
            The Consent & Disclosure Recommendations [(CADRe)](https://clinicalgenome.org/tools/cadre/) workgroup was part of the ClinGen resource. Our research focused on development of an ethical framework with an emphasis on consent and diclosure by non-genetic providers.  Some of our publications are noted below: 
          image: cadre.jpg
          feature_icon: emoji/dna
          features:
            - 'A rubric-based approach to consent and disclosure [[Link](https://pubmed.ncbi.nlm.nih.gov/29976988/)]'
            - 'Application of ethicial framework [[Link](https://pubmed.ncbi.nlm.nih.gov/33926532/)]'
            - 'A delphi consensus foucsed on informed consent [[Link](https://pubmed.ncbi.nlm.nih.gov/34945775/)]' 
            - 'Informed consent: Views of GCs and MD geneticsts [[Link](https://pubmed.ncbi.nlm.nih.gov/37308598/)]'
          button:
            text: 'View our publications'
            url: '/publications'

        - title: 'Rare Disease'
          text: 
            Our rare disease work foucses on equitable access to treatment.  This ranges from ensuring that all children have oppritunities for medical treatment regardless of genetic diagnosis or access to high cost therapeutics.  Some of our publications on ethical issues in the treatment of rare diseases are noted below  
          image: rare.jpg
          feature_icon: emoji/pill
          features:
            - 'Treatment of fetal cystic fibrosis [[Link](https://pubmed.ncbi.nlm.nih.gov/40965475/)]'
            - 'Pediatric metabolic bariatric surgery [[Link](https://pubmed.ncbi.nlm.nih.gov/33191162/)]'
            - 'Relationships with industry partners [[Link](https://pubmed.ncbi.nlm.nih.gov/31337884/)]'
          button:
            text: 'View our publications'
            url: '/publications'

    design:
      css_class: "bg-white dark:bg-gray-800"

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