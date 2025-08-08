HOW TO DEPLOY THIS POST ON GITHUB PAGES

1) Copy into your GitHub Pages repo (username.github.io):
   - _posts/2025-08-08-teensy-logic-analyzer.md
   - assets/teensy-logic-analyzer/chadilat_annotated.jpg
   - assets/teensy-logic-analyzer/ps2_decode.csv
   - _config.yml  (merge if you already have one)
   - Gemfile      (merge if you already have one)

2) Enable RSS:
   - In _config.yml ensure:
       plugins:
         - jekyll-feed
   - In Gemfile ensure 'jekyll-feed' is present. (The 'github-pages' gem bundles it.)

3) Commit & push to the default branch. Your RSS feed will be at:
   https://<your-username>.github.io/feed.xml

4) Optional: link your RSS feed in your site header/footer:
   <a href="/feed.xml">RSS</a>
