# enpm702-fall-2026-fork-demo

Practice repository for the ENPM702 fork and pull request tutorial
(Fall 2026). Nothing here is real software. The repository exists so that
you can fork it, open a pull request, have it reviewed, and watch your
change travel back down to your own machine.

## What to do

1. **Fork** this repository. You now own a copy at
   `your-username/enpm702-fall-2026-fork-demo`.
2. **Clone your fork** and add this repository as `upstream`.
3. Create a branch: `git switch -c feature/add-your-username`
4. Copy `contributors/TEMPLATE.md` to `contributors/your-github-username.md`
   and fill it in.
5. Commit, push to **your fork**, and open a pull request against this
   repository.

Full instructions are in
[contributors/README.md](contributors/README.md).

## Layout

```
enpm702-fall-2026-fork-demo/
|
|-- .gitignore
|-- LICENSE                    Apache-2.0
|-- README.md                  this file
|
|-- contributors/              one file per person, so pull requests never collide
|   |-- README.md              what to add and how to name it
|   `-- TEMPLATE.md            copy this, rename it to your username
|
`-- demo/
    `-- robot_config.yaml      shared file, used only in the live demo
```

## Why two directories

| Directory | Why it is shaped this way |
|---|---|
| `contributors/` | Your pull request adds **one new file** that nobody else touches. Every pull request merges cleanly, in any order, however many of you there are. This is the normal case. |
| `demo/` | A single file that everyone shares. Two people editing the same line is how you make a merge conflict on purpose. Used only during the live demo. Do not put your contribution here. |

That split is the point, and it is worth taking away. Most merge conflicts
are not caused by hard problems. They are caused by two people editing the
same line. A repository laid out so that contributions land in separate
files has far fewer of them. Think about that when you set up your group
project repository.

## Licence

Apache-2.0. See [LICENSE](LICENSE).
