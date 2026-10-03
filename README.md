# gist-rs Scoop bucket

Manifest-only bucket for gist-rs binaries. Source-free by policy: every
manifest installs a **prebuilt release binary** — no source is published
here.

## Use

```powershell
scoop bucket add gist-rs https://github.com/gist-rs/scoop-bucket
scoop install cargo-refine   # the `cargo refine` lint healer
scoop install riir-reflex    # the `reflex` modelless decision engine
```

Manifests are added with each release and land as commits or pull
requests — a human merges after checking the hash against the release's
`SHA256SUMS`.
