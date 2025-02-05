---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: CZEŚĆ JESTEM OLA
      color: text-dark
      type: TitleBlock
    subtitle: >-
      Na tej stronie znajdziecie wszystko o moich ulubionych książkach i nie
      tylko
    text: >+
      Czytanie to podróż, która nie ma końca. Witaj na stronie, gdzie miłość do
      literatury łączy się z pasją do odkrywania nowych historii. Prezentujemy
      recenzje, analizy i ciekawostki o książkach, które inspirują, poruszają i
      zmieniają sposób myślenia.


      Niezależnie od tego, czy kochasz klasykę, fantastykę, thrillery czy
      literaturę współczesną – znajdziesz tutaj coś dla siebie!



    actions: []
    media:
      altText: ''
      elementId: ''
      type: ImageBlock
      styles:
        self:
          borderRadius: x-large
    badge:
      label: Książkowe mole
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - type: FeaturedItemsSection
    title:
      text: Korzyści z czytania książek
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Rozwój intelektualny i wiedzy
        subtitle: ''
        text: >+

          Książki poszerzają horyzonty, wzbogacają słownictwo i rozwijają
          zdolność analitycznego myślenia. Dzięki nim możemy zdobywać nową
          wiedzę i lepiej rozumieć świat.

        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          styles:
            self:
              borderRadius: x-large
      - title: Poprawa koncentracji i redukcja stresu
        subtitle: ''
        text: |2+

           Regularne czytanie wzmacnia zdolność skupienia się na jednej czynności przez dłuższy czas. Ponadto literatura pomaga się odprężyć, redukując poziom stresu i poprawiając samopoczucie.

        image:
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: Rozwój empatii i wyobraźni
        subtitle: ''
        text: >
          Wcielając się w bohaterów literackich, lepiej rozumiemy ich emocje i
          motywacje. To zwiększa naszą empatię oraz kreatywność.
        image:
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions: []
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-4
          - pl-3
          - pb-3
          - pr-3
  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-4
          - pl-4
          - pb-4
          - pr-4
        justifyContent: center
        margin:
          - ml-0
    type: FeaturedPostsSection
    hoverEffect: move-up
    title:
      type: TitleBlock
      text: '                         Moje TOP 3'
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: ''
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Co następnego przeczytać?
      color: text-dark
      type: TitleBlock
    subtitle: Daj mi pomysł a napewno pojawi sie na moim blogu!
    text: ''
    media:
      fields:
        - name: Imię
          label: Imię
          hideLabel: true
          placeholder: Imię
          isRequired: true
          width: full
          type: TextFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Napisz wiadomość!
          width: full
          type: TextareaFormControl
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
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Wyślij
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-neutral-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
