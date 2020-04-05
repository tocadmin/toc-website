---
layout: post
title:  "First Post"
date:   2020-04-05 12:22:43 -0400
categories: [meta]
---
This the **first post** showing how it's possible to set up a website using GitHub and Jekyll.

To get this far (with some experimentation) I did the following steps.

1. Create a new GitHub account
2. Create a github repo in the format tocadmin.github.io
3. Pull down the github repo
4. Follow Jekyll setup instructions in the project folder (using `jekyll new . --force)` since the folder already exists
5. Run `git add .`, `git commit -m 'Jekyll commit'` and `git push` to upload the website to GitHub
6. Edit `_config.yml` file with custom information
7. Copy the default post in the `_posts` folder, edit it to match what I want, rename it, and delete the original
8. `git commit -am 'First post'` and `git push`

## References

- <https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages>
- <https://jekyllrb.com/docs/>
- <https://pages.github.com/>
