# Setup

in svelte directory run

```
npm i (pnpm i)
npm run build
```

in root directory

```
neu update
```

# Dev

in svelte directory run

```
npm run dev
```

then in root directory run

```
neu run --frontend-lib-dev
```

# Build

before
in index.html ensure the neutralino script tag is

<script src="/neutralino.js"></script>

in svelte diretory run

```
npm run build
```

then in root directory run

```
neu build
```
