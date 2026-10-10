# Fix both missing graphs

1. Extract this ZIP and upload its contents (not the ZIP itself) to `sujalnaik20/sujalnaik20`, keeping `.github/workflows/pacman.yml` in its exact folder. For a repo with existing commits, use a clone and regular commit/push — do not force-push.
2. Open repository Settings > Actions > General. Under Workflow permissions, choose Read and write permissions and Save, if allowed.
3. Open repository Actions > Update Pac-Man Contribution > Run workflow, selecting main.
4. Wait for the run to finish successfully. The workflow creates/updates the `output` branch with three SVG files: `pacman-contribution-graph.svg`, `pacman-contribution-graph-dark.svg` and `activity-graph.svg`.
5. Open the `output` branch and check the files exist. Refresh your profile with Ctrl+F5. GitHub image caching may delay updates briefly.
6. If Actions fails, click the failed run and share the red error log. The missing images cannot be fixed until GitHub runs the workflow successfully.

This setup does not use the paused third-party Activity Graph service. It generates a real 31-day contribution chart from GitHub data using the repository GitHub Actions token. The Pac-Man SVGs are generated with the official abozanona action.

## Header update
The old text-rendered banner was replaced with your exact blue anime-eyes image in `assets/anime-eyes-banner.png`. Do not omit this file when pushing. Only one greeting remains below it.
