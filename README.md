# story-time
Toy example of collaboration through git

---
## 1. Clone Repository (only do this the first time)

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

## 2. Edits

In your text editor of choice, add a line to `story.txt` and **SAVE**.

**Optional**: Check change status. `story.txt` should be **red** to indicate it has been changed.

```bash
git status
```

---

## 3. Add and Commit

Add the newly changed file to stage
```bash
git add story.txt
```

**Optional**: check change status. `story.txt` should be **green** to indicate it has been staged on main branch.

```bash
git status
```

Commit with relevant message.
```bash
git commit -m "Tom added a story line"
```

---

## 4. Finally, Push

Push your change back on the remote Github repository.

```bash
git push
```

## 5. Pull (after remote changes)

After others have added to the story, pull in updated version to your local version.

```bash
git pull
```

---

## 6. Go to step 2.

Repeat.