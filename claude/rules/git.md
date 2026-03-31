# Git & Deployment Rules

Repo: ffgroup-8 org on GitHub | deployed via GitHub Pages
File: always index.html at repo root

Push workflow (no confirmation needed):
  git add index.html && git commit -m "[clear description]" && git push

Commit message format:
  "Update [page name] — mark [category] complete"
  "Add content for [page name] homepage hero"
  "Fix progress bar percentages"

Never push without a meaningful commit message.
Never push broken HTML — validate structure before committing.
