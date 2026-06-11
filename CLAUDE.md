# CLAUDE.md

## What this repo is

A personal submission repo for the **AI Forward Deployed Engineer (FDE) Training**, a
12-week program. As of this writing it is **documentation only**: every tracked file is a
`README.md`. There is no application source code, no dependencies, and no build.

## Install / Run / Test

**Not applicable yet.** There is no package manager, build script, or test suite in this
repo (no `package.json`, `Makefile`, config files, or source files of any kind). Nothing to
install, run, or test. Coding deliverables are expected to land in the weekly folders as the
program progresses (likely weeks 4–7 and the capstone, 11–12); add real commands here when
they exist.

## Architecture / Layout

Note the **one-level nesting**: the git root holds a single `training-ai-fde/` folder, and
all content lives inside it. Paths are `training-ai-fde/week-NN/README.md`, not
`week-NN/README.md`.

```
training-ai-fde/            (git root)
└── training-ai-fde/
    ├── README.md           index/hub: program overview + weekly links
    ├── week-00/README.md   Setup & Diagnostic (only week with a real submission)
    ├── week-01..week-12/    one folder per week, each an empty README template
```

Each week README follows a fixed template: **Deliverables**, **Submission**, **Notes**.

## Conventions a new contributor is most likely to get wrong

1. **Content lives one level deep.** Work goes in `training-ai-fde/week-NN/`, not at the git
   root. The root only contains the `.git` dir and the nested folder.
2. **Submitting = push the work, then share the link.** Per the root README, each week you
   add files to that `week-NN/` folder, fill in its README's **Submission** section, then
   share the link (file / folder / PR / release tag, as the week specifies).
3. **No secrets in git.** The repo is public on purpose; API keys go in environment
   variables, never in a committed file.

## Unverified — please confirm

- The **Name** and **Cohort** fields in `training-ai-fde/README.md` are still placeholders
  (`*your name here*`). Fill these in.
- Whether CLAUDE.md should live at the git root (where I put it) or inside the nested
  `training-ai-fde/` folder. Root is the conventional location for Claude Code to find it.
- The exact submission format (file vs. folder vs. PR vs. tag) is "as each week specifies" —
  driven by the external lessons, which are not in this repo.
