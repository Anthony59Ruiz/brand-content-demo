# Brand Content (Demo)

Content-as-code system of record for a single brand's social posts. Each post is a file under `/content`; merging a post's pull request to `main` is the approval-to-publish gate.

## Workflow

1. A new post enters on a `content/...` branch as a file in `/content`.

2. A pull request opens the post for review.

3. Merging the PR approves the post for publishing.

## Post format

Each file in `/content` is markdown with YAML front matter: `platform`, `scheduled`, `status`.
