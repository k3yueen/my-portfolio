# create-svelte

Everything you need to start yet another Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte). 
Because reinventing the wheel every time os inefficient and exhausting

## Creating a project

If you're seeing this, you probably already did this part. Good for you

```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

## Developing

After creating the project and installing dependencies (you know the drill: npm install, or pnnm or yarn if youre feeling quirky) start the dev server:

```bash
npm run dev

# or open it in a browser too if youre into that kind of automation
npm run dev -- --open
```

## Building

For when youre pretending its ready for production:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> Deployment requires an adapter [adapter](https://kit.svelte.dev/docs/adapters) Pick one that makes sense or not. It's your app
