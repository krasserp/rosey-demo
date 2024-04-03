---
title: Home
seo:
  page_description: >-
    A multilingual site, made using a translation workflow with Rosey in
    CloudCannon.
  canonical_url:
  featured_image:
  featured_image_alt:
  author_twitter_handle:
  open_graph_type:
  no_index: false
content_blocks:
  - _bookshop_name: hero
    heading: Hugo Rosey Demo
    text: >-
      A demonstration of how Hugo and Rosey work in CloudCannon. This site has
      extra setup so that we can enter translations via the CloudCannon GUI.
      Additional languages can be set in the environment variables in
      CloudCannon's build configuration.
    button:
      _bookshop_name: global/button
      path: https://rosey.app/
      button_text: Read More
      button_text_color: '#ffffff'
      button_color: '#034ad8'
  - _bookshop_name: left-right
    heading: Keep what you need. Delete the rest.
    text: >-
      Make your own copy of this repository. Reference it or use it as a
      template to get up and running with translation workflows in CloudCannon
      using Rosey.
    button:
      _bookshop_name: global/button
      path: https://github.com/tomrcc/hugo-rosey-demo
      button_text: Read More
      button_text_color: '#ffffff'
      button_color: '#034ad8'
    image: /images/transparent-bg/undraw-hello.svg
    image_alt:
  - _bookshop_name: left-right
    heading: Integrate with an external translation service
    text: >-
      This site is set up to allow for translations in the CloudCannon GUI. If
      you would rather use an external translation service to translate for you,
      Rosey can do that too! In most cases this will involve building some
      middleware that uploads the strings from your base.json to a translation
      API (e.g. Smartling), and creates rosey/locales/example.json files with
      the translated response.
    button:
      _bookshop_name: global/button
      path: https://rosey.app/docs/#creating-locale-files
      button_text: Read More
      button_text_color: '#ffffff'
      button_color: '#034ad8'
    image: /images/transparent-bg/undraw-data-input.svg
    image_alt:
---
