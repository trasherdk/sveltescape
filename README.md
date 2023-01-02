SvelteScape is a Storybook alternative made for Svelte. Its goal is to also allow managing very complex component, as seen in the [Shapes](https://story.bonfireleads.com/ShapesInteractive) example.

## Unique features
- Allows more complex data structures to be edited
- Prop pre- and post-processors, to move load from the svelte component to SvelteScape. Very useful in the shapes example, so you do not have to ship an entire SVG curve generator with negative runtime performance benefits. Instead, this generates the svg paths via the postprocessor.

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
