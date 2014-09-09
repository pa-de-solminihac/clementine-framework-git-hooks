clementine-framework-git-hooks
==============================

Git hooks to enforce best practices.

__pre-commit__

A simple hook to forbid committing UTF8-with-BOM PHP files.

Install
---

```
cd /path/to/project/.git/hooks/ && /RELATIVE/PATH/to/clementine-git-hooks/pre-commit && cd -
```

__Remarque__
Lors de la création du lien symbolique, il est important que le chemin soit relatif au dossier .git/hooks ! Il semble que git évalue le lien symbolique depuis l'intérieur du dossier .git/hooks 
[Source](cf. http://stackoverflow.com/questions/4592838/symbolic-link-to-a-hook-in-git)
