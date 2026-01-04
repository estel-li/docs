---
title: Code Group
description: 
published: undefined
---


## Usage

::stack
  ::div{class="p-4"}
    ::code-group
      ```vue [app.vue]
      <template>
        <div>
          <NuxtLayout>
            <NuxtPage />
          </NuxtLayout>
        </div>
      </template>
      ```

      ```vue [pages/index.vue]
      <template>
        <div>
          <h1>Welcome to the homepage</h1>
          <AppAlert>
            This is an auto-imported component
          </AppAlert>
        </div>
      </template>
      ```
    ::
  ::

  ```mdc
  ::code-group
    ```vue [app.vue]
    <template>
      <div>
        <NuxtLayout>
          <NuxtPage />
        </NuxtLayout>
      </div>
    </template>
    ```

    ```vue [pages/index.vue]
    <template>
      <div>
        <h1>Welcome to the homepage</h1>
        <AppAlert>
          This is an auto-imported component
        </AppAlert>
      </div>
    </template>
    ```
  ::
  ```
::

::alert{to="/components/docs/tabs"}
`::code-group`{lang="mdc"} is a wrapper around `::tabs{variant="card"}`{lang="mdc"}.
::

## Props

:field{name="sync" type="string"}[Sync scope for `::tabs`]
