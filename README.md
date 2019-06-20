# npm test: how "auto install" packages in multiple folders?

Bitte ausprobieren:

```
  git clone https://github.com/nilshartmann/npm-test
  cd npm-test

  npm run setup
```

- Danach sollte in `frontend` und `backend` jeweils ein `node_modules`-Folder vorhanden sein.
- Im Optimallfall zeigt danach `git status` auch keine Änderungen im Repository an (zumindest nicht im Root-Verzeichnis)
