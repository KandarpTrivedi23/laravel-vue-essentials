## Suspense

**Suspense** helps with managing asynchronous components by allowing you to display fallback content while the actual component is loading. This is useful for improving user experience, especially when data fetching or component rendering takes time.

## How These Features Improve Your Application

Suspense improves the user experience by providing smooth loading states, keeping the UI responsive even during complex data loads.

Together, Teleport and Suspense features help you create polished and efficient Vue 3 applications.

## Example:
You can use `Suspense` to display loading indicators or placeholders while waiting for a component dependent on external data.

```vue
<template>
  <Suspense>
    <template #default>
      <DataDependentComponent />
    </template>
    <template #fallback>
      <div>Loading...</div>
    </template>
  </Suspense>
</template>


