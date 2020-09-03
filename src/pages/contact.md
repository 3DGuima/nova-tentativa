---
title: Contato
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: 'Para entrar em contato preencha os campos a seguir:'
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: Digite seu nome...
        label: Nome
        default_value: Seu nome
        is_required: true
      - input_type: email
        name: Digite seu endereço de email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
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
template: advanced
---
