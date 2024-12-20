## Git Hidden Folder

je tam `.git`

git init
touch Readme.md
code Readme.md
git status
git add Readme.md

## Commits

```
git commit
```

## Branches

## Remotes

## Cloning

```sh
mkdir /workspace/tmp
cd /workspace/tmp
```

### HTTPS

```sh
git clone https://github.com/skills/introduction-to-github.git
cd introduction-to-github/
```

## Add

```
git add Readme.md
git add .
```

`git add` stagne vsechny fily

## Reset

```
git reset
```

`git reset` resetuje staged fily 


## Gitconfig files

ukazuje globalni konfiguraci pro git jako je email, jmena

```
git config --list --show-origin
```

pri prvnim prihlaseni musim nastavit jmeno a email

```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

## Log

ukaze vsechny commit

```
git log
```

## Push

Pushnout repo na remote origin



