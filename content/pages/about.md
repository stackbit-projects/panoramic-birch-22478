---
title: About us
sections:
  - type: HeroSection
    title: Our story
    text: >
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus vel
      venenatis augue. Suspendisse tincidunt, nibh eget sodales eleifend, lectus
      magna elementum lorem, ut bibendum tellus turpis quis risus. Sagittis enim
      est, et semper lectus hendrerit ut.


      In sollicitudin imperdiet turpis quis accumsan. Pellentesque euismod
      turpis et nisi fermentum accumsan.
    feature:
      type: ImageBlock
      url: /images/about.jpg
      altText: About us
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        fontWeight: '700'
        fontStyle: normal
        textAlign: left
        margin:
          - mt-0
          - mb-8
      subtitle:
        fontWeight: '400'
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
        margin:
          - mt-0
          - mb-8
      actions:
        justifyContent: flex-start
    backgroundImage:
      altText: lorem-ipsum
      caption: lorem-ipsum
      elementId: ''
      styles:
        self:
          opacity: 100
      type: ImageBlock
  - type: FeaturedPeopleSection
    elementId: ''
    variant: variant-a
    colors: colors-a
    title: The Team
    subtitle: An optional subtitle of the section
    people:
      - content/data/team/gordon-norman.json
      - content/data/team/parsley-montana.json
      - content/data/team/hilary-ouse.json
      - content/data/team/desmond-eagle.json
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        justifyContent: center
      title:
        fontWeight: '700'
        fontStyle: normal
        textAlign: center
        margin:
          - mt-0
          - mb-4
      subtitle:
        fontWeight: '400'
        fontStyle: normal
        textAlign: center
        margin:
          - mt-0
          - mb-12
      actions:
        justifyContent: center
  - type: HeroSection
    elementId: ''
    colors: colors-h
    backgroundImage:
      elementId: ''
      styles:
        self:
          opacity: 100
      type: ImageBlock
    title: Become A Team Player
    text: >
      We are always looking for great people to join our team. If you are
      interested in working for Agency, please send an email to
      [email@example.com ](mailto:email@email.com)with your CV and which
      position you are interested in.
    feature:
      type: ImageBlock
      url: /images/cta-about.svg
      altText: Hero section image
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        fontWeight: '700'
        fontStyle: normal
        textAlign: left
        margin:
          - mt-0
          - mb-5
      subtitle:
        fontWeight: '400'
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
        margin:
          - mt-0
          - mb-8
      actions:
        justifyContent: flex-start
  - elementId: contact-form
    colors: colors-a
    title: Contact us
    text: We look forward to hearing from you.
    form:
      type: FormBlock
      elementId: contact-form
      action: /.netlify/functions/submission_created
      destination: ''
      fields:
        - type: TextFormControl
          name: name
          label: Name
          placeholder: Your name
          isRequired: true
          width: 1/2
        - type: EmailFormControl
          name: email
          label: Email
          placeholder: Your email
          isRequired: true
          width: 1/2
        - type: TextFormControl
          name: home-address
          label: Home address
          placeholder: Your home address
          isRequired: true
          width: full
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
      submitLabel: Send Message
    feature:
      type: ImageBlock
      url: /images/about.jpg
      altText: Contact us
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
    action: /.netlify/functions/submission_created
    type: ContactSection
  - elementId: ''
    colors: colors-a
    title: Testimonials
    subtitle: What they say about us
    testimonials:
      - quote: >-
          It is a long established fact that a reader will be distracted by the
          readable content of a page when looking at its layout.
        name: Hilary Ouse
        title: 'Co-Founder, Creative Director'
        image:
          type: ImageBlock
          url: /images/team-2.png
          altText: 'Co-Founder, Creative Director'
        styles:
          self:
            margin:
              - mt-0
              - mb-0
            flexDirection: row-reverse
          quote:
            textAlign: right
          name:
            fontWeight: 400
            fontStyle: normal
            textAlign: right
          title:
            fontWeight: 400
            fontStyle: normal
            textAlign: right
      - quote: >-
          Lorem Ipsum is simply dummy text of the printing and typesetting
          industry.
        name: Dianne Ameter
        title: 'Co-founder, Designer'
        image:
          type: ImageBlock
          url: /images/team-4.png
          altText: 'Co-founder, designer'
        styles:
          self:
            margin:
              - mt-0
              - mb-0
            flexDirection: row
          quote:
            textAlign: left
          name:
            fontWeight: 400
            fontStyle: normal
            textAlign: left
          title:
            fontWeight: 400
            fontStyle: normal
            textAlign: left
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
        margin:
          - mt-0
          - mb-0
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
        margin:
          - mt-0
          - mb-12
    type: TestimonialsSection
  - elementId: ''
    colors: colors-a
    title: The Section Title
    subtitle: The section subtitle
    text: |-
      Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium
      doloremque laudantium, totam rem aperiam. Eaque ipsa quae ab illo
      inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
      Sed ut perspiciatis undeomnis iste natus error sit voluptatem accusantium
      doloremque laudantium, totam rem aperiam. Eaque ipsa quae ab illo
      inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-neutral
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
        margin:
          - mt-0
          - mb-2
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
        margin:
          - mt-0
          - mb-6
      text:
        textAlign: center
        margin:
          - mt-0
          - mb-0
    type: TextSection
  - elementId: ''
    colors: colors-a
    title: The Section Title
    subtitle: The section subtitle
    text: |-
      Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium
      doloremque laudantium, totam rem aperiam. Eaque ipsa quae ab illo
      inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
      Sed ut perspiciatis undeomnis iste natus error sit voluptatem accusantium
      doloremque laudantium, totam rem aperiam. Eaque ipsa quae ab illo
      inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-neutral
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
        margin:
          - mt-0
          - mb-2
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
        margin:
          - mt-0
          - mb-6
      text:
        textAlign: center
        margin:
          - mt-0
          - mb-0
    type: TextSection
  - elementId: ''
    colors: colors-a
    backgroundImage:
      url: ''
      altText: ''
    title: Let's do this
    text: >-
      The Stackbit theme is flexible and scalable to every need. It can manage
      any layout and any screen.
    actions:
      - type: Button
        label: Try it now
        url: /about
        style: primary
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: CtaSection
  - elementId: ''
    colors: colors-a
    backgroundImage:
      url: ''
      altText: ''
    title: Let's do this
    text: >-
      The Stackbit theme is flexible and scalable to every need. It can manage
      any layout and any screen.
    actions:
      - type: Button
        label: Try it now
        url: /about
        style: primary
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: CtaSection
  - elementId: ''
    colors: colors-a
    title: Testimonials
    subtitle: What they say about us
    testimonials:
      - quote: >-
          It is a long established fact that a reader will be distracted by the
          readable content of a page when looking at its layout.
        name: Hilary Ouse
        title: 'Co-Founder, Creative Director'
        image:
          type: ImageBlock
          url: /images/team-2.png
          altText: 'Co-Founder, Creative Director'
        styles:
          self:
            margin:
              - mt-0
              - mb-0
            flexDirection: row-reverse
          quote:
            textAlign: right
          name:
            fontWeight: 400
            fontStyle: normal
            textAlign: right
          title:
            fontWeight: 400
            fontStyle: normal
            textAlign: right
      - quote: >-
          Lorem Ipsum is simply dummy text of the printing and typesetting
          industry.
        name: Dianne Ameter
        title: 'Co-founder, Designer'
        image:
          type: ImageBlock
          url: /images/team-4.png
          altText: 'Co-founder, designer'
        styles:
          self:
            margin:
              - mt-0
              - mb-0
            flexDirection: row
          quote:
            textAlign: left
          name:
            fontWeight: 400
            fontStyle: normal
            textAlign: left
          title:
            fontWeight: 400
            fontStyle: normal
            textAlign: left
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
        margin:
          - mt-0
          - mb-0
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
        margin:
          - mt-0
          - mb-12
    type: TestimonialsSection
  - elementId: contact-form
    colors: colors-a
    title: Contact us
    text: We look forward to hearing from you.
    form:
      type: FormBlock
      elementId: contact-form
      action: /functions/submission_created
      destination: ''
      fields:
        - type: TextFormControl
          name: name
          label: Name
          placeholder: Your name
          isRequired: true
          width: 1/2
        - type: EmailFormControl
          name: email
          label: Email
          placeholder: Your email
          isRequired: true
          width: 1/2
        - type: TextFormControl
          name: home-address
          label: Home address
          placeholder: Your home address
          isRequired: true
          width: full
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
      submitLabel: Send Message
    feature:
      type: ImageBlock
      url: /images/about.jpg
      altText: Contact us
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
    action: /.netlify/functions/submission_created
    type: ContactSection
  - elementId: ''
    variant: variant-b
    colors: colors-a
    title: About us
    subtitle: Meet the team
    actions: []
    people:
      - content/data/team/desmond-eagle.json
      - content/data/team/dianne-ameter.json
      - content/data/team/hilary-ouse.json
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-neutral
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
        margin:
          - mt-0
          - mb-2
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
        margin:
          - mt-0
          - mb-12
      actions:
        justifyContent: center
    type: FeaturedPeopleSection
layout: PageLayout
---
