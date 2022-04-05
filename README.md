To reproduce minify issue found:

```
pnpm add next@latest # any newer release (12.1.1 / 12.1.2 /12.1.3 /12.1.4 / 12.1.5.canary.x)
pnpm build
pnpm start
```

Then open `localhost:3000` and you'll see the following exception:

<img src='https://github.com/hanford/bug-swcMinify-next-12.1.1/blob/master/failing-12.1.1.png' alt='preview gif' width='600px' />

Note that this code works as is (on Next `12.1.0`), on this version after running through the following:

```
pnpm build
pnpm start
```

I see:

<img src='https://github.com/hanford/bug-swcMinify-next-12.1.1/blob/master/working-12.1.0.png' alt='preview gif' width='600px' />
