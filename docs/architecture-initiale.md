# Architecture initiale

- Référentiel de contenu séparé, sélectionné par configuration locale.
- Markdown versionné par Git comme source de vérité.
- Python pour validation, recherche textuelle et logique métier partagée par l'interface et MCP.
- Interface web TypeScript/React dans une étape ultérieure.
- Index local éventuel reconstructible depuis les sources.
- Toute modification assistée par IA reste une proposition jusqu'à validation humaine.

Décisions à confirmer avant l'implémentation : format de sérialisation des métadonnées, convention de statut, précision des références textuelles et gestion des conflits.
