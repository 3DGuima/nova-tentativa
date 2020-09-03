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
        default_value: Digite seu nome...
        is_required: true
      - input_type: email
        name: Digite seu endereço de email...
        label: Email
        default_value: Digite seu endereço de email...
        is_required: true
      - input_type: select
        name: Assunto
        label: Assunto
        default_value: Selecione um ítem...
        options:
          - Contratar um trabalho
          - Dúvidas técnicas ou profissionais
          - Outro assunto
      - input_type: textarea
        name: Menssagem
        label: Menssagem
        default_value: Digite sua mensagem...
      - input_type: checkbox
        name: consent
        label: >-
          Eu entendo que este formulário está armazenando meu email e mensagem,
          fornecidos por mim, para que eu possa ser contatado.
    submit_label: Enviar
  - title: lorem-ipsum
    section_id: lorem-ipsum
    content: >-
      ## Lorem ipsum

      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua.

      - Lorem ipsum

      - dolor sit amet
    actions: []
    type: section_content
template: advanced
---
