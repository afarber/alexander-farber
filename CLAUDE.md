# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static personal website/portfolio for Alexander Farber containing:
- Single HTML page (`index.html`) with personal information, resume links, and references
- Supporting PDF documents (resumes, certificates, references)
- Images and graphics in `images/` and `thesis/` directories
- No build process or dependencies - pure static HTML/CSS/JS

## Development Commands

This is a static website with no build process. To view locally:
- Open `index.html` directly in a web browser
- Or serve via any static web server (e.g., `python -m http.server 8000`)

## Architecture

- `index.html` - Main page with embedded CSS and JavaScript
- `README.md` - Structured links to all documents and profiles
- `images/` - Icons and profile photo
- `thesis/` - Graphics from diploma thesis
- PDF files - Resume, certificates, and employment references
- Uses Leaflet.js CDN for the location map display