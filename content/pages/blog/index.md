---
title: Product
slug: /blog
numOfPostsPerPage: 8
enableSearch: true
topSections:
  - title:
      text: Featured Post
      color: text-dark
      type: TitleBlock
    subtitle: This is the subtitle
    posts:
      - content/pages/blog/top-ten-lessons-we-learned.md
    showThumbnail: true
    showExcerpt: true
    showDate: true
    showAuthor: true
    variant: big-list
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-28
          - pb-0
          - pl-4
          - pr-4
        justifyContent: flex-start
    type: FeaturedPostsSection
    hoverEffect: move-up
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Items on sale
      color: text-dark
      styles:
        self:
          textAlign: center
    items:
      - type: FeaturedItem
        title: Faux Fur Throw
        subtitle: $ 88 – $ 176
        text: >+
          Available in a range of colors and patterns, we make it easy to pick
          the perfect look for you.




          Our faux fur is incredibly soft, plush and oh-so inviting. It's like
          the real deal (but better)!



        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Faux Fur Throw
          elementId: ''
          styles:
            self:
              borderRadius: medium
              padding:
                - pt-0
                - pl-0
                - pb-0
                - pr-0
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pl-6
              - pb-6
              - pr-6
            textAlign: left
            borderColor: border-neutralAlt
            borderWidth: 2
            borderRadius: x-small
            flexDirection: row-reverse
            justifyContent: center
            borderStyle: dotted
      - type: FeaturedItem
        title: Cotton Knit Throws
        subtitle: $ 44.99 – $ 90
        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Cotton Knit Throws
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            flexDirection: row
      - type: FeaturedItem
        title: Chunky Cotton Knit Throw
        subtitle: $117
        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Chunky Cotton Knit Throw
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            flexDirection: row
    actions: []
    elementId: ''
    variant: small-list
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-0
          - pl-0
          - pb-0
          - pr-0
        justifyContent: center
      subtitle:
        textAlign: center
styles:
  title:
    textAlign: center
seo:
  metaTitle: Blog - Demo site
  metaDescription: >-
    This is the blog of the demo site where we post about technology, product,
    and design.
  socialImage: /images/img-placeholder.svg
  type: Seo
type: PostFeedLayout
bottomSections: []
postFeed:
  type: PagedPostsSection
  title: null
  subtitle: null
  showThumbnail: true
  showExcerpt: true
  showDate: true
  showAuthor: true
  actions: []
  elementId: null
  variant: three-col-grid
  colors: bg-light-fg-dark
  hoverEffect: move-up
---
