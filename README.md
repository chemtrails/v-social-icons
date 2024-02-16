# v-social-icons

About 120 [simple-icons](https://github.com/simple-icons/simple-icons) of social media brands in one Vue component.

```
npm i v-social-icons
```

## example

```vue
<template>
    <SocialIcon brand="instagram" @error="handleError"></SocialIcon>
</template>

<script setup>
    import { SocialIcon } from 'v-social-icons'
</script>
```

## props

prop | type | default
------|------|--------
brand | string |
size | number | 24
