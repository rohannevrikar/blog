# Rohan's Blog

Daily learning blog built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme. Auto-deployed to GitHub Pages via GitHub Actions.

## Daily Workflow

```bash
# Create today's post
hugo new posts/$(date +%Y-%m-%d)-topic.md

# Preview locally
hugo server -D

# Publish
git add content/posts/<post-file>.md
git commit -m "TIL: topic"
git push
```

Live at: https://rohannevrikar.github.io/blog/
