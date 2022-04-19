---
layout: collection
title: Section one
description: Section one description
related:
  items:
    - text: Prototype
      description: |
        Username: `apply`
        Password: `bat`
      href: https://support-for-apply-prototype.herokuapp.com
    - text: User needs
      href: /support-for-apply/user-needs
pagination:
  data: collections.section-one
  reverse: true
  size: 50
permalink: "section-one/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
override:tags:
  - post
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 6
---
