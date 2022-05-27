---
layout: collection
title: Section two
description: Section two description
related:
  items:
    - text: Prototype
      description: |
        Username: `username`
        Password: `password`
      href: https://#
    - text: More content
      href: /#
pagination:
  data: collections.section-two
  reverse: true
  size: 50
permalink: "section-two/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
override:tags:
  - post
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 2
---
