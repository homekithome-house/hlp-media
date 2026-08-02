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
- **Miroirs** : `HLP/hlp-social/content/…` **fait foi** (source + rendu) ; ce repo est le miroir publié, rafraîchi par dual-write depuis `HLP/hlp-social`. `privacy-policy.html` ici diverge de celui de `HLP/habitation-la-pinede` (152 vs 161 lignes) sans arbitrage — voir QUESTION dans le contrat `habitation-la-pinede`.

## M'adresser un travail
Chip `spawn_task` cwd=`/Users/benjamindupouy/Developer/Claude-Projet/HLP/hlp-media` — usage attendu quasi nul en écriture directe : les écritures normales passent par le dual-write de `HLP/hlp-social`, pas par une session ouverte ici.
