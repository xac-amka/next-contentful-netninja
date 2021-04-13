This is the Next.js starter site (and course files) for the Next.js & Contentful tutorial by the Net Ninja.

## Getting Started

To use the starter project, run the following in a terminal:

```bash
npx create-next-app [your-site-name] -e https://github.com/iamshaunjp/next-contentful/tree/lesson-1-starter-site
```

## Incremental Static Regenration

Next.js generates new pages & regenerates current pages on the fly when data is updated

Update the marmite stew recipe on CONTENTFUL
 - There is no change on first visit after the current is changed
 - The page triggers Next.js to re-fetch the page data in the bg
 - The static page is regenerated ready for the next visit