---
title: 'Pyridoxine-dependent epilepsy try 2'
date: 2024-05-20
type: landing

summary: "Ensuring every patient is diagnosed and treated at birth. Focused on improving clinical outcomes today and treatment advances for tomorrow."

design:
  # Section spacing
  spacing: '5rem'

# Page sections  
sections:
  - block: hero
    content:
      title: |
        **Pyridoxine-dependent epilepsy**
      text: |
        We aim to ensuring every patient is diagnosed and treated at birth. We are ocused on improving clinical outcomes today so that patients can beneift from treatment advnacees tomorrows.
      primary_action:
        text: Schedule a Tour
        url: '#contact'
        icon: hero/calendar
      secondary_action:
        text: Equipment Catalog
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

  - block: cta-image-paragraph
    content:
      items:
        - title: 'Clinical Research'
          text: |
            We collaborate with international PDE-ALDH7A1 experts including Professors Clara van Karnebeek, Sidney Gospe Jr, and members of the Interntional PDE Consortium. Our work has led to the incoproration of lysine-restricted diet and triple therapy (vitamin B<sub>6</sub>, lysine-restricted diet, arginine supplementation) as standard of care treatment. 
          image: Cohort study.jpg
          feature_icon: emoji/hospital
          features:
            - 'First clinical studies using lysine-reduction therapies (LRT)'
            - 'Demonstration that early treatment with LRT improves IQ' 
            - 'Consensus guidlines for diagnosis and treatment' 
            - 'New clinical insights from the International PDE Registry'
          button:
            text: 'Join our Natural History Study'
            url: '/resources/computing'

        - title: 'Basic Research'
          text: |
            We aim to understand the underlying disease mechansim of PDE-ALDH7A1 with a focus on biochemistry. This work led us to identify a new metabolite within lysine metabolism (6-oxo-pipecolate) that we later applied to newborn screening. Our current research focuses on impact of global metabolic dysfunction and the impact of &alpha;-AASA dehydrogenase deficiency. This work is funded by NIH/NICHD and the CurePDE Foundation. 
          image: 6OP.jpg
          feature_icon: emoji/dna
          features:
            - 'Human samples to identify and evalute novel biomakers'
            - 'Animal models to elucidate the impact of metabolic dysfunction'
            - 'Functional studies focused on unique genetic variants'
            - 'Translation of research results to clinical partners'
          button:
            text: 'Equipment Reservations'
            url: '/resources/equipment'

        - title: 'Novel Genetic Therapies'
          text: |
            Although lysine reduction therapies improve clinical outcomes, nutritional based treatments are diffiuclt and associted with a negative impact on quality of life. We collaborate with the CHARLIE consoritum, other scientists, biotech, and pharmaceutical partners to evalute genetic based therapies for PDE-ALDH7A1. This includes several approaches to substrate reduction therapy. This work is funded by philanthropic donations and the CurePDE Foundation. 
          image: curepde-lab.jpg
          feature_icon: emoji/pill
          features:
            - 'Zebrafish and mouse models allow us to evalute new treatments'
            - 'Leveraging disease expertise to ensure meaningful outcomes' 
            - 'Enagement with stakeholders to ensure patinet-first approaches'
            - 'Translational approches to move quickly from lab to the clinic'
          button:
            text: 'Donate our research'
            url: '/resources/computing'
    design:
      css_class: "bg-white dark:bg-gray-800"

  - block: features
    id: equipment
    content:
      title: Core Research Equipment
      text: Our comprehensive instrumentation supports diverse research needs across multiple disciplines
      items:
        - name: 'High-Performance Computing Cluster'
          description: '500+ GPU cores, 100TB storage, redundant systems for maximum uptime and computational power.'
          icon: hero/server
          
        - name: 'Electron Microscopy Suite'
          description: 'Scanning and transmission electron microscopes for nanoscale materials characterization.'
          icon: hero/magnifying-glass
          
        - name: 'Spectroscopy Laboratory'
          description: 'Complete range of analytical instruments including NMR, FTIR, and mass spectrometry.'
          icon: hero/chart-bar
          
        - name: 'Clean Room Facilities'
          description: 'Class 100 and 1000 clean rooms for sensitive sample preparation and device fabrication.'
          icon: hero/shield-check
          
        - name: 'Biological Safety Labs'
          description: 'BSL-2 certified laboratories with specialized ventilation and containment systems.'
          icon: hero/beaker
          
        - name: '3D Printing & Fabrication'
          description: 'Rapid prototyping capabilities for custom research equipment and sample holders.'
          icon: hero/cube
    design:
      css_class: "bg-gradient-to-b from-gray-50 to-white dark:from-gray-900 dark:to-gray-800"

  - block: markdown
    content:
      title: 'Safety & Compliance'
      subtitle: 'Research Excellence Through Responsible Practices'
      text: |
        ## Safety First Philosophy
        
        Safety is fundamental to our research mission. All facilities operate under strict safety protocols with regular training, equipment maintenance, and compliance audits.
        
        ### Key Safety Features:
        - **Emergency Response**: 24/7 emergency response team and automated safety systems
        - **Training Programs**: Mandatory safety training for all researchers and regular refresher courses  
        - **Equipment Maintenance**: Preventive maintenance schedules and real-time monitoring systems
        - **Regulatory Compliance**: Full compliance with OSHA, EPA, and institutional safety requirements
        
        ### Environmental Responsibility:
        - Energy-efficient equipment and LED lighting throughout facilities
        - Waste minimization programs and proper hazardous waste disposal
        - HVAC systems optimized for both safety and energy conservation
        - Sustainable procurement policies for equipment and supplies
    design:
      columns: '1'
      css_class: "bg-primary-50 dark:bg-primary-900/10"

  - block: contact-info
    id: contact
    content:
      title: Plan Your Visit
      subtitle: 'Experience Our Facilities Firsthand'
      visit_title: 'Visit Us'
      connect_title: 'Connect'
      address:
        lines:
          - Research Lab
          - Science Building, University of Excellence
          - 123 Science Drive
          - Excellence City, EC 12345
      office_hours:
        - 'Monday - Friday: 8:00 AM - 6:00 PM'
        - 'Saturday: 9:00 AM - 2:00 PM'
        - 'Sunday: By appointment only'
      email: 'facilities@example.edu'
      phone: '+1 (555) 123-4567'
      social:
        - icon: brands/linkedin
          url: https://linkedin.com
        - icon: brands/x
          url: https://x.com
      map_url: 'https://maps.google.com/?q=Science+Building+Excellence+City'
    design:
      css_class: "dark bg-gray-900 text-white"
---