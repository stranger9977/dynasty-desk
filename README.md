# dynasty-desk

A rendered, phone-readable copy of one thing: the September 5, 2026 "Make it (dy)Nasty"
league write-up, so it can be opened from a link instead of a local file.

**It is an unedited draft.** It was machine-written as a first pass for Nick to rewrite.
It is not finished copy and is not meant to be read as such. The page says so at the top.

- Live page: https://stranger9977.github.io/dynasty-desk/
- Source markdown, data pulls, and derivation scripts live outside this repo, in
  `~/sq-data/make-it-dynasty/2026-09-05/`. Only the rendered page is published here.
- Every figure in the page is computed from the files listed in its appendix.
  Nothing is from memory.

## Rebuild

```sh
cd ~/sq-data/make-it-dynasty/2026-09-05
python3 build_page.py DRAFT-claude-van-pelt.md ../site/index.html
```

The page is set to `noindex` and `robots.txt` disallows crawlers, but the repo is
public, so treat the URL as shareable-but-not-secret.
