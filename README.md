# Talos project website

Jekyll site for the Talos capstone (UCSB ECE 189A), served by GitHub Pages at
https://alexander-reyes9.github.io/Capstone_Website/

## Branches

- `dev`: work in progress. Commit and push changes here.
- `main`: the deployed site. GitHub Pages builds from this branch.

To deploy, merge `dev` into `main`:

```sh
git checkout main
git merge dev
git push origin main
git checkout dev
```

## Run locally

```sh
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000/Capstone_Website/
