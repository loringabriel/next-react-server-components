# Next.js 12 React Server Components Demo (Alpha)

First look on React Server components.

## SSR vs RSC

Examples with `Fast3G`

**SSR** - page is build complete on the server and then it get sent to client

https://user-images.githubusercontent.com/28633412/161990116-10094794-aa94-4847-9c9e-302dc6f7c808.mov

---

**Server Components** - server start to build the page and then start sending ready components to the client

https://user-images.githubusercontent.com/28633412/161990196-a69b94b8-bcfe-48f9-9bf1-38b886e83215.mov


## Introduction

This is a demo app of the Hacker News website clone, which shows Next.js 12's experimental React Server Components support. We recommend you taking a look at these links, before trying out the experimental feature:
- [**Introducing Zero-Bundle-Size React Server Components**](https://reactjs.org/blog/2020/12/21/data-fetching-with-react-server-components.html)
- [**Everything About React Server Components**](https://vercel.com/blog/everything-about-react-server-components)
- [**Docs of React Server Components in Next.js**](https://nextjs.org/docs/advanced-features/react-18#react-server-components)

This demo is built for showing what features that Server Components provide and what the application structure might look like. **It's not ready for production adoption, or performance benchmarking** as the underlying APIs are not stable yet, and might change or be improved in the future.

## Technical Details

This Next.js application uses React 18 (RC build) and the new [Edge Runtime](https://nextjs.org/docs/api-reference/edge-runtime). It has `runtime` set to `'edge'` and feature flag `serverComponents` enabled. You can check out [next.config.js](https://github.com/vercel/next-react-server-components/blob/main/next.config.js) for more details.

### Running Locally

1. `yarn install`
2. `yarn dev`

Go to `localhost:3000`.

### Deploy

You can quickly deploy the demo to Vercel by clicking this link:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https%3A%2F%2Fgithub.com%2Fvercel%2Fnext-react-server-components&project-name=next-react-server-components&repo-name=next-react-server-components&demo-title=React%20Server%20Components%20(Experimental%20Demo)&demo-description=Experimental%20demo%20of%20React%20Server%20Components%20with%20Next.js.%20&demo-url=https%3A%2F%2Fnext-rsc-hn.vercel.app&demo-image=https%3A%2F%2Fnext-server-components.vercel.app%2Fog.png)

## License

This demo is MIT licensed.
