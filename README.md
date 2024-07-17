# Weather Icons icons for deno / Preact

**License** [SIL OFL 1.1](http://scripts.sil.org/OFL)

**Project** [https://erikflowers.github.io/weather-icons/](https://erikflowers.github.io/weather-icons/)

[See available icons here](https://react-icons.deno.dev/wi)

## import_map.json

For a transparent usage:

```json
{
  "imports": {
    "preact":  "https://esm.sh/preact@10.22.1",
    "preact/": "https://esm.sh/preact@10.22.1/",
    "react-icons/wi":  "https://cdn.jsdelivr.net/gh/urielch/react-icons-wi@1.0.10/mod.ts",
    "react-icons/wi/": "https://cdn.jsdelivr.net/gh/urielch/react-icons-wi@1.0.10/ico/",
  }
}
```

## Import an icon without import_map by and afer loading all icons from the lib wi

```ts
import { WiAlien } from "https://deno.land/x/react_icons_wi@1.0.10/mod.ts"
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

