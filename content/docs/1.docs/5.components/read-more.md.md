---
title: Read More
description: 
published: undefined
---


## Usage

::stack
  ::div{class="p-4"}
    :read-more{to="/getting-started/writing/markdown"}
    :read-more{title="Nuxt website" to="https://nuxt.com/"}
    :read-more{to="https://nuxt.com/"}
    :read-more{icon="lucide:link" to="https://nuxt.com/"}
  ::

  ```mdc
  :read-more{to="/getting-started/writing/markdown"}
  :read-more{title="Nuxt website" to="https://nuxt.com/"}
  :read-more{to="https://nuxt.com/"}
  :read-more{icon="lucide:link" to="https://nuxt.com/"}
  ```
::

## Props

::field-group
  :field{name="title" type="string"}[Read More title]
  :field{name="icon" type="string"}[Read More icon]
  :field{name="to" type="string"}[Link URL]
  :field{name="target" type="Target"}[A `target` attribute value to apply on the link]
::
