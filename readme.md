# To Do

## For Launch

- [ ] Google Analytics
- [ ] Update data in `_config.`

## Content

- [ ] Update blog dates
- [ ] Update internal urls
- [ ] Update blog posts

# Documentation

## Instal

```
bundle install
```

## Local Development

```
bundle exec jekyll serve -l
```

## Production Build

```
jekyll build
```

---

## Meta Data

- Defaults are stored in `_config.yml`
- To override values use front matter

```
---
title: Home
excerpt:
---
```

---

## Styles

- All `scss` files are imported into `assets/css/styles.scss` from `_sass/`
- Bootstrap variables are overridden in `_sass/base/_var.scss`
