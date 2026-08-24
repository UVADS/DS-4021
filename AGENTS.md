# Repository Instructions

This repository contains university course materials, primarily Jupyter notebooks. Apply these instructions to all files and directories in the repository.

## Course authority and organization

- Treat the new syllabus in `syllabus/` as the authoritative source for course organization, ordering, modules, topics, lectures, labs, and assignments.
- Preserve the pedagogical and academic meaning of all course materials.
- Keep the repository suitable for eventual conversion into a Jupyter Book. Maintain clear module ordering, stable relative links, consistent filenames, and a clean separation between student-facing, instructor-only, and archived material.
- Preserve data files, images, helper scripts, downloadable files, and relative resource relationships when moving or editing materials.
- Do not delete unused or obsolete course material. Move it to `archive/` unless explicitly instructed to delete it.

## Jupyter notebook safety

- Never execute notebooks unless explicitly instructed.
- Never clear, regenerate, or otherwise modify notebook outputs unless explicitly instructed.
- Prefer editing prose only in Markdown cells.
- Do not change executable code merely while proofreading.
- Do not change equations, mathematical notation, numerical values, results, or technical claims unless explicitly instructed.
- Do not alter notebook kernels or metadata unnecessarily.
- When a notebook is moved, inspect its local resource references carefully. Update relative paths only when necessary to preserve the existing relationship and behavior.
- Avoid broad notebook-JSON rewrites. Make the smallest targeted change needed and preserve unrelated cells, outputs, metadata, and formatting.

## Academic integrity and editorial judgment

- Do not invent citations, sources, quotations, results, or supporting evidence.
- Flag substantive corrections, ambiguous mappings, and uncertain technical or pedagogical changes for human review rather than guessing.
- Distinguish clearly between mechanical corrections and changes that could alter academic meaning.

## Change management

- Make changes in small, reviewable batches.
- Preserve unrelated user changes and existing worktree modifications.
- Do not publish, upload, push, open pull requests, or otherwise distribute anything externally unless explicitly instructed.
- Before completing any repository-wide task, check `git status` and summarize the modified, added, moved, deleted, and untracked files relevant to the task.
- When practical, also report verification performed, paths or links changed, material deliberately left unchanged, and unresolved issues.
