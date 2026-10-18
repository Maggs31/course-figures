# Course figures

Teaching figures for the course notebooks. A notebook references a figure by a URL pinned to one commit, so a released notebook
always shows the picture it was released with, whatever is pushed later.

Layout

    course1/
      hw2/      Homework 2 figures
      hw3a/     Homework 3a figures (and hw3b, hw3c)
      r3/       Recitation 3 figures (and r4, r5, ...)
      shared/   figures reused by more than one notebook
    course2/    the same layout for the second course

Rules

- One folder per homework or recitation, pushed in one commit when that deliverable is built. Nothing else is touched in that push.
- Every folder holds a README.md listing its figures and a MANIFEST.sha1 with the hash of every file, so a build can check that what
  GitHub serves is what was reviewed.
- Files are PNG, named fig_<section>_<what-it-shows>.png, 1440 px wide for full-width figures and 768 px for half-width ones.
- A figure that changes after a release gets a new commit, and the notebook that uses it is re-released pinned to that commit. Files
  are never deleted or renamed, since older notebooks still point at them.
- No course name in any folder or file name.
