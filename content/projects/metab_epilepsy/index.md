---
title: 'Metabolic Epilepsies'
date: 2025-07-18
type: landing

tags:
  - Epilepsy
  - Disease Mechanisms
  - Therapeutic Advances
  - Rare Disease Studies
featured: true
summary: "We aim to understand the mechanism of metabolic epilepsies and to identify shared clinical outcome measures that can faciliate clinical trial designs."

design:
  # Section spacing
  spacing: '5rem'

# Page sections  
sections:
  - block: hero
    content:
      title: |
        **Metabolic Epilepsies**
      text: |
        We focus on rare, metabolic epilepsies. We aim to understand that disease mechansim and develop treatment for indivdiual disorders. We also focus on basket trial designs using shared clinical outcomes for similar disorders.
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

  - block: cta-image-paragraph
    content:
      items:
        - title: 'B<sub>6</sub> responsive seizures'
          text: |
            Our primary reseearch is focused on PDE-ALDH7A1 defciency which is only one of the vitamin B<sub>6</sub> responsive seizure disorders. In addition to the known genetic B<sub>6</sub> responsive disorders, a number of patients with idiopathic seizures respond to vitmain B<sub>6</sub> supplementation. We are focused on both identification of novel genetic causes and understanding general mechanism of these disorders.
          image: b6.jpg
          feature_icon: emoji/dna
          features:
            - 'Genome study to identify novel biomakers [[Enroll](#contact)]'
            - 'Tissue specific LC-MS/MS quantification of Bsub>6</sub> vitamers' 
            - 'Disesase specific LC-MS/MS quantification of Bsub>6</sub> vitamers' 
            - 'The role of vitamin B<sub>6</sub> in idopathic seizure disorders'
          button:
            text: 'View all our publications'
            url: '/publications'

        - title: 'Nonketotic hyperglycinemia'
          text: |
            We collaborate with Professor Johan Van Hove's [laboratory](https://medschool.cuanschutz.edu/pediatrics/sections/genetics-and-metabolism/research/nonketotic-hyperglycinemia-(nkh)-research-lab) to study Nonketotic Hyperglycinemia (NKH). We initially charecterized mutations in the genes **GLDC** and **AMT** that cause classic NKH, and described biomarkers (imaging, genetic, and biochemical based) that may aid prognosis. We continue to collaborte with the Van Hove lab to understand the impact of vitamin B<sub>6</sub> and evaluate novel therapies.  
          image: nkh.jpg
          feature_icon: emoji/dna
          features:
            - 'Genetic basis of classic NKH [[Link](https://pubmed.ncbi.nlm.nih.gov/27362913/)]'
            - 'Neuodevelomental outcomes in NKH [[Link](https://pubmed.ncbi.nlm.nih.gov/26749113/)]'
            - 'Brain imagining and phenotype in NKH [[Link](https://pubmed.ncbi.nlm.nih.gov/30737808/)]'
            - 'Biocehmical and molecular predictors of prognosis [[Link](https://pubmed.ncbi.nlm.nih.gov/26179960/)]'
          button:
            text: 'View all our publications'
            url: '/publications'

        - title: 'Rare metabolic epilepsies'
          text: |
            We collaborate with several clinicican-scientists who are studying metabolic epilepsies. HCFC1 is a transcriptoinal regulator and mutations in HCFC1 can cause a severe neurologic phentoype, seizure or infantile spasms, and abnormal cobalmin metabolism. Along with Professors [Shaikh](https://som.cuanschutz.edu/Profiles/Faculty/Profile/7943) and van Hove, we described HCFC1 deficeincy and later show that this disorder can mimic abnormal biochemistry of NKH.  We also described the inital patient with CARS2 encephalopthay, a mitochondrial disorder and that presented with epileptic encpahlopathy, and a novel biomaker for ECHS1 where patients have leigh syndrome and (at least for most patients) seizures.  
          image: hcfc1.png
          feature_icon: emoji/dna
          features:
            - 'A rare X-linked cobalamin disorder: HCFC1 [[Link](https://pubmed.ncbi.nlm.nih.gov/24011988/)]'
            - 'HCFC1 and elecated CSF glycine and MMA levels [[Link](https://pubmed.ncbi.nlm.nih.gov/28363510/)]' 
            - 'Mutations in CARS2 leads to a severe epileptic encphalopathy [[Link](https://pubmed.ncbi.nlm.nih.gov/25787132/)]'
            - 'The clinical and biochemical charecterization of ECHS1 defciency [[Link](https://pubmed.ncbi.nlm.nih.gov/26081110/)]'
          button:
            text: 'View all our publications'
            url: '/publications'
    design:
      css_class: "bg-white dark:bg-gray-800"

  - block: features
    id: equipment
    content:
      title: Coughlin Research Laboratory Overview 
      text: We are a translational reserch laboratory focused on patient-centered reserach.  We combine rigours scientic methods with patient engagement approaches. 
      items:
        - name: 'Natural History Studies'
          description: 'Clincical outcomes help prioritze reserch goals and provide critical control data in clincial trials'
          icon: emoji/clipboard
          
        - name: 'Record of Collaboration'
          description: 'Collaboration with clinican and scientist advance research and translation of results to the bedside'
          icon: emoji/hospital
          
        - name: 'Enagement Stratagies'
          description: 'Partnerships with patients and families to enusre our reserach goals are patient-centered'
          icon: emoji/family_man_man_girl_boy
          
        - name: 'Model Systems for Rare Disease'
          description: 'Animal (zebrafish, mice) and human model systems to interrogate mechansim and novel treatments'
          icon: emoji/mouse2
          
        - name: 'Omics Expertise'
          description: 'Exerpience in  genonmics, metaoblimics, proteomics with a focus on disease mechanism'
          icon: emoji/dna
          
        - name: 'Spectroscopy Laboratory'
          description: 'Analytical instrumententaion with a focus on quantiative mass spectrometry approaches'
          icon: emoji/microscope
        
    design:
      columns: '1'
      css_class: "bg-primary-50 dark:bg-primary-900/10"

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