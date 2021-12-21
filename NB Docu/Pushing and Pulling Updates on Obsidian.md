# Pushing and Pulling Notes
#git #guide 

---
###### Pulling new notes
1. If there are new notes, go to vault directory (cloned folder) and open a command line terminal.

```bash
git pull origin main
```

###### Pushing new notes

1. Go to vault directory (cloned folder) and open a command line terminal. Add changes for commit.

```bash
git add -A
```

2. Commit changes

```bash
git commit -m "[Enter your commit message here, example: added notes about SQL]"
```

3. Push to GitHub

```bash
git push origin main
```

*`Make sure that you have the latest updates before pushing, pull first before pushing changes`*