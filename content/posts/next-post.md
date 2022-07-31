---
title: "Fully Automated Hugo Publishing"
date: 2022-07-30T17:18:57-07:00
draft: false
---

After my friend told me all about [Hugo](https://gohugo.io/) I decided to create a quickstart website with content published to [GitHub pages](https://pages.github.com/), automatically using [GitHub Actions](https://github.com/features/actions). Initially I installed Hugo using Brew locally, creating a repo and pushing to a repo. Then I finally decided to read about setting up GitHub pages. The main requirement is setting up a repo with the proper naming convention: *user/organization.github.io*. The details regarding the gh-pages branch and GitHub Actons is well-documented here by [Hugo](https://gohugo.io/hosting-and-deployment/hosting-on-github/). Anytime I merge changes to the Main branch, GitHub Action will build the Hugo site and publish the public content to the *gh-pages* branch.

 
