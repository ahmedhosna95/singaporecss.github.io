# This be the source code for the Talk.CSS website

The site will be updated after every meet-up, with a short recap and links to videos of the talks.

## v1.4.0

- Ported all speaker and video content into data files
- Rewrote post template to utilise data files
- Reorganised folder structure for assets
- Added links to previous and next meetups on each post page
- Added logic for Codepen embed script

## v1.3.0

- Tidied up styles
- Moved past meet-ups to a separate page
- Added more logic to cater for special events, e.g. max-content edition

## v1.2.0

- Added Developer voice page

## v1.1.0

- Fixed issue with Facebook metatags
- Added Platform status page

## v1.0.0

- Updated recaps for past meetups
- Updated speaker bios for each meetup
- Added styling for broken images

## v0.0.1

- Created initial styling
- Set current site font to [Hack](http://sourcefoundry.org/hack/)
- Added pages for first 3 meet-ups
- Added About page
- Wrote copy for site footer

## If you want to clone the site...

You'll need to have the following installed:

1. [NodeJS](http://nodejs.org) - You can use the installer, but if you're on a Mac, I highly suggest using [Homebrew](http://blog.teamtreehouse.com/install-node-js-npm-mac)
2. [GulpJS](http://gulpjs.com) - `npm install -g gulp`
3. [Bundler](http://bundler.io) - `gem install bundler`

- Clone this repository into your working directory.
- Navigate to the directory and run `npm install`. This will install the required node modules for the project.
- Run `bundle install`. This will install the [GitHub Pages gem](https://github.com/github/pages-gem) and [SCSS-Lint gem](https://github.com/brigade/scss-lint).

- Run `gulp`. This will run the Gulp tasks needed for:
    -  compiling Sass, 
    -  serving the Jekyll site, 
    -  watch for changes to relevant folders and reload the browser accordingly.

- There is also a `gulp build` task, which will also minify the stylesheet. Only used when deploying site to production.
