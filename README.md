# Weather Icons icons for preact

[![JSR](https://jsr.io/badges/@preact-icons/wi)](https://jsr.io/@preact-icons/wi)

**License** [SIL OFL 1.1](http://scripts.sil.org/OFL)

**Project** [https://erikflowers.github.io/weather-icons/](https://erikflowers.github.io/weather-icons/)

[See available icons here](https://react-icons.deno.dev/wi)

## import_map.json

For a transparent usage:

```json
{
  "imports": {
    "@preact-icons/common": "jsr:@preact-icons/common@^1.0.10",
    "preact": "npm:preact@10.22.1",
    "preact/jsx-runtime": "npm:preact@10.22.1/jsx-runtime",
    "preact/hooks": "npm:preact@10.22.1/hooks",
    "react-icons/wi": "jsr:@preact-icons/wi@^1.0.11/mod.ts",
    "react-icons/wi/": "jsr:@preact-icons/wi@^1.0.11/ico/",
  }
}
```

## Import an icon without import_map by and afer loading all icons from the lib wi

```ts
import { WiAlien } from "jsr:preact-icons/wi@1.0.11/mod.ts"
```

## import_map import an icon from all icons

```ts
import { WiAlien } from "react-icons/wi"
```

## import a single icon, downloading just one icon

```ts
import { WiAlien } from "react-icons/wi/WiAlien.ts"
```

or using default export

```ts
import WiAlien from "react-icons/wi/WiAlien.ts"
```

