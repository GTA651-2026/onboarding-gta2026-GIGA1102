# Rétroaction automatisée -- S01 (L'IA générative et l'ère agentique : orchestrer des experts sans en être un)

_Générée le 2026-05-28T20:19:30+00:00 -- Run `20260528T200936Z-acdfcf6a`_

Ce document est produit par un pipeline reproductible (vérification SQL déterministe + analyse LLM du brief et de la déclaration IA). Une revue humaine précède toujours sa publication. **À ce stade expérimental, aucune note ni étiquette de niveau n'est diffusée : l'objectif est purement formatif.**

---

## 1. Vérification automatique de la requête SQL

La vérification automatique n'a pas pu être réalisée (gate non applicable (type=text_artifact, must_run=False)).


## 2. Rétroaction pédagogique sur le brief

> Le brief identifie le cas Klarna et décrit un rôle d'agent pour le service client avec des estimations de gains de temps et de couverture. Cependant il manque de contextualisation organisationnelle, d'une grille justifiant les scores et de mitigations/mesures concrètes pour convaincre un comité de direction.

### Observations par dimension

**Contexte organisationnel**
- Observation : Le brief se contente d'indiquer «Le cas choisi est Klarna» sans définir taille, secteur, budget ni différencier PME vs grande entreprise.
- Piste d'amélioration : Ajouter une description chiffrée du contexte (taille, secteur, budget) et expliquer comment la recommandation diverge pour une PME vs une grande entreprise.

**Justification criteres**
- Observation : Aucune grille d'évaluation avec les quatre critères (impact, faisabilité, risque, coût) et leurs justifications n'est fournie.
- Piste d'amélioration : Présenter une matrice pour les trois agents avec une justification factuelle ou une hypothèse vérifiable pour chaque critère et chaque cellule.

**Role specialise identifie**
- Observation : Vous écrivez : «L'agent a comme rôle orchestré d'être un spécialiste en service client.»
- Piste d'amélioration : Illustrer par un exemple métier concret (ex. : prioriser réclamations à haute valeur) et préciser une tâche mesurable pour montrer la valeur métier.

**Recommandation argumentee**
- Observation : Le document propose un plan de mise en place mais n'expose pas une recommandation claire ni les compromis entre options.
- Piste d'amélioration : Formuler une recommandation finale par contexte (PME vs grande entreprise) et expliciter pourquoi les autres options sont écartées (avantages/inconvénients).

**Role specialise**
- Observation : Le rôle est nommé «spécialiste en service client» mais aucun expert humain remplacé/augmenté n'est précisé.
- Piste d'amélioration : Identifier l'expert humain ciblé (ex. : agent de support niveau 1) et expliquer pourquoi ce rôle est stratégique pour Klarna.

**Probleme affaires**
- Observation : Vous indiquez comme problème : «gestion de millions de conversations à l'échelle mondiale.»
- Piste d'amélioration : Ajouter un ancrage chiffré supplémentaire (ex. : volume annuel, coût actuel du support, ou taux de résolution) pour mieux convaincre un comité exécutif.

**Valeur creee**
- Observation : Vous affirmez que l'agent gère en moyenne les 2/3 des discussions (~700 agents), disponible 24/7 et réduit la durée d'interaction de 11 à ~2 minutes.
- Piste d'amélioration : Citer la source publique de ces chiffres et traduire la réduction de temps en impact financier (ROI) ou en économies de coûts opérationnels.

**Risque mitigation**
- Observation : Les risques sont listés (déséquilibre humains/IA, sécurité des données, exactitude) et la mitigation évoquée comme «paramétrage dynamique» sans détails actionnables.
- Piste d'amélioration : Proposer des mitigations concrètes (ex. : human-in-loop pour escalade, chiffrement PII, audits périodiques, SLA fournisseur) et quand les appliquer.

**Condition succes**
- Observation : Vous décrivez un plan de mise en place, expertise, formation et mesure de performance mais sans indicateur temporel précis.
- Piste d'amélioration : Définir une condition de succès vérifiable (ex. : taux d'adoption > 80% en 6 mois ou réduction des interventions humaines de 50% en 12 mois).

**Ai disclosure**
- Observation : Le brief inclut seulement un rappel : «mettez a jour ai-usage.md», sans fournir le fichier ni préciser l'usage d'IA.
- Piste d'amélioration : Inclure un ai-usage.md indiquant les outils utilisés (ou «aucun»), l'étape d'utilisation, la validation humaine et les limites observées.

## 3. Déclaration d'utilisation de l'IA

> La déclaration précise l'outil utilisé et décrit l'étape d'aide ainsi que les vérifications effectuées. Il manque toutefois une mention explicite des limites/erreurs observées et la version/modèle exact(e) de l'outil.

**Sujets bien couverts dans votre déclaration :**

- à quelle étape l'IA a été utilisée
- comment la sortie a été validée par l'humain

**Sujets à ajouter ou expliciter pour la prochaine itération :**

- outils utilisés (nom + version/modèle)
- limites ou erreurs observées

## 4. Pistes d'action pour la prochaine itération

- Compléter `ai-usage.md` en y ajoutant : outils utilisés (nom + version/modèle).
- Compléter `ai-usage.md` en y ajoutant : limites ou erreurs observées.

---

## 5. Traçabilité

- **Run ID :** `20260528T200936Z-acdfcf6a`
- **Devoir :** `S01`
- **Étudiant·e :** `GIGA1102`
- **Commit analysé :** `83edffe`
- **Audit (côté instructeur) :** `tools/instructor/feedback_pipeline/audit/20260528T200936Z-acdfcf6a/GIGA1102/`
- **Prompts (SHA-256) :**
  - `rubric_grader_system` : `505f32d1d8319d66...`
  - `ai_usage_grader_system` : `81cb7fdf89bda55a...`
- **Fournisseur (rubrique) :** `openai`
- **Fournisseur (IA-usage) :** `openai` (gpt-5-mini-2025-08-07)

_Ce feedback a été produit par un pipeline automatisé et **revu par l'équipe pédagogique avant publication**. Aucun chiffre ni étiquette de niveau n'est diffusé à ce stade expérimental : l'objectif est uniquement formatif. Ouvrez une issue dans ce dépôt pour toute question._
