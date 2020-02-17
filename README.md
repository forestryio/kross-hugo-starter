# Kross Hugo Portfolio Forestry starter

![Homepage](https://user-images.githubusercontent.com/37659754/58154295-1a9c5300-7c93-11e9-992c-ad8d2ff8d99f.png)

[Live Preview](http://demo.themefisher.com/kross-hugo/)

[Kross Hugo theme](https://github.com/themefisher/kross-hugo/) is developed by Themefisher.

## Requirements

- GitHub, GitLab or BitBucket account
- Hugo > 0.58.0

## Content Management

![](static/images/kross-forestry.jpg)

[![import to Forestry](https://assets.forestry.io/import-to-forestryK.svg)](https://app.forestry.io/quick-start?repo=forestryio/kross-hugo-starter&engine=hugo&version=0.64.1)

This project has been pre-configured to work with [Forestry](https://forestry.io) a git-based CMS, [import your repository in Forestry](https://app.forestry.io/quick-start?repo=forestryio/kross-hugo-starter&engine=hugo&version=0.64.1) and you'll be able to edit and preview your site ✨. \

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

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/forestryio/kross-hugo-starter)

1. Set the build command to: `hugo --gc --minify`
2. Set the publish directory to: `public`
3. Make sure to set `HUGO_VERSION` to 0.58.0 or above (tested with 0.64.1)
3. Set the publish directory to: `public`

That's it, now your site gets deployed automatically on `git push` or when saving documents from Forestry.

### ZEIT Now

[![Deploy with ZEIT Now](https://zeit.co/button)](https://zeit.co/new/project?template=https://github.com/forestryio/kross-hugo-starter)

Follow the steps.

## Feedback

[Open an issue](https://github.com/themefisher/kross-hugo/issues) in the theme's repository.

## LICENSE

MIT as specified in the theme's [LICENSE](https://github.com/themefisher/kross-hugo/blob/master/LICENSE) file 
