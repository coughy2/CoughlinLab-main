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
        The **University of Colorado Anschutz** is a state-of-the-art research campus and provides infrastructure for groundbreaking discoveries. From specialized laboratories to high-performance computing resources, every facility is designed to accelerate scientific innovation.
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

  - block: stats
    content:
      items:
        - statistic: "15,000"
          description: Square feet of lab space
          icon: hero/building-office
        - statistic: "500+"
          description: GPU cores for computation
          icon: hero/cpu-chip
        - statistic: "24/7"
          description: Facility access for researchers
          icon: hero/clock
        - statistic: "$10M"
          description: Equipment value
          icon: hero/currency-dollar
    design:
      layout: compact
      css_class: "bg-gray-50 dark:bg-gray-900"

  - block: cta-image-paragraph
    content:
      items:
        - title: 'Spectroscopy'
          text: |
            Many of our primary research questions foucs on the association between the abnormal metabolism and disaese phenotype. This requires accurate measurement of several biomakers through approaches such as liquid chromatography tandem mass spectrometry (LC-MS/MS). Our spectroscopy equipment is the heart and soul of our laboratory. This work has led to the identificaition and clinical validation of novel biomakers, and demonstration that new therapeutic approaches and improve the abnormal biochemistry in various model systems.
          image: kristie_ms.jpg
          feature_icon: hero/beaker
          features:
            - 'Waters H-Class UPLC system'
            - 'Waters TQD Triple Quadrupole MS'  
            - 'Waters Tunable UV (TUV) detector'
            - 'Waters Fluorescence (FLR) detector'
          button:
            text: 'Request Computing Access'
            url: '/resources/computing'

        - title: 'Disease Model Systems'
          text: |
            Our reserach has primarly foucsed on two rare diseases: pyridoxine-dependent epilepsy (PDE-ALDH7A1) and glutaric aciduria type 1 (GA1). To study PDE-ALDH7A1 we utize both e.coli and yeast systems to evalute the impact of disease variants and animal models to answer complex questions about diease mechanism. Although Dr. Woontner played a significant role in the develoment of the GA1 murine model, we have moved to a zebrafish model of GA1.  
          image: nicole_bench.jpg
          feature_icon: hero/beaker
          features:
            - 'Samples from study participants'
            - 'E.coli based expression system for ALDH7A1'
            - 'Mouse model of PDE-ALDH7A1'
            - 'Zebrafish models of PDE-ALDH7A1 and GA1'
          button:
            text: 'Equipment Reservations'
            url: '/resources/equipment'

        - title: 'Patient Engagement'
          text: |
            Our reserach has primarly foucsed on two rare diseases: pyridoxine-dependent epilepsy (PDE-ALDH7A1) and glutaric aciduria type 1 (GA1). To study PDE-ALDH7A1 we utize both e.coli and yeast systems to evalute the impact of disease variants and animal models to answer complex questions about diease mechanism. Although Dr. Woontner played a significant role in the develoment of the GA1 murine model, we have moved to a zebrafish model of GA1.  
          image: Jen_PDE.jpg
          feature_icon: hero/beaker
          features:
            - 'Samples from study participants'
            - 'E.coli based expression system for ALDH7A1'
            - 'Mouse model of PDE-ALDH7A1'
            - 'Zebrafish models of PDE-ALDH7A1 and GA1'
          button:
            text: 'Equipment Reservations'
            url: '/resources/equipment'
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
