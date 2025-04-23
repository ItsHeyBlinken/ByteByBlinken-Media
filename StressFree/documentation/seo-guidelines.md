# SEO Guidelines for Stress Free Events and Weddings Website

This document provides guidelines for maintaining and improving the search engine optimization (SEO) of the Stress Free Events and Weddings website.

## Table of Contents

1. [Meta Tags](#meta-tags)
2. [Page Structure](#page-structure)
3. [Content Guidelines](#content-guidelines)
4. [Image Optimization](#image-optimization)
5. [Technical SEO](#technical-seo)
6. [Local SEO](#local-seo)
7. [Monitoring and Analytics](#monitoring-and-analytics)

## Meta Tags

Each page should include the following meta tags:

### Required Meta Tags

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="[UNIQUE DESCRIPTION - 150-160 characters]">
<title>[PAGE TITLE] - Stress Free Events and Weddings</title>
<link rel="canonical" href="https://www.stressfree-events.com/[PAGE-URL]">
```

### Open Graph Tags (for Social Media)

```html
<meta property="og:type" content="website">
<meta property="og:title" content="[PAGE TITLE] - Stress Free Events and Weddings">
<meta property="og:description" content="[SOCIAL DESCRIPTION - Can be same as meta description]">
<meta property="og:image" content="[IMAGE URL]">
<meta property="og:url" content="https://www.stressfree-events.com/[PAGE-URL]">
<meta property="og:site_name" content="Stress Free Events &amp; Weddings">
```

### Meta Description Guidelines

- Keep descriptions between 150-160 characters
- Include relevant keywords naturally
- Make it compelling and action-oriented
- Each page should have a unique description
- Accurately summarize the page content

## Page Structure

### Heading Hierarchy

- Use only one `<h1>` tag per page (main title)
- Use `<h2>` tags for main sections
- Use `<h3>` and `<h4>` tags for subsections
- Maintain a logical hierarchy (h1 → h2 → h3 → h4)
- Include keywords in headings where natural

### URL Structure

- Use descriptive, keyword-rich URLs
- Keep URLs short and readable
- Use hyphens to separate words (not underscores)
- Avoid special characters and unnecessary parameters

Example: `https://www.stressfree-events.com/services/full-service-wedding-planning`

## Content Guidelines

### General Content Guidelines

- Create unique, valuable content for each page
- Aim for at least 300-500 words of content per page
- Include relevant keywords naturally throughout the content
- Break up text with headings, paragraphs, and lists
- Update content regularly to keep it fresh

### Keyword Usage

- Research keywords relevant to wedding planning in DFW
- Include primary keywords in:
  - Page title
  - Meta description
  - H1 heading
  - First paragraph of content
  - Throughout the body content (naturally)
- Use related keywords and synonyms throughout the content
- Avoid keyword stuffing

### Blog Content

- Create regular blog posts (aim for at least 2 per month)
- Focus on topics relevant to wedding planning
- Use the blog templates provided in the `blog-posts` directory
- Include internal links to relevant service pages
- Add external links to authoritative sources when appropriate

## Image Optimization

### Image File Guidelines

- Use descriptive, keyword-rich filenames (e.g., `outdoor-wedding-ceremony-dallas.jpg`)
- Compress images before uploading (aim for under 200KB per image)
- Use appropriate dimensions (see [Image Sizes](#image-sizes))
- Use JPG for photographs, PNG for graphics with transparency, and SVG for logos/icons

### Alt Text

- Add descriptive alt text to all images
- Include relevant keywords naturally
- Describe the image accurately
- Keep alt text under 125 characters

Example: `<img src="images/gallery/ceremony/outdoor-ceremony-dallas.jpg" alt="Outdoor wedding ceremony with floral arch at Dallas botanical garden">`

### Image Sizes

| Image Type | Recommended Width | Recommended Height | Notes |
|------------|------------------|-------------------|-------|
| Hero Images | 1920px | 1080px | 16:9 aspect ratio |
| Content Images | 800px-1200px | Varies | Maintain aspect ratio |
| Gallery Thumbnails | 600px | 400px | 3:2 aspect ratio |
| Gallery Full Size | 1600px | 1067px | 3:2 aspect ratio |
| Team Photos | 400px | 400px | 1:1 aspect ratio (square) |
| Logo | 200px | Varies | Maintain aspect ratio |

## Technical SEO

### Structured Data

The website uses Schema.org structured data to provide search engines with detailed information about the business. The following structured data is implemented:

- Local Business / Event Planner schema on the homepage
- BreadcrumbList schema on all pages (to be implemented)
- FAQPage schema on the FAQ section (to be implemented)

To add or update structured data:

1. Use the [Schema Markup Generator](https://technicalseo.com/tools/schema-markup-generator/) to create the JSON-LD code
2. Add the generated code to the `<head>` section of the relevant page

### XML Sitemap

The sitemap.xml file helps search engines discover and index all pages on the website. Update the sitemap when:

- Adding new pages
- Removing pages
- Making significant changes to existing pages

To update the sitemap:

1. Open `sitemap.xml`
2. Add/remove/update the relevant `<url>` entries
3. Update the `<lastmod>` date to reflect the changes

### Robots.txt

The robots.txt file controls which pages search engines can access. The current configuration allows all search engines to access all pages except for specific development and example files.

To update robots.txt:

1. Open `robots.txt`
2. Add/remove/update the relevant directives
3. Be careful not to accidentally block important pages

## Local SEO

As a wedding planning business serving the Dallas-Fort Worth area, local SEO is crucial.

### Google Business Profile

- Claim and verify the Google Business Profile
- Keep business information up to date
- Add high-quality photos regularly
- Respond to all reviews promptly
- Create Google Posts for special offers and events

### NAP Consistency

Ensure Name, Address, and Phone number (NAP) information is consistent across:

- Website footer
- Contact page
- Google Business Profile
- Social media profiles
- Online directories and listings

### Local Keywords

Include location-specific keywords throughout the website:

- "Dallas wedding planner"
- "Fort Worth wedding coordinator"
- "DFW wedding planning services"
- "North Texas wedding venues"

## Monitoring and Analytics

### Google Analytics

Set up Google Analytics to track website performance:

1. Create a Google Analytics account
2. Add the tracking code to all pages
3. Set up goals for contact form submissions and consultation bookings
4. Monitor traffic, user behavior, and conversion rates

### Google Search Console

Set up Google Search Console to monitor search performance:

1. Verify ownership of the website
2. Submit the sitemap
3. Monitor search queries, click-through rates, and indexing issues
4. Address any errors or warnings promptly

### Regular SEO Audits

Conduct regular SEO audits to identify and address issues:

1. Check for broken links
2. Ensure all pages have proper meta tags
3. Verify mobile-friendliness
4. Monitor page speed
5. Review content for keyword optimization

## Additional Resources

- [Google's SEO Starter Guide](https://developers.google.com/search/docs/beginner/seo-starter-guide)
- [Moz's Beginner's Guide to SEO](https://moz.com/beginners-guide-to-seo)
- [Schema.org Documentation](https://schema.org/docs/gs.html)
- [Google Search Console Help](https://support.google.com/webmasters)
- [Google Analytics Help](https://support.google.com/analytics)
