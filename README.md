To reproduce minify issue found:

```
pnpm add next@latest # any newer build (12.1.1/12.1.2/12.1.3/12.1.4/12.1.5.canary.x)
pnpm build
pnpm start
```

Then open `localhost:3000` and you'll see the following exception:

Note that this code works as is (on Next `12.1.0`)
