This template supports the following features:

* Films
* Bundles
* Pages
* Template only pages (robots.txt and sitemap.txt are examples)
* Internationalization

## Building

 * install kibble
 * ```kibble render``` - generate a new site (files are located at ```.kibble/build```)
 * ```kibble serve --watch``` to preview the site

 ## Screen Plus / Event development

 `master` branch contains config for deploying to staging-event.shift72.com
 `prod-au` branch is for deploying to event.shift72.com
 `prod-nz` branch is for deploying to eventnz.shift72.com

 Need to be careful merging any master changes into the 2 prod branches.
