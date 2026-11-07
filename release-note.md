# Release Notes — Silo Fiscalité (domain-tax)

Toutes les versions publiées de ce dépôt respectent la spécification [SemVer 2.0.0](https://semver.org/lang/fr/).

---

## [0.0.1] - 2026-11-07

### Type de release
**Version initiale** (mise en place et validation de la structure autonome multi-dépôts)

### Résumé
Première version stable du silo Fiscalité (`domain-tax`), regroupant `tax-api` et `tax-core` avec import du BOM centralisé, cycle de build autonome et configuration de déploiement GitHub Packages.

### Changements par composant
- **`tax-api`** : contrats, ports, interface de service (calcul fiscal, projections) (aucun changement métier).
- **`tax-core`** : moteur de calcul et persistance JPA des tables fiscal_*.

### Rétro-compatibilité & Compatibilité binaire
Non applicable : version initiale, aucune version antérieure publiée.
