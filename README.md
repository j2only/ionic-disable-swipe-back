# @j2only/ionic-disable-swipe-back

 ![npm publish](https://github.com/j2only/ionic-disable-swipe-back/actions/workflows/npm.yml/badge.svg) [![npm](https://img.shields.io/npm/v/@j2only/ionic-disable-swipe-back.svg)](https://www.npmjs.com/package/@j2only/ionic-disable-swipe-back) ![npm bundle size (scoped)](https://img.shields.io/bundlephobia/minzip/%40j2only/ionic-disable-swipe-back) ![CodeFactor Grade](https://img.shields.io/codefactor/grade/github/j2only/ionic-disable-swipe-back) [![TypeScript](https://img.shields.io/badge/%3C%2F%3E-TypeScript-%230074c1.svg)](https://www.typescriptlang.org/) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/j2only/ionic-disable-swipe-back/issues) ![GitHub](https://img.shields.io/github/license/j2only/ionic-disable-swipe-back)

## Installation

Install this component via package manager:

```bash
yarn add @j2only/ionic-disable-swipe-back
```

## Usage

Import the component in your app. Example of the main.ts file in your ionic vue project:

```typescript
<script setup lang="ts">
import App from "./App.vue"

import { DisableSwipeBackDirective } from "@j2only/ionic-disable-swipe-back"

const app = createApp(App)
    .directive("disable-swipe-back", DisableSwipeBackDirective)
app.mount("#app")
</script>
```

In vue template include directive in ion-page

```vue
<template>
    <ion-page v-disable-swipe-back>
        ...
    </ion-page>
</template>
```

## Licensing

MIT License
Forked from [@Sitronik/v-disable-swipe-back](https://github.com/Sitronik/v-disable-swipe-back), Sitronik, [MIT License](LICENSE)
