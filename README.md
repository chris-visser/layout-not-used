# TODO

- Form control should "register" a field so the field can determine how to reset to a given default etc
- Reset should reset fields to their original value instead of emptying






- Form owns the values of each field

```vue
<script setup lang="ts">
  const doc = {}
</script>

<template>
  <SimpleForm v-model="doc">
    
  </SimpleForm>
</template>
```

- Form owns the errors of each field
- Form provides a reactive value<unknown | undefined> to each field
- Form provides a reactive error<string | undefined> to each field

- ZodForm accepts a schema for validation



- When a field is loaded, it "registers" at the form by setting `setField(props)`