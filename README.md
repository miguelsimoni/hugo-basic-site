# Hugo Basic Site

This repository is based on [Hugo Basic Example](https://github.com/gohugoio/hugoBasicExample), offers an example site for some of my [Hugo Theme Projects](https://miguelsimoni.xyz/project/) that are hosted on the [Hugo Themes Showcase](https://themes.gohugo.io/).

# Using

1. [Install Hugo](https://gohugo.io/overview/installing/)

2. Clone this repository

```bash
git clone https://github.com/miguelsimoni/hugo-basic-site.git
cd hugo-basic-site
```

3. Clone the repository of the theme you want to test.

4. Run Hugo and select the theme of your choosing

```bash
hugo server -t YOURTHEME
```

5. Under `/content/` this repository contains the following:

- A section called `/post/` with sample markdown content
- A headless bundle called `homepage` that you may want to use for single page applications. You can find instructions about headless bundles over [here](https://gohugo.io/content-management/page-bundles/#headless-bundle)
- An `about.md` that is intended to provide the `/about/` page for a theme demo
