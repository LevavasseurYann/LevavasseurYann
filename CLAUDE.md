# github-profile — Contexte agent

> Source de vérité du profil GitHub de Yann Levavasseur.
> Ce projet local est connecté au repo spécial `levavasseuryann/levavasseuryann` sur GitHub,
> dont le README.md s'affiche automatiquement en haut du profil public.

---

## Ce que contient ce projet

```
github-profile/
├── README.md   → le profil GitHub (source de vérité — pousser après chaque modif)
└── CLAUDE.md   → ce fichier
```

## Positionnement de Yann

| | |
|---|---|
| **Titre** | Senior Data Engineer — Databricks & Azure · Cloud, DevOps & IaC |
| **Statut** | Freelance, disponible |
| **Localisation** | Lille (59), remote-first, ouvert France & Europe |
| **Stack cœur** | Databricks, Azure, Terraform, PySpark, Python |
| **Stack solide** | GCP / BigQuery, Airflow, dbt, FastAPI, Docker |
| **TJM** | ~650 €/j — **ne pas afficher sur GitHub** (profil public) |

Profil complet, CV, historique missions → `C:\Users\levav\Documents\Claude\Projects\CRM\_contexte\PROFIL.md`

---

## Repos mis en avant (pinnés sur GitHub)

| Repo | Pourquoi épinglé |
|---|---|
| `airflow-bigquery` | Démontre Airflow 3 / dbt / BigQuery / Cosmos — reflète l'expérience Adeo (3 ans GCP/BigQuery chez Leroy Merlin Group) |
| `dbt-bigquery` | Démontre analytics engineering dbt / BigQuery — refonte du repo prévue (ne pas upgrader le README avant) |

**Narrative** : les deux repos sont GCP-focused mais appliquent les mêmes standards
(IaC, CI, tests, docs) que sur ses plateformes Azure/Databricks. Ils documentent
l'expérience GCP terrain (Adeo, 3 ans) et comblent le gap perçu "il ne fait que Azure".

---

## Liens à renseigner dans README.md

```
YOUR_LINKEDIN  → slug LinkedIn de Yann  (ex. yann-levavasseur-XXXX)
YOUR_MALT      → slug Malt de Yann      (ex. yannlevavasseur)
```

Chercher les vraies valeurs dans le CRM ou demander à Yann avant de pousser.

---

## Règles de maintenance

1. **Mise à jour README** à chaque : nouveau repo vitrine, changement de disponibilité, nouvelle mission marquante à mettre en avant
2. **Langue** : anglais uniquement (audience internationale + recruteurs hors France)
3. **Pas de TJM** sur le profil (public, indexé)
4. **Repos pinnés** : max 6 sur GitHub — prioriser qualité > quantité
5. **dbt-bigquery** : attendre la refonte du repo avant d'upgrader sa description dans le README

## Quand mettre à jour

- Nouvelle mission démarrée ou terminée → mettre à jour la ligne "Available"
- Nouveau repo vitrine poussé → ajouter une ligne dans la table Portfolio
- Changement de stack principal → mettre à jour le bloc "Stack"

---

## Déploiement

```bash
git add README.md
git commit -m "update: <ce qui a changé>"
git push origin main
```

Remote : `https://github.com/levavasseuryann/levavasseuryann`
