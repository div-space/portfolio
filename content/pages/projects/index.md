---
type: ProjectFeedLayout
title: Projects
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/supriya-bhandari-0Uv_-KfgMwE-unsplash.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 4
projectFeed:
  type: ProjectFeedSection
  colors: colors-f
  showDate: false
  showDescription: false
  showReadMoreLink: true
  showFeaturedImage: true
  variant: variant-d
  styles:
    self:
      width: narrow
      padding:
        - pt-0
        - pl-4
        - pr-4
        - pb-12
  actions: []
topSections:
  - type: HeroSection
    title: Projects
    subtitle: ''
    actions: []
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-16
          - pb-16
          - pl-4
          - pr-4
        flexDirection: row
        textAlign: left
bottomSections:
  - type: FeaturedProjectsSection
    subtitle: 'Projects:'
    actions:
      - type: Link
        label: See all projects
        altText: See all projects
        url: /projects
        showIcon: false
        icon: arrowRight
        iconPosition: right
        elementId: ''
    projects:
      - content/pages/projects/project-one.md
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
    colors: colors-d
    variant: variant-b
    elementId: ''
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
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
  - type: LabelsSection
    title: 'You can find me here:'
    subtitle: ''
    items:
      - type: Label
        label: Instagram
        url: 'https://www.instagram.com/dv_design.space/'
      - type: Label
        label: Behance
        url: 'https://www.behance.net/divyarajsinhjhala'
      - type: Label
        label: Dribbble
        url: 'https://dribbble.com/Divyaraj'
    colors: colors-c
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-20
          - pb-20
          - pl-4
          - pr-4
        textAlign: center
---
