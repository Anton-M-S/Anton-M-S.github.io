

# Hosting a Resume as a Static Website on GitHub pages

## Purpose

These instructions will walk you through hosting your resume as a static website on GitHub pages using markdown and Jekyll. Hosting your resume using these tools allows you to easily update your resume without needing to redistribute it. That way if you make a change to your resume it will become visible to everybody who you have already shared it with.

- Andrew Etter suggests that all Functional documentation includes a description of what the product is and why it is useful. This first paragraph does just that.

## Prerequesites

### Jekyll

Jekyll is a static site generator which will provide structure and design to your website. You can either use a built-in theme on GitHub pages or install it on your machine. You can find instructions on how to do both as well as a list of pre-built themes under [more resources](#More-Resources) below. These instructions will walk you through using the themes available on Github pages.

### A Resume, formatted in Markdown

Markdown will form the basis of your website. It is simpler and easier to use than other languages such as HTML. If you are unfamiliar with markdown, a tutorial can be found under [more resources](#More-Resources) down below.

- The prerequisites section satisfies Andrew Etter’s recommendation to let your readers know what the dependencies are and how it feeds into a broader ecosystem. It describes the tools that will be used (the dependencies) and explains how they work together. It also covers his recommendation for install instructions. Install instructions are provided primarily through links because Etter recommends using links to previously written tutorials, rather than repeating information that is already available.

## Instructions
1. *Create a GitHub Account*
	If you already have an account, you can use it. Otherwise, head to https://github.com/ and follow the instructions there to create an account.
	
	- Using version control allows us to access, edit and update files from any device. This allows for easy updates to your resume. 
		
---

 2. *Create a GitHub pages repository*

	This is done by creating a GitHub Repository and naming it “yourGitHubUsername.github.io.” For more detailed instructions, you can find a link to a tutorial under [more resources](#More-Resources) below.

	- One of Etter's arguments for the use of static websites is that they have no software dependencies. All someone needs to view a static website is a web browser. This means that you do not need to worry about file type compatibility. Anybody with the address for a static website will be able to view it without issue.

		
---

3. *Upload your resume to GitHub*

	Upload your resume to GitHub in a file called index.md. GitHub pages looks for this name by default and will automatically pick it to display. Ensure that you place this file in the main directory of your repository. At this point you should be able to view your resume by typing “https://yourGitHubUsername.github.io/” into your search engine
		
---

4. *Create a configuration file*

	In your main directory, create a file called _config.yml. Jekyll will use this file to store information about your theme and page layout.

	- One of Etter's key points for using a static site generator is the ability to easily update and add information. Frontmatter is important for this. Frontmatter can be used to define layouts that act as formatting for pages so that you can add pages while easily maintaining a unified theme without duplicating work. 
---

5. *Pick a theme*

	In [more resources](#More-Resources), there is a list of themes supported by GitHub pages. You can add themes by putting them in your frontmatter in _config.yml. Refer to the documentation of the chosen theme to find the exact code needed to do so as it varies from theme to theme. The code needed will either start with “theme:” or “remote_theme.”

	- On GitHub pages, the chosen Jekyll theme provides the layout information mentioned in the previous step. This is important because it allows you to update the content of your page without worrying about affecting the formatting. This lines up with Etter's emphasis on making your writing easy to read and update.

---
6. *Title your page*

	This step is not strictly necessary, but is useful to fully utilize the stylistic elements of your chosen theme. Most themes display the title differently from the rest of the page. In your _config.yml file, add the line "title: yourTitle" to set a title.

See the video below for a short guide on setting a theme and title on Github pages. 

![test gif](demo.gif)

There you have it. You have successfully hosted your resume on GitHub pages and formatted it using a Jekyll theme. Now you can share your resume with a simple link. Additionally prospective employers will always see the most up-to-date version.
## More Resources:

1. [Markdown Tutorial](https://www.markdowntutorial.com/)



2. [GitHub pages tutorial](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll)


3. [Adding a Jekyll Theme to github pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll)

4. [Jekyll Themes](https://pages.github.com/themes/)
5. _Modern Technical Writing_ By Andrew Etter

## Authors and Acknowledgments 

- Peer editors: Ikram Khan Shipon, Joshua Moreira, Kevin Kim, Ryan Campbell

- [GitHub Pages themes](https://github.com/pages-themes/slate)

## FAQs

#### Q. Why is markdown better than a word processor?
A. Markdown is better than a word processor because it offers a widely recognized format, and can be written without the use of specialized editors. It also has fewer features, which means it is much easier to learn and use, especially for simple documents that don't require complex features. 

#### Q.  Why is my resume not showing up?
A. If your resume is not showing up it can be because GitHub pages has not recognized that the file has been added to the repository. GitHub pages can take up to 20 minutes to recognize changes. This can be solved by waiting and refreshing the page. 
	If that doesn't work, it is possible that GitHub does not recognize the file that contains your resume. Ensure that your resume is in a file called "index.md" and that there are no typos in the file name that. 
