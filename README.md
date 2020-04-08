# story-time
Toy example of collaboration through git

---
## Clone Repository

First clone a repository to our local machine to get started.
```bash
git clone https://github.com/tomkeith/story-time.git
```
Change directory into the newly cloned folder.

```bash
cd story-time
```
**Optional**: Use `ls -a` as sanity check for `.git/` folder.

---

## Edits

In your text editor of choice, add a line to `story.txt` and **SAVE**.

**Optional**: Check change status. `story.txt` should be red to indicate it has been changed.

```bash
git status
```

---

## Commit

Commit with relevant message.
```bash
git commit -m "Tom added the first line"
```

**Optional**: check change status. `story.txt` should be green to indicate it has been commited to main branch.

```bash
git status
```

---

Push your change back on the remote Github repository.

```bash
git push
```
