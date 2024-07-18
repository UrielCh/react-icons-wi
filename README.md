# Weather Icons icons for preact

[![JSR](https://jsr.io/badges/@preact-icons/wi)](https://jsr.io/@preact-icons/wi)

**License** [SIL OFL 1.1](http://scripts.sil.org/OFL)

**Project** [https://erikflowers.github.io/weather-icons/](https://erikflowers.github.io/weather-icons/)

[See available icons here](https://react-icons.deno.dev/wi)

## install the module

```bash
deno add @preact-icons/wi
dnpx jsr add @preact-icons/wi
pnpm dlx jsr add @preact-icons/wi
bunx jsr add @preact-icons/wi
```

You may need to update your preact mapping to avoid mixing JSR and http import:
Currently Deno fresh import preact using https://esm.sh/preact http import can not be mixed with JSR package, so you may need to update your preact mapping:
```json
{
 "preact": "npm:preact@10.22.1",
 "preact/jsx-runtime": "npm:preact@10.22.1/jsx-runtime",
 "preact/hooks": "npm:preact@10.22.1/hooks",
}
```

## import an icon from all icons

```ts
import { WiAlien } from "@preact-icons/wi"
```

## import a single icon, downloading just one icon

```ts
import { WiAlien } from "react-icons/wi/WiAlien"
```

or using default export

```ts
import WiAlien from "react-icons/wi/WiAlien.ts"
```
