# tstypes

Personal repository of typescript definitions. These will override the typescript definitions provided by the library. 

They may also override what's in `@types/...`, but I haven't tested that yet.

## Setup

1. install via npm

```sh
npm install tstypes
```

2. configure `tsconfig.json`

```json
{
  "paths": {
    "*": [
      "node_modules/tstypes/*"
    ]
  }
}
```
