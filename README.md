# garden

"가든" channel of the [content-syndication](https://github.com/Chano-KR/content-syndication)
pipeline — a [Quartz](https://quartz.jzhao.xyz) site that renders the Obsidian
SoT notes **~1:1** (no channel rewrite).

- Notes are written into `content/` by `channels/garden/publish.py` in the
  content-syndication repo, then pushed here.
- GitHub Actions (`.github/workflows/deploy.yml`) builds and deploys to GitHub
  Pages on every push to `v5`.
- Live: https://chano-kr.github.io/garden

Local preview: `npm ci && npx quartz build --serve`
