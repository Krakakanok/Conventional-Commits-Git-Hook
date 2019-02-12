# Conventional-Commits-Git-Hook
Python script to maintain the conventional commit guidelines

## Installation
```cp commit-msg proyectFolder/.git/hooks```

```chmod +x proyectFolder/.git/hooks/commit-msg```

## Usage:
### Success:
Not produce any output:

```
> git commit -m "feat(lang): added polish language"
1 file changed, 1 insertion(+)
```

```
> git commit -m "fix: minor typos in code"
5 file changed, 3 insertion(+)
```


### Fails:
```
> git commit -m "Ugly commit"
Commit message not follow Conventional Commits
```

```
> git commit -m "feat Ugly commit version 2"
Commit message not follow Conventional Commits
```
