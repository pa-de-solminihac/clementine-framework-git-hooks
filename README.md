Clementine framework : git-hooks
===

Hooks Git pour éviter quelques erreurs de base

__pre-commit__

Un simple hook pour éviter d'envoyer des fichiers UTF8 avec BOM PHP.

Installation
---

```
cd /path/to/project/.git/hooks/ && /RELATIVE/PATH/to/clementine-git-hooks/pre-commit && cd -
```

__Remarque__

Lors de la création du lien symbolique, il est important que le chemin soit relatif au dossier .git/hooks ! Il semble que git évalue le lien symbolique depuis l'intérieur du dossier .git/hooks (cf. http://stackoverflow.com/questions/4592838/symbolic-link-to-a-hook-in-git)
