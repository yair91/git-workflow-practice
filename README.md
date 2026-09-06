# Git Workflow Practice

Practice repository for **Homework 1** of the Software Testing course (Fall 2026).

The deliverable is a small personal portfolio website. The website itself is
intentionally simple: the point of the assignment is the **Git workflow** used
to build it, not the complexity of the product.

## Project

A static portfolio site built with plain HTML, CSS and JavaScript. No build
step, no dependencies, no framework.

## Technologies

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and semantic markup |
| CSS3 | Layout, theming, responsive design |
| JavaScript (ES6) | Small interactions (theme toggle, year stamp) |
| Git / GitHub | Version control, branching, pull requests |

## Setup

```bash
git clone https://github.com/yair91/git-workflow-practice.git
cd git-workflow-practice
open index.html
```

Any static file server works too:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Git Workflow

Branches are created from `main` and merged back through pull requests.

### Branches

| Branch | Purpose |
|---|---|
| `feature/initial-structure` | HTML skeleton for both pages and the base stylesheet |

## License

MIT. See [LICENSE](LICENSE).
