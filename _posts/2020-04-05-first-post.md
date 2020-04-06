---
layout: post
title:  "Creating thinkingoutcode.com"
date:   2020-04-05
categories: [meta]
---
This site is motivated by selfish reasons. It is a forcing function for myself to write some guides or my experiences on topics related to programming. As a fortunate side effect, some of the material may prove useful to some. Since I already was paying for a webhost which sat unused, I started followed their instructions for setting up a Wordpress based blog. I immediately felt this was too heavyweight for my needs, and since I have some experience keeping notes in Markdown format, I came across Jekyll. A tool that builds static webpages from markdown.

### Setting up GitHub Pages

To get this far (with some experimentation) I did the following steps.

1. Create a new GitHub account
2. Create a github repo in the format tocadmin.github.io
3. Pull down the github repo

### Setting up Jekyll

1. Follow Jekyll setup instructions in the project folder (using `jekyll new . --force)` since the folder already exists
2. Run `git add .`, `git commit -m 'Jekyll commit'` and `git push` to upload the website to GitHub
3. Edit `_config.yml` file with custom information
4. Copy the default post in the `_posts` folder, edit it to match what I want, rename it, and delete the original
5. `git commit -am 'First post'` and `git push`

### References

- <https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages>
- <https://jekyllrb.com/docs/>
- <https://pages.github.com/>
