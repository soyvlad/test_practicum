# My first training README.md for GitHub
----------------------------------------
<br>

#### It's a big deal to start *coding from scratch*
<br>
 However, **everything can be reached** with a <b>plan<b>, having <b>dreams and goals<b>.
<br>

1. Use official [open-sources] (https://dart.dev/guides "Dart guide") for studying
2. Downloaded anything you need to work
3. Keep calm and practice!
<br>
-----------------------------------------
<br>

#### I pushed this file.md using GIT Bash
<br>

```bash
git add README.md && git commit -m "New DEMO README file" && git push

```
<br>
-----------------------------------------

#### My scheme plan:
<br>

```mermaid

flowchart TD

A [Need to git it into GitHub] --> B {Is it <b>untracked<b>?};
A [Need to git it into GitHub] --> C {Is it <b>modified<b>?};
B -- YES?! So, <i>git add<i> --> D [<b>Staged + tracked<b>];
C -- YES?! So, <i>git add<i> --> D [<b>Staged + tracked<b>];
D -- <i>git commit<i> --> E [Finally it's <tracked>];

```