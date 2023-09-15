---
---

# JSP Guide

## What is JSP?

Jekyll Starter Pack, usually called JSP, is a Jekyll theme created by Mspicata specifically for easy setup. It includes the necessary files to run a Jekyll website from Github Pages. It is intended as a more accessible version of the Github Pages theme [Cayman](https://pages-themes.github.io/cayman/), because it can sometimes be hard to customise.

=> [JSP Demo](https://spicata.github.io/jsp/)  
=> [JSP Repo](https://github.com/spicata/jsp)

## Setup

1. Go to the JSP Github repository and press "Use this template". Select "Create a new repository"
2. Untick "Include all branches". Give the repository a name and a description (optional), and make it public.
3. Open the `_config.yml` file and change `baseurl:` to the name of your repository. **IF your repository is called `<your_github_username>.github.io`, leave the baseurl empty**.
4. In this new repo, go to Settings > Pages (on the side). Select the Source: "Deploy from a branch". Select the Branch: "main". Save the changes. This will allow you to make a website. Go to Actions to find where it deploys to.

Generally, your website should deploy to `https://<your_github_username>.github.io/<name_of_repository>`.

## Use with Obsidian

JSP already comes with a `.obsidian` file, so you can use it with Obsidian right out of the box. Just add the JSP folder as a vault in Obsidian, and then disable restricted mode.

## Customise JSP

There are only two files you need to edit to customise JSP: `_layouts/default.html` and `assets/css/styles.css`. Normal HTML and CSS applies. For example: 

=> [The Chicken Pen](https://pi-thagoras.github.io/the-chicken-pen/)
