# Hugo DoulaProfile

![License](https://img.shields.io/github/license/zoe-moment/themeHugoProfile_healthcareDoula) 

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg)](https://github.com/RichardLitt/standard-readme)

 >This repo to serve as base for opensource healthcare worker profile for Doulas.

Example Site: [#](TBA)

## Table of Contents

- [Security](#security)
- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [Deployment](#deployment)
- [Thanks](#thanks-and-inspiration)
- [Contributing](#contributing)
- [License](#license)

## Background

### Features
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

## Install
[Direct deployment using netlify](#direct-deployment-using-netlify)

[Organizing Hugo's content](https://www.giraffeacademy.com/static-site-generators/hugo/content-organization/)

1. Create a new hugo site formatted in YAML
```sh
hugo new site mySite -f=yaml
```
2. Navigate inside of the new site `cd mySite`
3. Clone this repo into your empty themes forlder 
```sh
git clone https://github.com/zothsu/hugo-profile-doula.git /themes
```
4. Create config.yaml inside root folder. Setup the configurations in `config.yaml`. [reference](https://github.com/gurusabarish/hugo-profile/blob/master/exampleSite/config.yaml)
```sh
touch config.yaml
```

### Deployment

Run `hugo`. It will generate a folder called public. You can use the files inside public folder for deployment. You should delete the public folder for each time when you are using `hugo` commend.

### Direct deployment using netlify

Fork this repo or create new repo using `use this template` button and connect repo to netlify.
- whenever you customize the files exampleSite folder, netlify will automatically deploy your changes.

For more details: [host on netlify](https://gohugo.io/hosting-and-deployment/hosting-on-netlify/)

## Thanks and inspiration

- [Standard README](https://github.com/RichardLitt/standard-readme) - The readme standard

Hugo theme forked from [https://github.com/gurusabarish/hugo-profile](https://github.com/gurusabarish/hugo-profile).

## Contributing
## License

Licensed under [MIT](LICENSE)
