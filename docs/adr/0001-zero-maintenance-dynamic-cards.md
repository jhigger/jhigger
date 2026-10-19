# 0001. Use URL-Based Dynamic SVG Cards Over Scheduled Action Workflows

We decided to render real-time GitHub metrics using hosted dynamic SVG endpoints (`github-readme-stats` and `streak-stats`) instead of GitHub Actions scheduled cron workflows.

Scheduled GitHub Actions workflows on personal repositories are automatically disabled after 60 days of inactivity and require personal access tokens with elevated repository scopes. Direct SVG embeds are self-updating on page load, require zero maintenance, and present no token security surface.
