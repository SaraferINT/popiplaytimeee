# Landing EN — Open in browser

Landing linked from the TikTok bio. Detects whether the user is inside the app and, if not, automatically redirects to the blog article.

## Structure

```
.
├── index.html
└── videos/
    └── tutorial.mp4   (muted, autoplay, loop, playsinline)
```

## Change destination

In `index.html`, top script block:

```js
var target="https://zumitos33top.esbine.com/category/roblox/";
```

The same URL also appears in the `.redir-box` fallback link (`<a href="…">Continue</a>`): update both places if you want to point somewhere else.

## Deploy

Settings → Pages → Source: `main` / root. URL: `https://user.github.io/<repo>/`.
