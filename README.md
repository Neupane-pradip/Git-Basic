# Git Basics

A minimal practice repository for learning how to track and commit changes with Git.

## Contents

[`hello_world.py`](hello_world.py) prints a short sequence of messages. It requires no input, packages, or configuration.

## Run

With Python 3 installed:

```sh
git clone https://github.com/Neupane-pradip/Git-Basic.git
cd Git-Basic
python hello_world.py
```

## Git practice

After making a local change, inspect and commit it:

```sh
git status
git diff
git add hello_world.py
git commit -m "Update greeting messages"
git push
```

Pushing requires write access to the remote repository. Use your own fork when practicing independently.
