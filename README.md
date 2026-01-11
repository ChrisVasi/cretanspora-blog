# CretanSpora Blog (Static)

Greek-first starter blog for Cloudflare Pages.

## Structure
- `index.html` → home with sections + cards
- `data/posts.js` → posts list (edit here to add/remove posts)
- `posts/` → individual post pages
- `assets/css/blog.css` → styling + tokens

## Add a new post
1) Create `posts/your-slug.html`
2) Add one entry in `data/posts.js` (title/date/category/excerpt/url/tags)
3) Commit → Cloudflare auto-deploys
