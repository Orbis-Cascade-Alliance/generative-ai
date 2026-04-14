# Courses Template
This repository can be used to generate simple Alliance-branded websites with Jekyll. It uses the Github Pages-compatible [Minimal theme](https://github.com/pages-themes/minimal/) with customizations.

To use, create a new repository within the Orbis-Cascade-Alliance organization and select this one as the template. (Outside of the Alliance, fork and clone the repository.) Create a branch to use as the source for the website, such as "gh-pages," or use the default "main." Set the selected branch as the source under Settings > Pages. GitHub will automatically generate the website from the source code.

## Site Setup

Edit _config.yml with the site title, description, and URL of the new repository.

## Adding Pages to the Site

Add and edit pages within the /_pages directory.

Set the titles, permalinks, and order in the frontmatter. (Between the lines of three dashes at the top.)

All pages will appear in the menu to the left. For example, the page with an order of 1 will appear first in the list, followed by the page with order 2, etc.

## Markdown

All pages are written in Markdown. See [Basic Syntax](https://www.markdownguide.org/basic-syntax/)

## Multimedia

To add images to a page, add them to the /assets/img folder. Either use the complete path in the image source, including the repository, or use a path relative to the root of the project with the Jekyll filter ``absolute_url``. Examples:

    ![Artistic rendering of computers](/systems-librarianship/assets/img/binary-monitor-particles-600px.jpg)
    
    ![Artistic rendering of computers]({{ "/assets/img/binary-monitor-particles-600px.jpg" | absolute_url }})
	
To embed YouTube videos, use the iframe embed code. Example:

    <iframe width="560" height="315" src="https://www.youtube.com/embed/08VDn3vdD4A?si=EBxc050TnfEXUjAV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen\></iframe>

## Testing

If editing the website on Github.com, preview page contents using the button at the top of the editing window. The website will update soon after changes are committed to the source branch.

To run the website on another machine for development, see the [Jekyll Installation](https://jekyllrb.com/docs/installation/) documentation and [Testing your GitHub Pages site locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll). Clone the appropriate repository rather than creating a new site.
