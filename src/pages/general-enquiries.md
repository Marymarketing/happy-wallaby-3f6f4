---
title: Formulaire de contact
sections:
  - type: hero_section
    title: Contactez-nous
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >
      ## Confidentialité


      Mary Marketing traite les données recueillies en utilisant votre adresse
      électronique pour vous adresser des publicités concernant ces services.


      Pour en savoir plus sur la gestion de vos données personnelles et pour
      exercer vos droits, reportez-vous à la notice
      [**ci-jointe**](/privacy-policy).
    content_align: center
    form_position: top
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: Formulaire contact
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: 'Nom, prénom'
        label: Nom et prénom
        default_value: Votre nom et prénom
        is_required: true
      - input_type: email
        name: email
        label: Adresse mail
        default_value: Votre adresse mail
        is_required: true
      - input_type: select
        name: Objet
        label: Objet
        default_value: Choisissez
        options:
          - Partenariat
          - Demande de devis
          - Erreur à signaler
          - Autre
        is_required: true
      - input_type: textarea
        name: message
        label: Message
        default_value: Rédigez votre message
      - input_type: checkbox
        name: consent
        label: >-
          Je suis d'accord pour que Mary marketing utilise et stocke mes données
          à des fin publicitaire.
        is_required: true
    submit_label: Envoyer
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
seo:
  title: General Enquiries
  description: This is the general enquiries page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: General Enquiries
      keyName: property
    - name: 'og:description'
      value: This is the general enquiries page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: General Enquiries
    - name: 'twitter:description'
      value: This is the general enquiries page
template: advanced
---
