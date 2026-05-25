# Leetcode

Daily Leetcode solutions. One notebook or file per problem, grouped by topic.

## Branches

Each topic has its own branch. Do all work on that branch, push it, then merge into `main`.

| Topic | Branch |
|-------|--------|
| Arrays | `arrays` |
| *(add rows as you create branches)* | |

### Start a new topic

```bash
git checkout main
git pull origin main
git checkout -b <topic>    # e.g. trees, dynamic-programming
```

### Daily workflow (on a topic branch)

```bash
git checkout arrays        # or your current topic
# solve problems, save notebooks...
git add .
git commit -m "Add: 1929 Concatenation of Array"
git push -u origin arrays  # first push only needs -u; after that: git push
```

### Merge topic into main

```bash
git checkout main
git pull origin main
git merge arrays           # replace with your topic branch
git push origin main
```

On GitHub you can also open a pull request from `arrays` → `main` instead of merging locally.

## Structure

Organize by topic in filenames or folders, e.g. `arrays.ipynb` or `arrays/1929-concatenation.ipynb`. Name files with problem number when possible: `1929-concatenation-of-array`.
