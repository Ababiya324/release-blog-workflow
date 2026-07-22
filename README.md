# Release Blog Draft Workflow

A [gh-aw](https://github.com/githubnext/gh-aw) agentic workflow that drafts an
Adoptium release blog post near the end of a release period. All GitHub data is
gathered deterministically before the agent runs; the agent only assesses the
material and writes a review-ready draft, filed as an issue for a human to review.

Trigger it from the Actions tab (**Release Blog Draft** → **Run workflow**).
