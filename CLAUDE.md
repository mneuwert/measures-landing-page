# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static landing page for "Measures" - an iOS unit converter app. The project is a simple HTML/CSS/JavaScript website showcasing the app's features and encouraging App Store downloads.

## Architecture

- **Static Website**: Pure HTML/CSS/JavaScript with no build process or dependencies
- **Styling**: Uses Tailwind CSS via CDN + custom CSS for animations and specific styling
- **JavaScript**: Vanilla JS for smooth scrolling, intersection observer animations, and App Store click tracking
- **Assets**: Contains app screenshots in multiple languages (English/German) and SVG icons for unit categories

## File Structure

```
/
├── index.html          # Main landing page
├── privacy.html        # Privacy policy page
├── css/styles.css      # Custom styles and animations
├── js/main.js         # Landing page interactions
└── images/            # App screenshots, icons, and flags
    ├── 01_en.png      # App screenshots (English)
    ├── 01_de.png      # App screenshots (German)
    ├── *.svg          # Category icons and country flags
    └── Measures_icon_light.png  # App icon
```

## Development Commands

Since this is a static website with no build process:

- **Local Development**: Use any static file server (e.g., `python -m http.server 8000` or Live Server in VS Code)
- **No Build Required**: Files can be edited directly and viewed in browser
- **No Dependencies**: Uses CDN resources (Tailwind CSS, Google Fonts)

## Key Features

- **Responsive Design**: Mobile-first approach using Tailwind CSS utilities
- **Animations**: CSS keyframe animations for floating elements and scroll-triggered effects
- **App Store Integration**: Direct links to iOS App Store with download tracking
- **Multi-language Support**: Screenshots available in English and German
- **SEO Optimized**: Complete meta tags, Open Graph, and Twitter Card markup

## Styling Approach

- **Tailwind CSS**: Primary utility framework loaded via CDN
- **Custom CSS**: Animations, device frames, and specialized components in styles.css
- **Typography**: Inter font family from Google Fonts
- **Color Scheme**: Custom "accent" color palette defined in Tailwind config

## Content Management

- **App Screenshots**: Located in `/images/` with naming convention `{number}_{language}.png`
- **Icons**: SVG icons for unit categories and country flags
- **Text Content**: Hardcoded in HTML (no CMS or dynamic content)
- **Links**: App Store links point to actual app (ID: 287918318)