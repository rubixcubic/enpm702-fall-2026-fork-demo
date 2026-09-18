# contributors

One file per person. Add yours, do not edit anyone else's.

## Naming

Name the file after your **GitHub username**, lowercase, with the `.md`
extension:

```
contributors/octocat.md
```

Your GitHub username is the one in your profile URL
(`https://github.com/octocat`), not your display name and not your
directory ID.

## Adding yours

```bash
# on your fork, on a branch
git switch -c feature/add-octocat

cp contributors/TEMPLATE.md contributors/octocat.md
# edit the file, then:

git add contributors/octocat.md
git commit -m "Add octocat to contributors"
git push origin feature/add-octocat
```

Then open a pull request from your fork against this repository's `main`.

## Why one file each

Because a pull request that adds a new file cannot conflict with a pull
request that adds a different new file. Thirty of you can open pull
requests at the same time and every one of them merges, in any order,
with nothing to resolve.

If instead everyone appended a section to the same `README.md`, the first
pull request would merge and every later one would have to be rebuilt by
hand. That is not a Git problem. It is a repository layout problem, and
you avoid it by deciding, up front, who owns which file.
