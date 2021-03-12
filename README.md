# DocsifyJS Tutorial - SSR
> Use Server-Side Rendering to make an SEO-friendly version of a DocsifyJS Tutorial


## Note

I've discontinued due to bugs - https://github.com/docsifyjs/docsify-cli/issues/95 for config and https://github.com/docsifyjs/docsify/issues/704 which requires choosing a lower version, but then I still get no output.

I had partial success using or https://michaelcurrin.github.io/docsify-js-tutorial/#/ or https://docsify.js.org/ in the config - but an error on `link` when using https://michaelcurrin.github.io/docsify-js-tutorial perhaps because subpage is not parsed.


## Base site

Here is the original repo:

- https://github.com/MichaelCurrin/docsify-js-tutorial

That is served as a Single-Page Application on Github Pages here:

- https://michaelcurrin.github.io/docsify-js-tutorial/#/


## Approach

This repo was created to make a version of the site above which is rendered server-side using Node.js

The DocsifyJS docs provide a recommendation - publish the site on _Vercel_. That allows hosting as a free `APP.now.sh` domain.

## Setup

This applies for a new or existing repo.

Setup an account on [vercel.com](https://vercel.com/). You can sign in with Github. Note your email address which you'll need later.

Install `vercel` and `docsify-cli` - these are covered in [package.json](package.json)

```sh
npm install
```

Run the `vercel` command.

Enter your email address when prompted.

Open your email, check for an email from Vercel and click Verify.


## Resources

- Docsify
    - https://docsify.js.org/#/ssr
    - Example
        - https://github.com/docsifyjs/docsify-ssr-demo
        - https://docsify.now.sh/
- Vercel
    - [vercel.com](https://vercel.com/) homepage. Previously known as [zeit.co](https://zeit.co)
    - NPM package: [npmjs.com/package/now](https://www.npmjs.com/package/now)


### Install globally

```sh
$ npm install -g vercel
```


## License

Released under [MIT](/LICENSE).
