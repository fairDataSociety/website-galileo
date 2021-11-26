---
layout: blocks
title: Homepage
date: 2021-10-03T22:00:00.000+00:00
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "/uploads/2021/11/26/logo6galileo-mini.png"
  navigation:
  - link: "/"
    link_text: Home
  - link: contribute-maps
    link_text: Contribute maps
  cta:
    url: https://app.galileo.fairdatasociety.org
    button_text: Try out Galileo Maps
- template: hero-banner-w-image
  block: hero-2
  slug: features
  headline: We can build the<br><strong>new world.</strong>
  content: A fair and free one.
  cta:
    enabled: false
    url: https://github.com/forestryio/ubuild-jekyll
    button_text: 'See on GitHub '
  image:
    image: ''
    alt_text: ''
    show_image: false
  background_image: "/uploads/2021/10/01/nasa-yzygonrube8-unsplash.jpg"
- template: 1-column-text
  block: one-column-1
  slug: world-as-you-want-it
  headline: Project Galileo - The world as you want to see it.
  content: 'The World is not one, the Worlds are many. '
- template: 3-column-text
  block: three-column-1
  col_1:
    headline: Start with Mother Earth.
    slug: ''
    content: <img src="/uploads/2021/11/26/mother-earthgalileo-mini.png">
  col_2:
    headline: Add layers on top.
    slug: ''
    content: <img src="/uploads/2021/11/26/layers-2galileo-mini.png">
  col_3:
    headline: Move to other worlds.
    slug: ''
    content: <img src="/uploads/2021/11/26/other-worlds-3galileo-mini.png">
- template: content-feature
  block: feature-1
  media_alignment: Left
  slug: mother-earth
  headline: Start with mother Earth
  content: Run your own node and become a country maintainer. Try out how the incentive
    system will reward your efforts.<br><br>TODO ADD LINK TO INSTRUCTIONS
  media:
    image: "/uploads/2021/11/26/mother-earthgalileo.svg"
    alt_text: The planet is ours to map.
- template: content-feature
  block: feature-1
  media_alignment: Right
  slug: layers
  headline: Add layers on top
  content: Make a layer to be used with the maps and share it with the community.
  media:
    image: "/uploads/2021/11/26/layers-2galileo.svg"
    alt_text: Customize Blocks
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: Move to other worlds
  content: Build an app and use the maps and layers provided.
  media:
    image: "/uploads/2021/11/26/other-worlds-3galileo.svg"
    alt_text: ''
  slug: metaverse
- template: 1-column-text
  block: one-column-1
  headline: Powered by OpenStreetMap data and using Swarm decentralized storage.
  content: Thanks to the community efforts behind <a href="https://www.openstreetmap.org/"
    title="OpenStreetMap">OpenStreetMap</a>, maps of the world are already freely
    available. <br><br>Using <a href="https://www.ethswarm.org/" title="Swarm">Swarm</a>
    storage via <a href="https://github.com/fairDataSociety/fairOS-dfs" title="FairOS-dfs">FairOS-dfs</a>,
    the data can be hosted by peers, compensating them for the provided storage and
    bandwidth.
  slug: powered-by
- template: simple-footer
  block: footer-1
  content: Made with ❤︎ by <a href="https://fairdatasociety.org/" title="Fair Data
    Society">Fair Data Society</a>.

---
