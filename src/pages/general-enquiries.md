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
    content: >-
      ### Billing

      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
      ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
      fringilla, fringilla.

      ### Privacy

      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
      ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
      fringilla, fringilla.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: Formulaire contact
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: 'Nom, prénom'
        label: Prénom
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
