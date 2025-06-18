# cyberwatch

## 📦 Dépôt de publication RSS

Ce dépôt sert à **publier automatiquement les données issues de flux RSS**, générées quotidiennement par un script externe.

Les fichiers JSON sont organisés par date, versionnés via Git et accompagnés d’un lien symbolique vers le fichier le plus récent.

---

## Structure

```
\<année>/<mois>/\<nom\_flux>\_<YYYY-MM-DD>.json
daily/\<nom\_flux>\_latest.json  ← lien symbolique

```

---

## Mise à jour

Les fichiers sont ajoutés et commités automatiquement si des changements sont détectés.