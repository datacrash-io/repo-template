# repo-template

Starting layout for a new repository in datacrash-io: a `CLAUDE.md` with the working rules, a `.gitignore` that keeps
secrets out of git, and Dependabot for GitHub Actions. Use it through **Use this template** on GitHub, then replace
the sections below with what the project actually does.

## Contents

- `CLAUDE.md`: rules for people and coding agents working in the repo. Fill in the project-specific parts.
- `.gitignore`: local env files, keys and build output.
- `.github/dependabot.yml`: weekly updates for GitHub Actions.

## First steps after creating a repo from this template

1. Rewrite this README for the project.
2. Replace the placeholders in `CLAUDE.md`.
3. Add the CI and deploy workflows the project needs. Keep credentials out of the repo; store them as repository or
   environment secrets only where a job actually uses them.
