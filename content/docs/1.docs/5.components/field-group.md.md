---
title: Field Group
description: 
published: undefined
---


## Usage

::stack
  ::div{class="p-4"}
    ::field-group
      ::field{name="withDefault" type="boolean" defaultValue="true"}
      A field with a default value.
      ::
      ::field{name="requiredField" type="boolean" required}
      A required field.
      ::
      ::field{name="clear (path?: string)" type="void"}
      Clears form errors associated with a specific path. If no path is provided, clears all form errors.
      ::
      ::field{name="getErrors (path?: string)" type="FormError[]"}
      Retrieves form errors associated with a specific path. If no path is provided, returns all form errors.
      ::
      ::field{name="setErrors (errors: FormError[], path?: string)" type="void"}
      Sets form errors for a given path. If no path is provided, overrides all errors.
      ::
      ::field{name="errors" type="Ref<FormError[]>"}
      A reference to the array containing validation errors. Use this to access or manipulate the error information.
      ::
    ::
  ::

  ```mdc
  ::field-group
    ::field{name="withDefault" type="boolean" defaultValue="true"}
    A field with a default value.
    ::
    ::field{name="requiredField" type="boolean" required}
    A required field.
    ::
    ::field{name="clear (path?: string)" type="void"}
    Clears form errors associated with a specific path. If no path is provided, clears all form errors.
    ::
    ::field{name="getErrors (path?: string)" type="FormError[]"}
    Retrieves form errors associated with a specific path. If no path is provided, returns all form errors.
    ::
    ::field{name="setErrors (errors: FormError[], path?: string)" type="void"}
    Sets form errors for a given path. If no path is provided, overrides all errors.
    ::
    ::field{name="errors" type="Ref<FormError[]>"}
    A reference to the array containing validation errors. Use this to access or manipulate the error information.
    ::
  ::
  ```
::
