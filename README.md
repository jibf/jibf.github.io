# Binfei Ji's personal website

A small, responsive academic homepage for https://jibf.github.io/.
Plain HTML and CSS; no build process or JavaScript dependencies.

## Local preview

From this directory:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open http://127.0.0.1:8000/ and stop the server with Ctrl-C when finished.

## Editing

- `index.html`: biography, publications, experience, education, and profile links.
- `style.css`: layout, typography, and mobile styles.
- `assets/binfei-ji.jpg`: the original portrait selected by Binfei, displayed with a CSS crop.
- `assets/Binfei_Ji_Resume.pdf`: the August 24, 2026 résumé selected for download.
- `assets/favicon.svg`: simple initials icon.

Keep the footer's update date current when making substantive changes.
Keep private background notes and unpublished work details outside this repository.

## Publishing on GitHub Pages

The repository is `jibf/jibf.github.io`. Publish the site files from the root of the `main` branch
using Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
The `.nojekyll` file lets GitHub Pages serve the static files directly.

Before publishing, preview both a desktop and narrow mobile layout, check the résumé link,
and verify the visible publication and experience details.

## Content references

- [AgentSuite, ICML 2026](https://proceedings.mlr.press/v306/suh26a.html)
- [AgentSuite code](https://github.com/Agent-Suite/AgentSuite)
- [BlockBatch preprint](https://arxiv.org/abs/2605.29233)
- [BlockBatch code](https://github.com/Laurence-Wu/BlockBatch)
- [EIC Lab team](https://eiclab.scs.gatech.edu/pages/team.html)
- [Qite Li’s Peking University homepage (Chinese)](https://faculty.pku.edu.cn/liqite/zh_CN/index/7845/list/index.htm)
- [Di Jin's personal homepage](https://jind11.github.io/)

The Findings of EMNLP 2026 venue and AgentSuite equal-contribution designation were
supplied and confirmed by Binfei. BlockBatch currently links to its available arXiv page.
Experience dates and titles reflect Binfei's confirmations on October 19, 2026.
