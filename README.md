# Kross Hugo Portfolio Forestry starter

[Preview theme](http://demo.themefisher.com/kross-hugo/)

Theme developed by Themefisher.

## Requirements

- GitHub, GitLab or BitBucket account
- Hugo > 0.58.0

## Content Management

[![import to Forestry](https://assets.forestry.io/import-to-forestryK.svg)](https://app.forestry.io/quick-start?repo=forestryio/kross-hugo-starter&engine=hugo&version=0.64.1)

This project has been pre-configured to work with [Forestry](https://forestry.io) a git-based CMS, [import your repository in Forestry](https://assets.forestry.io/import-to-forestryK.svg)](https://app.forestry.io/quick-start?repo=forestryio/kross-hugo-starter&engine=hugo&version=0.64.1) and you'll be able to edit and preview your site ✨. \
Any changes you make in Forestry will be commited back to the repo, and deployed if you use [Netlify](#netlify) or [ZEIT now](#zeit-now).

## Local development

```bash
# clone the repository
git clone git@github.com:forestryio/kross-hugo-starter.git

# cd in the project directory
cd kross-hugo-starter

# Start local dev server
hugo server
```

## Deployment and hosting 

### Netlify

Import your site in [Netlify](https://netlify.com)

1. Create a new site in Netlify and import your repository.
2. Set the build command to: `hugo --gc --minify`
3. Set the publish directory to: `public`
4. Make sure to set `HUGO_VERSION` to 0.55.0 or above (tested with 0.62.2)
3. Set the publish directory to: `public`

That's it, now your site gets deployed automatically on `git push` or when saving documents from Forestry.

### ZEIT Now

[![Deploy with ZEIT Now](https://zeit.co/button)](https://zeit.co/new/project?template=https://github.com/forestryio/kross-hugo-starter)

Follow the steps.

## Feedback

[Open an issue](https://github.com/themefisher/kross-hugo/issues) in the theme's repository.

## LICENSE

MIT as specified in the theme's[LICENSE](https://github.com/themefisher/kross-hugo/blob/master/LICENSE) file 
