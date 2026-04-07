## Overview

This is a personal blog (chrisfleming.org) built with [Jekyll](https://jekyllrb.com/)

Ruby version is managed via `.tool-versions` (currently 3.4.8).

## Commands

```bash
# Install dependencies
bundle install

# Serve locally with live reload (includes drafts)
bundle exec jekyll serve --drafts

# Build for production
JEKYLL_ENV=production bundle exec jekyll build

# Run HTML link checker (used in CI)
bundle exec htmlproofer _site --disable-external
```
