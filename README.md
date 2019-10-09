# eddex.github.io
the eddex blog for eddex stuff

## theme

https://github.com/josephhutch/aether

## repo

- branch `hugo`: source code
- branch `master`: built sources

### usage:
1. clone this repo
2. `rm -rf public` (should not be there, just to be sure)
3. `git worktree add -B master public origin/master`
4. `hugo`

Now if you `cd` into `public/` you are automatically on the `master` branch.

To publish the page use [build_and_commit_to_master.sh](https://github.com/eddex/eddex.github.io/blob/hugo/build_and_commit_to_master.sh) and then `cd public && git push`.
