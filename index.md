---
layout: default
title: Home
---

# {{ page.title }}

This is the homepage of the course.

## Adding Pages

Add and edit pages within the /_pages directory. [Example]({{ "/page" | absolute_url}})

Set the titles, permalinks, and order in the frontmatter. (Between the lines of three dashes at the top.)

All pages will appear in the menu to the left. For example, the page with an order of 1 will appear first in the list, followed by the page with an order of 2, etc.

## Markdown

All pages are written in Markdown. See [Basic Syntax](https://www.markdownguide.org/basic-syntax/)

## Multimedia

To add images to a page, add them to the /assets/img folder. Either use the complete path in the image source, including the repository, or use a path relative to the root of this project with the Jekyll filter ``absolute_url``. Examples:

    ![Artistic rendering of computers](/systems-librarianship/assets/img/binary-monitor-particles-600px.jpg)
    
    ![Artistic rendering of computers]({{ "/assets/img/binary-monitor-particles-600px.jpg" | absolute_url }})

To embed YouTube videos, use the iframe embed code. Example:

    <iframe width="560" height="315" src="https://www.youtube.com/embed/08VDn3vdD4A?si=EBxc050TnfEXUjAV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen\></iframe>
