# manifeste-explorer

Application locale réutilisable pour explorer un référentiel de contenu Markdown configurable.

Le chemin des données sera fourni au lancement (variable `MANIFESTE_CONTENT_DIR` ou option CLI). Aucun chemin de contenu ni dépôt distant n'est codé en dur. Le contenu du manifeste reste dans un dépôt séparé.

## Organisation prévue

- `src/` : logique Python et serveur MCP, utilisant les mêmes fonctions métier.
- `web/` : interface TypeScript/React.
- `tests/` : tests automatisés.
- `docs/` : décisions d'architecture et guide de lancement.

## État

Socle documentaire initial. Aucune dépendance à Supabase, service externe ou fournisseur d'IA n'est introduite.
