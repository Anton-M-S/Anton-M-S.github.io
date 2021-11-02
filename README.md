# Title

## Purpose

These instructions will walk you through hosting your resume as a static website on GitHub pages using markdown and Jekyll. Hosting your resume using these tools allows you to easily update your resume without needing to redistribute it. That way if you make a change to your resume it will become visible to everybody who you have already shared it with.

	Andrew Etter suggests that all Functional documentation includes a description of what the product is and why it is useful. This first paragraph does just that.

## Prerequesites

Jekyll

Jekyll is a static site generator which will provide structure and design to your website. You can either use a built-in theme on GitHub pages or install it on your machine. You can find instructions on how to do both as well as a list of pre-built themes under [more resources](#More-Resources) below. These instructions will walk you through using the themes available on Github pages.

A Resume, formatted in Markdown

Markdown will form the basis of your website. It is simpler and easier to use than other languages such as HTML. If you are unfamiliar with markdown, a tutorial can be found under [more resources](#More-Resources) down below.

	The prerequesites section satisfies Andrew Etter’s recommendation to let your readers know what the dependencies are and how it feeds into a broader ecosystem. It describes the tools that will be used (the dependencies) and explains how they work together. It also covers his recommendation for install instructions. Install instructions are provided primarily through links because Etter recommends using links to previously written tutorials, rather than repeating information that is already available.

## Instructions

 1. Create a github pages repository


	This is done by creating a Github Repository and naming it “yourGitHubUsername.github.io.” For more detailed instructions, you can find a link to a tutorial under [more resources](#More-Resources) below.

		Etter emphasizes keeping instructions simple. Considering that we are assuming that our audience is already familiar with GitHub this step can be kept short and sweet. Again, to avoid repetition, links are used to provide a more detailed breakdown.

2. Upload your resume to GitHub

	Upload your resume to GitHub in a file called index.md. GitHub pages looks for this name by default and will automatically pick it to display. Ensure that you place this file in the main directory of your repository. At this point you should be able to view your resume by typing “https://yourGitUsername.github.io/” into your search engine

3. Create a configuration file

	In your main directory, create a file called _config.yml. Jekyll will use this file to store information about your theme and page layout.

4. Pick a Theme

	In [more resources](#More-Resources), there is a list of themes supported by GitHub pages. You can add themes by putting them in your frontmatter in _config.yml. Refer to the documentation of the chosen theme to find the exact code needed to do so as it varies from theme to theme. The code needed will either start with “theme:” or “remote_theme.”

## More Resources:

1. [Markdown Tutorial](https://www.markdowntutorial.com/)



2. [GitHub pages tutorial](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll)


3. [Adding a Jekyll Theme to github pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll)

4. [Jekyll Themes](https://pages.github.com/themes/)
4. _Modern Technical Writing_ By Andrew Etter
