---
title: Contact
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >
      How can we serve? We are pleased to help. Please fill the contact form
      below or send us directly an email at hello@epicfusion.com.
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
  - title: Contact
    section_id: lorem-ipsum
    content: >
      How can we serve? We are pleased to help. Please fill the contact form
      below or send us directly an email at hello@epicfusion.com.
    actions:
      - label: Leave a message here
        url: 'https://form.asana.com?k=AdlAWEDpqiAikr-o_rKkxA&d=1200129872637977'
        style: button
        icon: dribbble
        new_window: false
        no_follow: false
        type: action
    type: section_hero
seo:
  title: Contact - Epic Fusion GmbH
  description: >-
    How can we serve? We are pleased to help. Please fill the contact form below
    or send us directly an email.
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
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
