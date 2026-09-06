# Pull Request Guide for Open-Source Contributions

> The upstream `main` branch is protected. Contributors should submit changes through pull requests. Maintainers will review each PR before merging it into the repository.

## 1. Fork and Clone the Repository

Fork this repository to your own GitHub account, then clone your fork locally:

```bash
git clone https://github.com/<your-name>/Awesome-RL-for-Diffusion-Models.git
cd Awesome-RL-for-Diffusion-Models
```

Add the upstream repository once:

```bash
git remote add upstream https://github.com/lyongo/Awesome-RL-for-Diffusion-Models.git
```

## 2. Create a Working Branch

Always create a separate branch from the latest upstream `main`:

```bash
git fetch upstream
git checkout main
git merge upstream/main
git checkout -b add-paper-<short-name>
```

Use a clear branch name, such as `add-paper-ddpo`, `fix-link-rl-dllm`, or `update-survey-section`.

## 3. Make a Focused Change

Keep each PR focused on one type of update:

* Add new papers, surveys, or repositories to the correct category.
* Fix broken paper or code links.
* Improve formatting, descriptions, or metadata.
* Update images or other assets when they are directly related to the README.

When adding papers, please follow the existing table format:

```md
| YYYY-MM | `Name` | Paper Title | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](paper-url) | [![GitHub Stars](https://img.shields.io/github/stars/owner/repo?style=for-the-badge&logo=github&label=GitHub&color=black)](code-url) |
```

If no code repository is available, use `-` in the Code column. Keep each section sorted by Date from newest to oldest.

## 4. Commit Your Changes

Use a concise commit message that describes the change:

```bash
git add -A
git commit -m "add new RL diffusion papers"
```

## 5. Sync Before Opening a PR

Before pushing, sync again with upstream `main`:

```bash
git fetch upstream
git checkout main
git merge upstream/main
git checkout add-paper-<short-name>
git merge main
```

If conflicts occur, resolve them locally, then run:

```bash
git add <resolved-files>
git commit
```

## 6. Push and Open the PR

Push your working branch to your fork:

```bash
git push -u origin add-paper-<short-name>
```

Open a pull request on GitHub:

* base repository: `lyongo/Awesome-RL-for-Diffusion-Models`
* base branch: `main`
* compare repository: your fork
* compare branch: your working branch

## 7. PR Review and Merge

Maintainers will review the PR for:

* Relevance to reinforcement learning-driven diffusion models.
* Correct category placement.
* Valid paper and code links.
* No duplicate entries.
* Consistent README formatting and date ordering.

After approval, maintainers will merge the PR into `main`. Contributors should not force-push after review starts unless they are addressing requested changes.
