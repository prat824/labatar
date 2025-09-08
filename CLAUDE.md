# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a collection of HTML mockups for **Labatar**, a proteomics services marketplace platform by Alamar Biosciences. The application connects researchers with certified laboratories offering validated protein assays, particularly focusing on the Argo HT/NULISA platform and other proteomics technologies.

## Architecture & Structure

### Application Type
- Static HTML mockups with embedded CSS and JavaScript
- No build system or package management
- Self-contained files with inline styles and scripts
- No external dependencies or frameworks

### Key Pages & User Flows

**Public Marketplace:**
- `index.html` - Landing page with search functionality for tests by target, disease, or panel
- `search-results.html` - Test search results and filtering
- `browse-labs.html` - Laboratory directory with detailed lab profiles
- `browse-tests.html` - Test catalog browsing
- `test-details.html` - Individual test specifications and ordering

**User Interaction:**
- `request-quote.html` - Quote request forms
- `request-lab-quote.html` - Lab-specific quote requests
- `collaborate.html` - Research collaboration features

**Laboratory Portal:**
- `lab-login.html` - Lab authentication
- `lab-dashboard.html` - Lab admin interface for managing test listings
- `create-test-listing.html` - Test listing creation form
- `lab-leads.html` - Qualified lead management for labs

**Study Management:**
- `create-study.html` - Research study creation
- `propose-study.html` - Study proposal workflow
- `study-learn-mode.html` - Educational/learning interface

### Design System

**Brand Colors:**
- Primary Blue: `#2c4e8a`
- Accent Gold: `#f5b800`
- Background: `#f8f9fa`

**Component Patterns:**
- Consistent navigation header with Alamar logo and Labatar branding
- Card-based layouts for labs, tests, and content
- Tab interfaces for search functionality
- Status badges for test/lab verification
- Grid layouts with responsive design

### Key Features Implemented

1. **Multi-faceted Search**: Search by protein targets, diseases, or panels
2. **Laboratory Verification**: CLIA, CAP, ISO certifications displayed
3. **Platform Integration**: Argo HT, Simoa, MSD, Luminex platform support
4. **Pricing Integration**: Per-sample pricing display
5. **Collaboration Tools**: Multi-site research project support
6. **Lead Management**: Qualified lead routing for laboratories

### Development Notes

- All styling is inline within `<style>` tags in each HTML file
- JavaScript functionality is embedded in `<script>` tags
- Form submissions use basic event handling with URL parameter passing
- No server-side functionality - purely client-side mockups
- Responsive design implemented with CSS Grid and Flexbox

### File Relationships

- Navigation links connect pages in logical user flows
- Form submissions typically redirect to search results or dashboard pages
- `lab-dashboard.html` serves as the central hub for laboratory users
- `index.html` is the main entry point for researchers

### Testing & Validation

Since this is a mockup repository with no build process:
- Open HTML files directly in browsers for testing
- Validate HTML markup using browser developer tools
- Test responsive behavior across different screen sizes
- Verify form interactions and navigation flows

### Domain Knowledge

The application serves the **proteomics research community**, focusing on:
- Biomarker discovery and validation
- Clinical research applications
- Multi-site collaborations
- Regulated laboratory services
- Protein detection platforms (especially Alamar's Argo HT/NULISA technology)