---
title: Contact
sections:
  - section_id: contact
    type: section_contact
    background: black
    title: Contact
    content: >-
      Got questions? Just send us an email at <a href="mailto:info@smartminions.com.au?subject=Get in touch">info@smartminions.com.au</a>, or simply use the form below.
    form_id: contactForm
    form_action: https://formspree.io/f/mbjpavyw
    form_fields:
      - input_type: text
        name: name
        label: Name
        is_required: true
      - input_type: email
        name: email
        label: Email
        is_required: true
      - input_type: textarea
        name: message
        label: Message
    submit_label: Send Message
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: landing
---
