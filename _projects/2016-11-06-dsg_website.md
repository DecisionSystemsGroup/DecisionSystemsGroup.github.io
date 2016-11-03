---
layout: project
type: dsg_project
title: DSG Website
alias: dsg_website
members: [john_prantalos]
thumb: http://i.imgur.com/0xbGdv9.jpg
repo: https://github.com/DecisionSystemsGroup/DecisionSystemsGroup.github.io
website: http://dsg.teiste.gr/
---
Build on top of Jekyll and hosted on Github Pages the DSG website is a simple
blog-aware static site, where you can find all the info you want about the
DSG Team, its projects and news.

# About the project
The DSG Website is the third one built and the first one dumping the classic
LAMP technologies.

It is written in pure HTML, CSS and Javascript, with the usage of Twig
templating methods.

It is powered by Jekyll (more about it below) and it is hosted on Github Pages.

The website is developed by [John Prantalos]({{ site.baseurl }}/prantalos-john).
Furthermore, [Charis Dimos]({{ site.baseurl }}/dimos-charis) and
[Stavros Tsourlidakis]({{ site.baseurl }}/tsourlidakis-stavros) built an easy
to use [Jekyll editor]({{ site.baseurl }}/projects/jekyll_editor) so that
anyone without the need of Github Account can post and maintain the website.

# Some tech info
**DSG Website** is a custom-made static site built on top of
[Jekyll-now](http://www.jekyllnow.com), a plug-n-play repo for setting up a
[Jekyll](https://github.com/jekyll/jekyll) website in Github Pages.

The theme is a hacked version of [Bootswatch's](http://bootswatch.com/)
[Yeti Theme](http://bootswatch.com/yeti/) which is based on
[Bootstrap](http://getbootstrap.com) Framework.

For development we used the SASS versions of the Yeti and Bootstrap stylesheets
as long as [Font Awesome 4](http://fontawesome.io/) library.

All 3rd party SASS files (\*.scss) are imported via the main style.scss which
also contains all the custom-made stylesheet classes.

All of the posts are stored in posts folder and their filename must begin
with the date they are written. For example: 2016-10-10-post_name.md.

The posts are written in Markdown but if necessary pure html is also supported

There also two more **Collections**; one for the team members (stored in team
folder) and one for the projects (stored in projects folder).

Each page has its own layout, build specifically for it.

Finally, respecting the Github Guidelines, most of the images needed in DSG
Website are stored in Imgur and not inside the repo.
