---
title: "Reproducible Engineering Lessons"
date: 2026-11-07
layout: post
---

Today I put a simple site online through **GitHub Pages**, then used Jekyll front matter and the `minima` theme to turn a Git repository into a public learning journal.

## What I'm practicing

1. **Make work traceable:** link an issue, branch, commit, pull request, and merge.
2. **Prove changes work:** run tests locally and in GitHub Actions, and inspect coverage.
3. **Investigate CI failures:** distinguish an incorrect test expectation from an unsupported runner configuration.
4. **Protect important branches:** use required status checks before merging.
5. **Record evidence:** link verifiable training results rather than presenting an exercise as a professional certification.

## A concrete testing example

A sample Fibonacci test expected 89 at index 10, but the implementation correctly returned 55. Reproducing that failure, correcting the assertion, and adding negative-input tests brought the demonstration project to **7 passing tests and 100% statement coverage**. I also updated the hosted Python matrix after one outdated setup target failed.

## Where to find the work

See the [GitHub Skills training ledger](https://github.com/Nanodagr8/skills-idea-to-merge-with-the-copilot-app/blob/main/docs/GITHUB_SKILLS_COMPLETION_LEDGER_2026-11-07.md) for source repositories, proof links, and the distinction between GitHub Skills exercises and separately issued credentials.

The same review-before-merge principle transfers to game mathematics, quantitative simulations, cloud automation, and quantum software experiments.
