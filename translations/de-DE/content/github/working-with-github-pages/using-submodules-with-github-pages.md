---
title: Using submodules with GitHub Pages
intro: 'Du kannst Submodule in {{ site.data.variables.product.prodname_pages }} nutzen und damit andere Projekte in den Code Deiner Website einbinden.'
redirect_from:
  - /articles/using-submodules-with-pages/
  - /articles/using-submodules-with-github-pages
product: '{{ site.data.reusables.gated-features.pages }}'
versions:
  free-pro-team: '*'
---

Wenn das Repository für Deine {{ site.data.variables.product.prodname_pages }}-Website Submodule enthält, wird deren Inhalt automatisch beim Erstellen der Website abgerufen.

Du kannst nur Submodule verwenden, die auf öffentliche Repositorys verweisen, da der {{ site.data.variables.product.prodname_pages }}-Server nicht auf private Repositorys zugreifen kann.

Verwende die schreibgeschützte `https://`-URL für Submodule, einschließlich verschachtelter Submodule. Du kannst diese Änderung in Deiner _.gitmodules_-Datei vornehmen.

### Weiterführende Informationen

- „[Git-Tools – Submodule](https://git-scm.com/book/en/Git-Tools-Submodules)“ im _Pro Git_-Buch
- „[Jekyll-Build-Fehler für {{ site.data.variables.product.prodname_pages }}-Websites beheben](/articles/troubleshooting-jekyll-build-errors-for-github-pages-sites)“