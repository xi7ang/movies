# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Project Overview

This is a Chinese movie recommendation resource repository (`mswnlz/movies`) that serves as a curated collection of film recommendations, entertainment guides, and media resources.

## Common Commands

### Resource Management
```bash
# Create new monthly resource file
touch $(date +%Y%m).md

# View recent resource files
ls -la 2025*.md | head -5

# Search for movie topics
grep -r "电影" *.md
grep -r "movie" *.md
```

## Content Guidelines

- Use consistent formatting with descriptive titles
- Keep resource titles clean; do not append obsolete branding or domain suffixes. If a site link is needed, use https://pan.devmini.space
- Organize resources by genre and rating
- Provide both Chinese and English descriptions where applicable
