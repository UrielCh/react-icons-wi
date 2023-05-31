# Weather Icons icons for deno / Preact

**License** [SIL OFL 1.1](http://scripts.sil.org/OFL)

**Project** [https://erikflowers.github.io/weather-icons/](https://erikflowers.github.io/weather-icons/)

[See available icons here](https://react-icons.github.io/react-icons/icons?name=wi)

## import_map.json

For a transparent usage:

```json
{
  "imports": {
    "preact":  "https://esm.sh/preact@10.15.1",
    "preact/": "https://esm.sh/preact@10.15.1/",
    "react-icons/wi":  "https://cdn.jsdelivr.net/gh/urielch/react-icons-wi@1.0.6/mod.ts",
    "react-icons/wi/": "https://cdn.jsdelivr.net/gh/urielch/react-icons-wi@1.0.6/ico/",
  }
}
```

## Direct import sample

```ts
import { WiAlien } from "https://deno.land/x/react_icons_wi@1.0.6/mod.ts"
```

## import_map import sample

```ts
import { WiAlien } from "react-icons/wi"
```

## minimal import

```ts
import { WiAlien } from "react-icons/wi/WiAlien.ts"
```

## minimal import using default export

```ts
import WiAlien from "react-icons/wi/WiAlien.ts"
```

