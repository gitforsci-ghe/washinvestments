# man-washinvestments

A small Quarto manuscript on WASH investment trends, built on the
[`washinvestments`](https://openwashdata.github.io/washinvestments/) R data
package. It is the exercise material for the Git for Science workshop: you
practise the Git and GitHub workflow on it, the data analysis is already done.

## Workshop workflow

1. Clone your copy of this repository and open `man-washinvestments.Rproj`
2. Create a branch called `dev`
3. Edit the author details in `index.qmd` and render the document
4. Commit both changed files with the message "update author details"
5. Push, open a pull request from `dev` into `main`, and merge it

## What gets committed

A render writes exactly one output file, `docs/index.html`. After editing and
rendering you commit two files together: `index.qmd` and `docs/index.html`.
