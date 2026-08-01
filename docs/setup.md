# GitHub Profile Setup

This repository is the special GitHub profile repository for `github-bian`.

## First Run

1. Create a public repository named `github-bian` under the `github-bian` account.
2. Push this repository to GitHub.
3. Open `Settings -> Actions -> General`.
4. Under `Workflow permissions`, choose `Read and write permissions`.
5. Open the `Actions` tab and run `Generate Contribution Animations` once.

The workflow publishes generated SVG files to the `output` branch. The profile
README loads those SVG files from:

- `github-contribution-grid-snake.svg`
- `github-contribution-grid-snake-dark.svg`
- `profile-3d-contrib.svg`

After the first workflow run succeeds, refresh `https://github.com/github-bian`.
