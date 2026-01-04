---
title: Field
description: 
published: undefined
---


## Usage

::stack
  ::div{class="p-4"}
    ::field{name="Field" type="string" defaultValue="'default'" required}
    The _description_ can be set as prop or in the default slot with full **markdown** support.
    ::
  ::
  ```mdc
  ::field{name="Field" type="string" defaultValue="'default'" required}
  The _description_ can be set as prop or in the default slot with full **markdown** support.
  ::
  ```
::

The text `required` is configurable in [`main.fieldRequiredText`](/api/configuration/shadcn-docs#main).

## Props

::field-group
  :field{name="name" type="string"}[Field name]
  :field{name="type" type="string"}[Field type]
  :field{name="description" type="string"}[Field description]
  :field{name="defaultValue" type="string"}[Field default value]
  :field{name="required" type="boolean"}[Whether the field is required]
::
