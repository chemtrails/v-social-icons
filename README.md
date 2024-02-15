# v-social-icons

~ 150 [simple-icons](https://github.com/simple-icons/simple-icons) of social media brands and other apps in one Vue component.

```
npm i v-social-icons
```

## example

Icons inherit color.
If the brand isn't found, error is emitted.

```vue
<template>
    <SocialIcon brand="instagram" @error="handleError"></SocialIcon>
</template>
```

## props

prop | type | default
------|------|--------
brand | string |
size | number | 24
