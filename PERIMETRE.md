# PÉRIMÈTRE — HLP/hlp-media

## Mission (1 phrase)
Servir de dépôt distant public des médias (photos, vidéos) publiés par @habitationlapinede — le poids lourd hors du repo de code.

## Je possède (source de vérité — fait foi en cas de doublon)
- Médias publiés bruts : `posts/{YYYY-MM}/…`, `stories/{YYYY-MM}/…` (miroir publié, jamais la référence — cf. Interfaces)

## Je fais / je ne fais PAS
- ✅ Héberger les fichiers médias que `HLP/hlp-social` dual-écrit ici, servis publiquement à Meta et aux autres plateformes
- ⛔ Je ne suis PAS la source de vérité du contenu (copy, calendrier, statut) → `HLP/hlp-social/docs/calendrier-editorial.md`
- ⛔ Je ne décide rien (pas de strategist/copywriter/QC ici) — pur stockage dérivé

## Interfaces
- **J'entre** : rien (pas de pull actif — je reçois en écriture depuis `HLP/hlp-social`)
- **Je sors** : les fichiers médias servis en URL raw GitHub, consommés par le cron de publication et les plateformes tierces
- **Miroirs** : `HLP/hlp-social/content/…` **fait foi** (source + rendu) ; ce repo est le miroir publié, rafraîchi par dual-write depuis `HLP/hlp-social`. `privacy-policy.html` : **doublon périmé, ne fait PAS foi** (arbitré 2026-08-02 → `HLP/habitation-la-pinede/privacy-policy.html` fait foi). Texte juridique identique, mais cette copie date du 22/05 et référencerait 5 icônes absentes de ce repo. À supprimer après vérification qu'aucun portail développeur ne pointe son URL raw.

## M'adresser un travail
Adressage : `send_message` à une session ouverte sur ce dossier, sinon agent d'exécution lancé directement dedans (jamais de chip) · cwd=`/Users/benjamindupouy/Developer/Claude-Projet/HLP/hlp-media` — usage attendu quasi nul en écriture directe : les écritures normales passent par le dual-write de `HLP/hlp-social`, pas par une session ouverte ici.
