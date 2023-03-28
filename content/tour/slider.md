---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 👋 Quem somos
      content: Somos uma equipa constituída por Médicos de Família, Enfermeiros, Secretários Clínicos, Assistente Operacional,  Internos de Especialidade de Medicina Geral e Familiar, alunos de Medicina e Enfermagem, motivados para o servir melhor.
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: CS_Cantanhede.jpg
    - title: Lunch & Learn ☕️
      content: 'Share your knowledge with the group and explore exciting new topics together!'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: contact.jpg
    - title: World-Class Semiconductor Lab
      content: 'Just opened last month!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
