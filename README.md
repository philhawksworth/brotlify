# Brotlify

https://brotlify.neltify.app

Because [Netlify has brotli compression now](https://www.netlify.com/blog/2020/05/20/gain-instant-performance-boosts-as-brotli-comes-to-netlify-edge/?utm_source=brotlify&utm_medium=brotli-pnh&utm_campaign=devex) and no pun should go un-enjoyed.

## Local build

The site also uses a [Netlify Build Plugin](https://docs.netlify.com/configure-builds/build-plugins/?utm_source=brotlify&utm_medium=brotli-pnh&utm_campaign=devex) to [minify the HTML](https://www.npmjs.com/package/netlify-plugin-minify-html).

```toml

# globally install Netlify CLI
npm install -g netlify-cli

# get this site code
git clone git@github.com:philhawksworth/brotlify.git


# install Build Plugin
cd brotlify
npm i

# run local build
ntl build

```
