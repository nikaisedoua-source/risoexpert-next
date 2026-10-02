# RisoExpert Next

Refonte Web de RisoExpert, organisée pour évoluer vers un produit d'assistance :

```text
dist/
  index.html          Site public et démo d'espace client

Futur backend partagé
  /api/requests       Dossiers d'assistance
  /api/machines       Parc machines et catalogue
  /api/messages       Echanges client / technicien
  /api/documents      Photos, devis et rapports
  /api/notifications  E-mail, WhatsApp et push
```

## Lancer localement

```bash
cd "/Volumes/Samsung T7/Documents/Codex/RisoExpert-Next"
python3 -m http.server 4173 --directory dist
```

Ouvrir ensuite `http://127.0.0.1:4173`.

## Première itération intégrée

- accueil orienté diagnostic ;
- catalogue RISO filtrable ;
- formulaire de demande guidé ;
- espace client simulé avec dossier d'assistance ;
- design responsive inspiré des principes de profondeur et de contrôle flottant de macOS moderne.

Les données affichées sont des démonstrations locales : aucune demande réelle n'est transmise.
