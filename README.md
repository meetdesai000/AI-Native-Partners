# AI Native Partners Static Website

This project is a static website for AI Native Partners, designed to present information about the organization, its partners, capabilities, and featured insights in a professional and visually appealing manner.

## Features
- Modern, responsive design using the Bootswatch 'Lux' theme
- Home, About, Partners, Capabilities, Featured Insights, and Contact pages
- Easy-to-update content structure
- Accessible and SEO-friendly
- Deployed via GitHub Pages

## Getting Started
1. Clone the repository
2. Open the project in your preferred code editor
3. Edit content in the respective HTML/Markdown files
4. Push changes to the main branch to trigger deployment (if using GitHub Pages)

## Deployment
This site is deployed using GitHub Pages. To deploy:

1. Push your project to a GitHub repository.
2. In your repository settings, go to the "Pages" section.
3. Set the source to the `/docs` folder on the `main` branch.
4. Save and wait for GitHub Pages to build and deploy your site.
5. Visit the provided URL to verify your site is live.

For more details, see: [GitHub Pages Documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages)

## License
[Apache-2.0](../LICENSE)

## Managing Featured Insights

To add or update insights on the Featured Insights page:
1. Open `docs/featured-insights.html` in your code editor.
2. Each featured insight is represented by a `<div class="col">...</div>` block inside the main content area.
3. Duplicate an existing block to add a new insight, or edit the content and image URLs as needed.
4. Save your changes and commit them to update the site.

You can use placeholder images or replace them with your own.

## Testing & Review

### Manual Testing
- Open each page in your browser and verify correct layout and navigation.
- Test responsiveness by resizing the browser window or using device emulation.
- Check that the navbar, links, and forms are keyboard accessible.
- Ensure color contrast is sufficient for all text and UI elements.
- Proofread all placeholder content and update as needed.

### Automated Testing (Optional)
- Use tools like [Lighthouse](https://developers.google.com/web/tools/lighthouse), [axe](https://www.deque.com/axe/), or [WAVE](https://wave.webaim.org/) for accessibility and SEO audits.

### Review Checklist
- [ ] All pages load without errors
- [ ] Navigation works on all devices
- [ ] Content is accessible and readable
- [ ] SEO tags are present and correct
- [ ] Placeholder content is replaced as needed 