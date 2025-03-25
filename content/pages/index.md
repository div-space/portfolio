---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/34_1750.png
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 100
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: Computer Engineering graduate with +4 years in Experience Design.
    subtitle: >-
      I grew up in the white desert of kutch, surrounded by nature’s raw beauty
      and the rich tapestry of culture, craftsmanship, and storytelling. I
      collaborate with problem solvers, utilizing various design disciplines
      with the ability to adapt to roles. When I'm not designing, you'll find me
      reading, playing football, or sketching - activities that inspire my
      creativity and keep me balanced.
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
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        flexDirection: row-reverse
        textAlign: left
        borderColor: border-(--theme-secondary)
        borderStyle: solid
    type: HeroSection
    actions:
      - type: Button
        label: Find my resume here
        altText: resume download
        url: >-
          /https://drive.google.com/drive/u/1/folders/1vrNy7zwwwzAoV2YtyUndKubhkFSxQo0X
        showIcon: false
        icon: ''
        iconPosition: right
        style: primary
        elementId: ''
    text: |
      Toronto, ON
  - type: MediaGallerySection
    title: I worked with these
    subtitle: ''
    images:
      - type: ImageBlock
        url: /images/logo1.svg
        altText: logo one
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/logo2.svg
        altText: logo two
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/logo3.svg
        altText: logo three
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/logo4.svg
        altText: logo four
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/logo5.svg
        altText: logo five
        caption: Caption of the image
        elementId: ''
    colors: colors-f
    spacing: 16
    columns: 5
    aspectRatio: '16:9'
    showCaption: true
    enableHover: false
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        textAlign: center
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        textAlign: left
    subtitle: Projects
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Featured Posts
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        textAlign: left
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project? Tell me more...\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        self:
          textAlign: center
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
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
---
