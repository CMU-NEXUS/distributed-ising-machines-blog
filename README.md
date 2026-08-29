# When Ising Machines Become Distributed

Interactive companion post for the paper *Accelerating Distributed Digital
Ising Machines*. The public page is:

<https://cmu-nexus.github.io/distributed-ising-machines-blog/>

The prose is in `sections/`, images are in `figures/`, and `index.html` and
`main.html` are identical entry points.

## View locally

The page loads its section files at runtime, so serve the repository over HTTP:

```bash
cd /home/tongwu2/pbit/github-pages/distributed-ising-machines-blog
python3 -m http.server 8000 --bind 127.0.0.1
```

Then open <http://127.0.0.1:8000/>. For a static, fully expanded view suitable
for screenshots, open <http://127.0.0.1:8000/?static=1&tables=1>.

## Publishing

GitHub Pages publishes the `main` branch from the repository root. In the
repository settings, select **Pages → Deploy from a branch → main → /(root)**.
