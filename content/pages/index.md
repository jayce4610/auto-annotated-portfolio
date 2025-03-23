---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-c
    backgroundSize: full
    title: >-
      I'm Siew Hui, a Graphic Designer transitioning into UI/UX to create
      intuitive and engaging digital experiences.
    subtitle: >-
      With over 6 years of graphic design experience, specializing in social
      media ads and short videos. Driven by a passion for user-friendly design,
      I am transitioning into UI/UX design to craft intuitive and engaging
      digital interfaces that enhance user experiences and deliver results.
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
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions:
      - type: Button
        label: my projects
        altText: ''
        url: /projects
        showIcon: true
        icon: arrowRightCircle
        iconPosition: right
        style: secondary
        elementId: ''
    text: ''
  - type: FeaturedProjectsSection
    subtitle: UI UX Design
    actions:
      - type: Link
        label: See all projects
        altText: See all projects
        url: /projects
        showIcon: true
        icon: arrowRightCircle
        iconPosition: right
        elementId: ''
    projects:
      - content/pages/projects/project-one.md
      - content/pages/projects/go-diary.md
      - content/pages/projects/website-roar-bike.md
    colors: colors-c
    variant: variant-b
    elementId: ''
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: false
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-9
          - pb-14
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: center
---
