---
title: "Personal Website"
description: "My personal digital garden, built with Astro and Vanilla CSS."
pubDate: 2025-11-30
tags: ["Astro", "CSS", "SSG", "i18n"]
link: "https://github.com/GtPluto/PersonalWebsite"
---

# Building My Personal Website

I decided to build this website to have a place where I can share my thoughts, learning notes, and projects without the constraints of third-party platforms.

## Tech Stack

I chose **Astro** as the framework because of its "Island Architecture" and excellent performance for content-heavy sites. It allows me to write content in Markdown (or MDX) and ship zero JavaScript to the client by default.

For styling, I opted for **Vanilla CSS**. While frameworks like Tailwind are popular, I wanted to keep things simple and have full control over the design. I used CSS variables for theming and consistent spacing.

## Key Features

### 1. Internationalization (i18n)
The site supports both English and Chinese. I implemented a custom i18n solution that:
- Routes content based on the URL (e.g., `/zh/ideas`).
- Uses a central translation file for UI elements.
- Includes a language switcher with a globe icon.

### 2. Content Collections
I use Astro's Content Collections to manage my "Ideas", "Learning Notes", and "Projects". This ensures type safety for my frontmatter and makes it easy to query and filter content.

### 3. Clean & Premium Design
The design philosophy is "content-first". I used a clean typography system, plenty of whitespace, and subtle interactions to create a premium reading experience.

## Future Plans

I plan to add more features like:
- A dark mode toggle.
- An RSS feed.
- More interactive elements for my "Ideas" section.
