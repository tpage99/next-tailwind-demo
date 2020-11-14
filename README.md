Playing around with this demo and working through Next.js docs. Finished the tutorial and evaluating CMSs - good stuff!

## Progress:

**8/20/2020**  
Starting to implement [Framer](https://www.framer.com/api/) for motion/animation

Having a lot of trouble with [Strapi](https://strapi.io/documentation/v3.x/) deleting content types after first creation and not being able to access content types. Had to blow it up and start over twice with the same issue. Somehow this screwed up my .zshrc file and had to completely reinstall node with homebrew twice.

Got Strapi figured out and working. Downloaded a repo from Next.js built for Next, BUT, seems like they built it to develop quickly with other CMSs. Worthwhile to figure out and implement various headless CMS solutions to iterate quickly. Could determine if Strapi is best to work with or Sanity may still be a better bet. Also saw a demo of Prismic earlier today that looked great.  

**11/14/2020**  
Decided against using Framer. Had a lot of fun stuff in it but there really isn't the need to implement at the moment. Plus Tailwind has animations that I feel like are sufficient to meet those needs anyways.  

Am needing to update a website for a portfolio and this is going to get used rather than trying to implement an Eleventy site like I originally thought I was going to do. Thought about doing a Vue.js site since I've been doing more Shopify stuff and seems like everyone uses Vue with Shopify rather than React. But, I know React better so that's what I'm going with for a portfolio site. Eventually might implement a CMS but for now, at least for me, Markdown is super simple and easy to update.

# Tailwind CSS example

This is an example of using [Tailwind CSS](https://tailwindcss.com) in a Next.js project.

## Deploy your own

Deploy the example using [Vercel](https://vercel.com):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/vercel/next.js/tree/canary/examples/with-tailwindcss)

## How to use

### Using `create-next-app`

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```bash
npx create-next-app --example with-tailwindcss with-tailwindcss-app
# or
yarn create next-app --example with-tailwindcss with-tailwindcss-app
```

### Download manually

Download the example:

```bash
curl https://codeload.github.com/vercel/next.js/tar.gz/canary | tar -xz --strip=2 next.js-canary/examples/with-tailwindcss
cd with-tailwindcss
```

Install it and run:

```bash
npm install
npm run dev
# or
yarn
yarn dev
```

Deploy it to the cloud with [Vercel](https://vercel.com/import?filter=next.js&utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment)).

## Notes

This example is a basic starting point for using [Tailwind CSS](https://tailwindcss.com) with Next.js. It includes the following [PostCSS](https://github.com/postcss/postcss) plugins:

- [postcss-preset-env](https://preset-env.cssdb.org/) - Adds stage 2+ features and autoprefixes

To control the generated stylesheet's filesize, this example uses Tailwind CSS' [`purge` option](https://tailwindcss.com/docs/controlling-file-size/#removing-unused-css) to remove unused CSS.
