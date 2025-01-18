# Template for building new jupyter-book lectures

This template includes

1. folder structure for adding files
2. initial `_config.yml`
3. template for `_toc.yml`
4. basic configuration of github actions for PRs and Deployment to GH-PAGES

## Steps

1. Fork this Repository
2. `git clone` the forked repo
3. Rename the repo to your project name on GitHub
4. git pull your project repo
5. add `myst` markdown files or notebooks into the `lectures` folder
6. add the names of these files to `lectures/_toc.yml`
7. build the project with `jb build lectures` at the root level of the project