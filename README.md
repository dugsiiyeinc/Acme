# Project Enhancement

### Common Branch

**Purpose and Usage**

We created this branch to store common elements that are used on every page of the website. Each team member works on different pages, but some parts, like navigation links, need to be the same on all pages.

When a member finishes their page and needs to add links to other pages (like from the Home page to the Contact or Shop pages), they can use the common elements from this branch to keep everything consistent.

Using this common branch helps us:
- Keep navigation links and other shared parts the same on all pages.
- Let team members add their pages without missing important links.
- Keep our code organized and easy to manage.

This way, each member can work on their pages independently, while shared elements stay uniform and up-to-date.

### Started Code massages from here.
**Added Item Links and Background Images**

I add links to items on the Home page using a single CSS file for three HTML files. **I faced a challenge with using different pictures as background images for each item.** Since a single CSS file can only handle one background image per selector so  I resolved this issue by using internal CSS in each HTML file specifically for the background images. This allows the common styles  *h1, h2, p, links and others.* to remain in the external CSS file.
I also use Font Awesome for icons including the Twitter icon.