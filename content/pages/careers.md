---
title: services
slug: careers
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: "cuda\_ services"
      color: text-dark
    subtitle: Services et consulting de solutions informatiques Genève et Romandie
    text: "VOTRE INFRASTRUCTURE INFORMATIQUE\nHEBERGÉE EN SUISSE OU MAINTENUE SUR SITE\n\nASSISTANCE DANS LE QUOTIDIEN ET DANS VOS PROJETS\n\nSUPPORT INFORMATIQUE ET CONSULTING SUR\nSITE A GENÈVE ET EN ROMANDIE\n\n\_\n"
    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        icon: arrowRight
        iconPosition: right
        style: primary
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    colors: bg-light-fg-dark
seo:
  metaTitle: Careers - Demo site
  metaDescription: This is the careers page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
