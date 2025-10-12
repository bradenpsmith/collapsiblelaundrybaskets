
# CollapsibleLaundryBaskets.com — Jekyll Site

World's Greatest Authority on collapsible laundry baskets. (We checked. No one else wanted the title.)

## One‑click deploy (GitHub Pages)
1. Create a new **public** repo on GitHub, e.g. `collapsible-laundry-baskets`.
2. Upload these files (or drag/drop the whole folder).
3. Go to **Settings → Pages**:
   - Source: **Deploy from a branch**
   - Branch: **main / root**
4. Optional: Add your custom domain under **Pages → Custom domain** (and put the same domain in the `CNAME` file).

## Local development
```bash
bundle install
bundle exec jekyll serve
# open http://127.0.0.1:4000/
```

## Where to put posts with affiliate links
Create Markdown files in `_posts/` with front matter.
Use `{% include disclosure.html %}` or set `affiliate_disclosure: true` in front matter.
