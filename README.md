# purity
A pure Ghost theme

# Roadmap to 1.0

- [x] base on Casper 1.2.7 (done in v0.1.0)
- [ ] Improve blog title representation for SEO in <title> tags (Idea)
- [ ] Make navigation adaptive based on Ghost navigation helper
- [ ] Improve site header to be a more flat title bar with blog logo (Idea)

# Ideas

## Improve blog title representation for SEO in <title> tags

Current representation is `{{@blog.title}}` for the home page and `{{title}}` for any page. This is by making use of the `{{meta_title}}` helper in Ghost.

Preferrable would be to have it as `{{@blog.title}}` for the home page and `{{title}} - {{@blog.title}}` for any blog entries.
