# washinvestments

A small Quarto manuscript on WASH investment trends, built on the
[`washinvestments`](https://openwashdata.github.io/washinvestments/) R data
package. It is the exercise material for the Git for Science workshop: you
practise the Git and GitHub workflow on it, the data analysis is already done.

## Workshop workflow

1. Clone your team's copy of this repository and open `washinvestments.Rproj`
2. Create a branch called `dev`
3. Edit the author details in `manuscript.qmd` (there are two author slots) and
   render the document to check it still builds
4. Commit the change with the message "update author details"
5. Push, open a pull request from `dev` into `main`, and merge it

## What gets committed

You commit the source, `manuscript.qmd`. The rendered `manuscript.html` is a build
artifact and is git-ignored, so a commit stays a single, readable change to
the manuscript source. This repository is not published; the render is only to
confirm the document still builds.
