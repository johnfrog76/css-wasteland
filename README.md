# css-wasteland

Build output only. There is no source code in this repo — it holds the compiled
static site that [GitHub Pages](https://johnfrog76.github.io/css-wasteland/)
serves, and nothing else.

Every file here is generated and overwritten on each deploy. Editing anything
in this repo, including this README, has no lasting effect: the next publish
replaces the working tree wholesale.

## What the site is

**The CSS Wasteland** — a blog where the unit of thought is a scene rather than
a paragraph. Slide decks about engineering, played one panel at a time, narrated
if you want them to be. Best consumed while you're waiting on a build.

## Want the engine?

The presentation engine these decks run on is open source and documented, in a
repo you can actually read:

**https://github.com/johnfrog76/connected-deck**

A slide there is just a React component, so it can render a live chart, call a
real API, or embed a piece of your own product's UI — rather than a screenshot
of one. Take it and build your own.

## How this repo gets built

A private toolkit builds the site and pushes the build output here. No CI runs in this
repo; there is nothing to build, only something to serve. That split is why the
source can stay private while the site stays free and public — Pages needs the
bundle, not the code, and the bundle is handed to every visitor's browser
anyway.