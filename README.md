# Tiago's Blog

## Installation and running

1. Clone this repository
2. Run `cd tiagodread.github.io`
3. Init the submodule `git submodule init`
4. Update the submodule `git submodule update`
5. Build the site `hugo`
6. Run hugo server `hugo server`

```sh
git submodule add --depth=1 <https://github.com/adityatelange/hugo-PaperMod.git> themes/PaperMod
git submodule update --init --recursive # needed when you reclone your repo (submodules may not get cloned automatically)
git submodule update --remote --merge
```
