# Organization Documentation

## Table of Contents
1. [What is this org?](#about)
2. [Repositories Breakdown](#repos)
2. [Technological Choices and Aspects](#aspects)
3. [Interests](#intrests)


<a name="about"></a>
## What is this organization?

This organization will serve as a place to organize all of the boilerplate code that I've setup as [template repositories](https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates/). I didn't want to litter my regular profile with a bunch of template repositories as I wanted it to have active projects on there. I tried setting up a single boilerplate repo that used branches but that got messy very quickly, that's when I read about [Github Organization's for grouping related repo's ](https://stackoverflow.com/questions/20908994/grouping-repos-on-github) and now here we are.



<a name="repos"></a>
## Current Planned Template Setups:

### Frontend

1. frontend-static-seo-site
    - Very simple setup, maybe not even using webpack
    - Setup something that would allow you to do customize html (eg. partials).
    - https://www.sitepoint.com/bundle-static-site-webpack/
    - https://github.com/h5bp/html5-boilerplate
    - https://medium.com/@ivarprudnikov/static-website-multiple-html-pages-using-webpack-3bdb7accffad
    - https://mozilla.github.io/nunjucks/templating.html#template-inheritance
2. frontend-plain-spa-app
3. frontend-react-app
4. frontend-react-ssr-app
    - https://github.com/manuelbieh/react-ssr-setup
5. php-plain-bootstrap

### Backend


### Tooling, etc.

1. [Puppeteer Scripts](https://developers.google.com/web/tools/puppeteer)
1. [Github Templates](https://help.github.com/en/github/building-a-strong-community/using-templates-to-encourage-useful-issues-and-pull-requests)
1. [Building Wikis](https://help.github.com/en/github/building-a-strong-community/documenting-your-project-with-wikis)



### Ideas, (need more thought)
1. Plain Node
  - https://github.com/tvvignesh/node-skeleton
1. A PWA application plugged into using local storage
1. Some kind of style guide that would come with boilerplates
1. Deployment scripts, handling dist folders
  - https://gist.github.com/cobyism/4730490
1. ESlint and Prettier setups for projects w/ vscode, other editors?
1. Make an npm module, php package, pip package, have a template for publishing one.
1. Site Customizer Template:
  - Build a template for customizing an exisitng website you don't have any control over. Something that allows modularity/breaking up css/js files for any large projects.
  - You can achieve this with injecting scripts/css into a site in your own browser with something like [Tampermonkey](https://www.tampermonkey.net/).
  - https://www.google.com/search?q=tamper+monkey+customize+style+sheet
  - https://stackoverflow.com/questions/19385698/how-to-change-a-class-css-with-a-greasemonkey-tampermonkey-script/19392142


<a name="aspects"></a>
## Technological Choices and Aspects

This is a list of all the different technological goals I'm looking to achieve within these repositories. Not every goal will be covered in every repository, each repository will be made up of a selection of the technologies that help achieve that repositories goals.

### Tooling and config files
  - Bundlers: Webpack vs Rollup vs Parcel vs MicroBundle
  - VS Code config file for styling setup
  - Github issues template files with just basic Markdown

### Code styling and structure
  - ESLint, with some sane rules
    - https://mobile.twitter.com/kentcdodds/status/1176249054247841792
    - https://overreacted.io/writing-resilient-components/
    - https://www.npmjs.com/package/eslint-config-react-app

### CSS Complication
  - Webpack to build the CSS
  - Source Maps
  - Sass
    - https://www.npmjs.com/package/node-sass
    - https://www.npmjs.com/package/sass-loader
  - PostCSS
    - https://www.npmjs.com/package/postcss-loader
    - https://www.smashingmagazine.com/2015/12/introduction-to-postcss/
    - https://postcss.org/



### JS Compilation
  - Browser targets added
  - ES6 and beyond compilation
  - Source Maps
    - https://developers.google.com/web/tools/chrome-devtools/javascript/source-maps


### Miscellaneous Boilerplates to work on:
  - UI toolkit
  - API tooling
  - Doc generation
  - Marketing site


<a name="intrests"></a>
## Interests

Interesting tools that I've run into that I'm not sure where they fit into my workflow but I'd like to keep them on my radar.

1. [Loopback, a tool for api developers, kind of like a boilerplate generator itself](https://loopback.io/)
2. [Tailwind CSS, utility first css framework](https://tailwindcss.com/)












