# Stellar Quest 3 Proof of Acheivement Jekyll Theme

[![Open in GitHub Codespaces](https://img.shields.io/badge/Open%20in-GitHub%20Codespaces-blue?logo=github&style=flat-square)](https://github.com/codespaces/new?repo=anataliocs/Stellar-Quest-3-Jekyll)

Preview Github Pages Certificate
[![SQuest3Cert Preview](https://img.shields.io/badge/🚀%20Stellar%20Quest%203-blueviolet)](https://anataliocs.github.io/Stellar-Quest-3-Jekyll/)

## Run Locally

```
bundle install && bundle exec jekyll serve
```

Compile Sass
```
sass _sass/:css/index.css
```

## Installation
* Edit `_config.yml` file.
* Remove sample posts from `_posts` folder and add yours.
* Edit `index.md` file in `about` folder. 

### Global Config
`_config.yml` 


#### URL Details

Used to generate absolute urls in `sitemap.xml`, `feed.xml`, and for generating canonical URLs in `<head>`. When developing locally either comment this out or use something like `http://localhost:4000` so all assets load properly. *Don't include a trailing `/`*.

Examples:

{% highlight yaml %} url: http://tolgatatli.me/Moonrise url: http://localhost:4000 url: //cooldude.github.io url {%endhighlight%}

#### logo
Your site's logo. It will show on homepage and navigation menu. Also used for twitter meta tags.

#### background
Image for background. If you don't set it, color will be used as a background.

---

### Navigation Links

To set what links appear in the top navigation edit `_data/navigation.yml`. Use the following format to set the URL and title for as many links as you'd like. *External links will open in a new window.*

{% highlight yaml %}
- title: Home
  url: /

- title: Blog
  url: /blog/

- title: Projects
  url: /projects/

- title: About
  url: /about/

---

### Feature Image

You can set feature image per post. Just add `feature: some link` to your post's front matter.

```
feature: /assets/img/some-image.png
or
feaure: http://example.com/some-image.png
```    

