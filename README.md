# Stellar Quest 3 Proof of Acheivement Jekyll Theme

[![Open in GitHub Codespaces](https://img.shields.io/badge/Open%20in-GitHub%20Codespaces-blue?logo=github&style=flat-square)](https://github.com/codespaces/new?repo=anataliocs/Stellar-Quest-3-Jekyll)

## Getting Started

To learn how to install and use this theme check out the [Setup Guide](https://tolgatatli.github.io/Moonrise/) for more information.

## Installation
* Fork the [Moonrise repo](https://github.com/TolgaTatli/Moonrise/fork)
* Edit `_config.yml` file.
* Remove sample posts from `_posts` folder and add yours.
* Edit `index.md` file in `about` folder.
* Change repo name to `YourUserName.github.io`    
     
That's all.

## Site Setup
A quick checklist of the files you’ll want to edit to get up and running.    

### Site Wide Configuration
`_config.yml` is your friend. Open it up and personalize it. Most variables are self explanatory but here's an explanation of each if needed:

#### title

The title of your site... shocker!

Example `title: My Awesome Site`

#### bio

The description to show on your homepage.

#### description

The description to use for meta tags and navigation menu.

#### url

Used to generate absolute urls in `sitemap.xml`, `feed.xml`, and for generating canonical URLs in `<head>`. When developing locally either comment this out or use something like `http://localhost:4000` so all assets load properly. *Don't include a trailing `/`*.

Examples:

{% highlight yaml %} url: http://tolgatatli.me/Moonrise url: http://localhost:4000 url: //cooldude.github.io url {%endhighlight%}

#### reading_time

Set true to show reading time for posts. And set `words_per_minute`, default is 200.

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

- title: Moon
  url: http://tolgatatli.me/Moon
{% endhighlight %}

---

## Layouts and Content

Moon Theme use [Jekyll Compress](https://github.com/penibelst/jekyll-compress-html) to compress html output. But it can cause errors if you use "linenos" (line numbers). I suggest don't use line numbers for codes, because it won't look good with this theme, also i didn't give a proper style for them. If you insist to use line numbers, just remove `layout: compress` string from layouts. It will disable compressing.

### Feature Image

You can set feature image per post. Just add `feature: some link` to your post's front matter.

```
feature: /assets/img/some-image.png
or
feaure: http://example.com/some-image.png
```    

