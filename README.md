# Hugo DoulaProfile

![License](https://img.shields.io/github/license/zoe-moment/themeHugoProfile_healthcareDoula)

Hugo theme forked from [https://github.com/gurusabarish/hugo-profile](https://github.com/gurusabarish/hugo-profile). This repo to serve as base for opensource healthcare worker profile for Doulas.

- Example Site: [#](TBA)

# Features
- Fully Responsive
- Minimalist Design
- SEO Friendly.
- Light/Dark/auto
- Taxonomies
- [Color customization](https://github.com/gurusabarish/hugo-profile/wiki/Color-Customization)
- Analytics Support 
  - [Google Analytics](https://gohugo.io/templates/internal/#google-analytics)
- Comment Support
  - [Disqus](https://gohugo.io/content-management/comments/)
- Integration with [FormSpree](https://formspree.io/) for submitting "Contact me" form

Technology used: Bootstrap, fontawesome 

# Requirements
- Hugo Version 0.87.0 or higher


# How to use this template

- [Hugo theme](#Hugo-theme)
- [Direct deployment using netlify](#Direct-deployment-using-netlify)

[For more details](https://github.com/gurusabarish/hugo-profile/wiki)
## Hugo theme

- Install Hugo and create a site using `hugo new site my-site -f=yaml`
- Clone this repo inside your themes folder
```
cd themes
git clone https://github.com/zoe-moment/hugo-profile-doula.git
```
- Create config.yaml (you can use `config.toml` too) inside root folder 
- Setup the configurations in `config.yaml`. [reference](https://github.com/gurusabarish/hugo-profile/blob/master/exampleSite/config.yaml)
- You should have the mentioned (_inside the config file_) images in static folder to use them.

For more details: [Hugo's official docs](https://gohugo.io/getting-started/quick-start/), [content management](https://www.mikedane.com/static-site-generators/hugo/content-organization/)

## Direct deployment using netlify

- Fork this repo or create new repo using `use this template` button and connect repo to netlify.
- whenever you customize the files exampleSite folder, netlify will automatically deploy your changes.

For more details: [host on netlify](https://gohugo.io/hosting-and-deployment/hosting-on-netlify/), [content management](https://www.mikedane.com/static-site-generators/hugo/content-organization/)

# Deployment

Run `hugo`. It will generate a folder called public. You can use the files inside public folder for deployment. You should delete the public folder for each time when you are using `hugo` commend.

# Issues

If you have a question, please [open an issue](https://github.com/gurusabarish/hugo-profile/issues) for help and to help those who come after you. The more information you can provide, the better!

# Contributing

Contributions, issues, and feature requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

# License

Licensed under [MIT](LICENSE)
