---
title: Neem contact op
img_path: images/contact.jpg
form_id: contactForm
form_action: 'http://energieinspiratie.nl:8080/contact'
form_fields:
  - input_type: text
    name: name
    label: Naam
    default_value: Uw naam
    is_required: true
  - input_type: email
    name: email
    label: Email
    default_value: Uw email
    is_required: true
  - input_type: select
    name: subject
    label: Onderwerp
    default_value: Selecteer
    options:
      - Inschrijving voor een activiteit
      - Informatie over een activiteit
      - Overig
      - Fout op de website
  - input_type: textarea
    name: message
    label: Bericht
    default_value: Uw bericht
  - input_type: checkbox
    name: consent
    label: >-
      Ik begrijp dat deze gegevens opgeslagen worden zodat er contact met mij
      opgenomen kan worden.
submit_label: Verstuur
seo:
  title: Get in Touch
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Get in Touch
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'og:image'
      value: images/contact.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Get in Touch
    - name: 'twitter:description'
      value: This is the contact page
    - name: 'twitter:image'
      value: images/contact.jpg
      relativeUrl: true
template: contact
---
Vertel me wat je bezig houdt.
