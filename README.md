# cbelena.es

Personal website of Carlos Beleña, powered by [Hugo](https://gohugo.io) and [Congo theme](https://github.com/jpanther/congo).

## Deployment

To live testing on local network (default port: `1313`):

`hugo server --bind "0.0.0.0"`

And to build/publish:

`hugo`

Remember that running `hugo` [does not](https://gohugo.io/getting-started/usage/#deploy-your-website) remove generated files before building.

That's it! :tada:

## Updates

### Hugo

To update Hugo, download latest release from [here](https://github.com/gohugoio/hugo/releases) and install it like any other package.

### Theme

To update Congo theme to latest version:

`git submodule update --remote --merge`

Once the submodule has been updated, rebuild with `hugo` and check everything works as expected.
