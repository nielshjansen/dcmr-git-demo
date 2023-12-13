# Workflow

## Clone project

```bash
git clone git@github.com:nielshjansen/dcmr-git-demo.git
```

## Nieuwe branch maken

```bash
git checkout -b feature/create-mkdocs-material-project
```

## Nieuwe branch naar remote (origin) pushen

```bash
git push --set-upstream origin feature/create-mkdocs-material-project
```

## Werken op de branch

### Wijzigingen toevoegen

```bash
git add docs
git add mkdocs.yml
```

### Wijzigingen commiten

```bash
git commit
```

### Nog wat wijzigingen toevoegen

```bash
git add README.md
```

### De nieuwe wijzigingen committen

```bash
git commit
```

### Wijzigingen naar de remote sturen

```bash
git push
```

## Mergen main branch

```bash
git checkout main
git pull
git checkout feature/create-mkdocs-material-project
git merge main
git push
```

## Je werk aan de branch afronden

Oplossen van door de merge ontstane problemen in je nieuwe branch

## Pull- of Merge request

Met het maken van een Pull request verzoek je de eigenaar van het project om je wijzigingen door te voeren op de main branch

## Merge in main

De eigenaar van het project voert de merge door. Vanaf dit moment zijn jouw wijzigingen in de main branch verwerkt.

