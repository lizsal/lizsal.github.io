lizsaling.com is built using **[Jekyll](https://github.com/jekyll/jekyll)**, a static site generator that's perfect for GitHub hosted blogs, and based on **[Jekyll Now](https://github.com/barryclark/jekyll-now)** which makes it easy by eliminating a lot of the up front setup.

### Configuring the site

Main site configuration is done by editing the _config.yml file. You can easily turn on Google Analytics tracking, Disqus commenting and social icons here too. Making a change to _config.yml (or any file in your repository) will force GitHub Pages to rebuild your site with jekyll. Your rebuilt site will be viewable a few seconds later at <https://yourgithubusername.github.io> - if not, give it ten minutes as GitHub suggests and it'll appear soon.  

### Publishing a blog post

Cope the metadata table from a [previous post](/_posts) and paste it into a new file in the posts directory. When it's merged, it will automatically post using the title and exerpt given. Additional options are available for the [front-matter](http://jekyllrb.com/docs/frontmatter/) block at the top of each new blog post file. Make sure the post's filename is in this format: year-month-day-title.md

### More Info

<details>
  <summary>Local Development</summary>
  
    1. Install Jekyll and plug-ins in one fell swoop. `gem install github-pages` This mirrors the plug-ins used by GitHub Pages on your local machine including Jekyll, Sass, etc.
    2. Clone down your fork `git clone https://github.com/yourusername/yourusername.github.io.git`
    3. Serve the site and watch for markup/sass changes `jekyll serve`
    4. View your website at http://127.0.0.1:4000/
    5. Commit any changes and push everything to the master branch of your GitHub user repository. GitHub Pages will then rebuild and serve your website.
</details>

<details>
  <summary>Bigger Walkthrough</summary>
  
    I've created a more detailed walkthrough, [**Build A Blog With Jekyll And GitHub Pages**](http://www.smashingmagazine.com/2014/08/01/build-blog-jekyll-github-pages/) over at the Smashing Magazine website. Check it out if you'd like a more detailed walkthrough and some background on Jekyll. :metal:

    It covers:

    - A more detailed walkthrough of setting up your Jekyll blog
    - Common issues that you might encounter while using Jekyll
    - Importing from Wordpress, using your own domain name, and blogging in your favorite editor
    - Theming in Jekyll, with Liquid templating examples
    - A quick look at Jekyll 2.0’s new features, including Sass/Coffeescript support and Collections
</details>

<details>
  <summary>More Details</summary>
  
  #### Questions?

[Open an Issue](https://github.com/barryclark/jekyll-now/issues/new) and let's chat!

#### Other forkable themes

You can use the [Quick Start](https://github.com/barryclark/jekyll-now#quick-start) workflow with other themes that are set up to be forked too! Here are some of my favorites:

- [Hyde](https://github.com/poole/hyde) by MDO
- [Lanyon](https://github.com/poole/lanyon) by MDO
- [mojombo.github.io](https://github.com/mojombo/mojombo.github.io) by Tom Preston-Werner
- [Left](https://github.com/holman/left) by Zach Holman
- [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) by Michael Rose
- [Skinny Bones](https://github.com/mmistakes/skinny-bones-jekyll) by Michael Rose

#### Credits

- [Jekyll](https://github.com/jekyll/jekyll) - Thanks to its creators, contributors and maintainers.
- [SVG icons](https://github.com/neilorangepeel/Free-Social-Icons) - Thanks, Neil Orange Peel. They're beautiful.
- [Solarized Light Pygments](https://gist.github.com/edwardhotchkiss/2005058) - Thanks, Edward.
- [Joel Glovier](http://joelglovier.com/writing/) - Great Jekyll articles. I used Joel's feed.xml in this repository.
- [David Furnes](https://github.com/dfurnes), [Jon Uy](https://github.com/jonuy), [Luke Patton](https://github.com/lkpttn) - Thanks for the design/code reviews.
- [Bart Kiers](https://github.com/bkiers), [Florian Simon](https://github.com/vermluh), [Henry Stanley](https://github.com/henryaj), [Hun Jae Lee](https://github.com/hunjaelee), [Javier Cejudo](https://github.com/javiercejudo), [Peter Etelej](https://github.com/etelej), [Ben Abbott](https://github.com/jaminscript), [Ray Nicholus](https://github.com/rnicholus), [Erin Grand](https://github.com/eringrand), [Léo Colombaro](https://github.com/LeoColomb), [Dean Attali](https://github.com/daattali), [Clayton Errington](https://github.com/cjerrington), [Colton Fitzgerald](https://github.com/coltonfitzgerald), [Trace Mayer](https://github.com/sunnankar) - Thanks for your [fantastic contributions](https://github.com/barryclark/jekyll-now/commits/master) to the project!

#### Contributing

Issues and Pull Requests are greatly appreciated. If you've never contributed to an open source project before I'm more than happy to walk you through how to create a pull request.

You can start by [opening an issue](https://github.com/barryclark/jekyll-now/issues/new) describing the problem that you're looking to resolve and we'll go from there.

I want to keep Jekyll Now as minimal as possible. Every line of code should be one that's useful to 90% of the people using it. Please bear that in mind when submitting feature requests. If it's not something that most people will use, it probably won't get merged. :guardsman:
</details>
