# @natsuneko-laboratory/vite-plugin-next-directives

Support use client/server directives in Vite

## Installation

```bash
$ npm install @natsuneko-laboratory/vite-plugin-next-directives
```

## Usage

Add `directives()` to your Vite configuration:

```typescript
// vite.config.ts
import { defineConfig } from "vite";
import { directives } from "@natsuneko-laboratory/vite-plugin-next-directives";

export default defineConfig({
  plugins: [...directives()],
});
```

## License

MIT by [@6jz](https://to.natsuneko.com/6jz)
