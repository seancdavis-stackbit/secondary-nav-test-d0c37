---
metaTitle: null
metaDescription: null
addTitleSuffix: true
socialImage: null
metaTags: []
title: Example Preset
colors: colors-c
backgroundImage:
  url: /images/bg2.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 80
sections:
  - colors: colors-c
    elementId: ''
    backgroundSize: full
    title: This page is an example that we're going to use to create a preset
    subtitle: >-
      Veniam eiusmod laborum elit sunt elit cillum tempor anim est nulla
      excepteur elit. Sint minim in est consequat. Cupidatat do nulla amet Lorem
      irure magna duis. Amet nulla exercitation non quis tempor irure sit
      pariatur deserunt duis laborum sunt.
    text: ''
    actions:
      - type: Button
        label: Do Something Important
        showIcon: true
        icon: arrowRight
        style: primary
        url: /
    media:
      type: ImageBlock
      url: /images/about.jpg
      altText: Hero image
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
  - colors: colors-f
    elementId: ''
    title: Image Gallery
    subtitle: This tells you about these super cool images below.
    images:
      - type: ImageBlock
        url: /images/gallery-1.jpg
        altText: Image one
        caption: Image one caption
      - type: ImageBlock
        url: /images/gallery-2.jpg
        altText: Image two
        caption: Image two caption
      - type: ImageBlock
        url: /images/gallery-3.jpg
        altText: Image three
        caption: Image three caption
      - type: ImageBlock
        url: /images/gallery-4.jpg
        altText: Image four
        caption: Image four caption
    spacing: 16
    columns: 4
    aspectRatio: '4:3'
    showCaption: false
    enableHover: true
    styles:
      self:
        height: auto
        width: full
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
      title:
        textAlign: center
      subtitle:
        textAlign: center
    type: MediaGallerySection
layout: PageLayout
---
