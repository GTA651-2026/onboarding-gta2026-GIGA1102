# Rétroaction automatisée -- S02 (Sélectionner des solutions IA : décision, opérations, productivité)

_Générée le 2026-05-28T17:32:50+00:00 -- Run `20260528T172647Z-afdf4262`_

Ce document est produit par un pipeline reproductible (vérification SQL déterministe + analyse LLM du brief et de la déclaration IA). Une revue humaine précède toujours sa publication. **À ce stade expérimental, aucune note ni étiquette de niveau n'est diffusée : l'objectif est purement formatif.**

---

## 1. Vérification automatique de la requête SQL

La vérification automatique n'a pas pu être réalisée (gate non applicable (type=text_artifact, must_run=False)).


## 2. Rétroaction pédagogique sur le brief

> Brief clair et complet : les deux contextes sont bien décrits et la grille justifie les scores par critère, conduisant à des recommandations distinctes et solidement motivées. Pour parfaire la soumission, joignez des preuves chiffrées pour une ou deux justifications clés et incluez le contenu d'ai-usage.md ou son résumé.

### Observations par dimension

**Contexte organisationnel**
- Observation : Le document définit une PME de 50 employés (Lumen Logistique inc., budget IA ~25 K$) et une coopérative de 800 employés (budget IA ~2 M$, contrainte AMF et Loi 25), et explique pourquoi la faisabilité diffère entre elles.
- Piste d'amélioration : Ajouter un tableau synthétique comparant explicitement taille, budget et maturité IT pour chaque contexte afin de rendre la différenciation encore plus immédiate.

**Justification criteres**
- Observation : La grille présente des scores pour impact, faisabilité, coût et risque avec une justification pour chaque agent et chaque contexte (ex. faisabilité Copilot=5 pour PME car M365 déjà déployé).
- Piste d'amélioration : Inclure une source chiffrée ou une hypothèse vérifiable pour au moins une justification critique (p.ex. estimation du lift de conversion alléguée pour Einstein).

**Role specialise identifie**
- Observation : Les rôles métier sont nommés clairement : 'directeur financier que la PME n'a pas', 'directeur commercial ou analyste CRM' et 'adjoint de productivité polyvalent'.
- Piste d'amélioration : Ajouter un exemple concret d'activité métier (KPI impacté) pour chaque rôle pour renforcer la connexion valeur-métier.

**Recommandation argumentee**
- Observation : La recommandation diffère par contexte: pour la PME privilégier Copilot puis pilote Brex, et pour la grande entreprise déployer Einstein en premier avec mitigations de conformité.
- Piste d'amélioration : Présenter un petit calendrier de déploiement (phases, critères de succès) pour rendre la recommandation immédiatement actionable devant un comité de direction.

**Ai disclosure**
- Observation : Le brief indique que 'ai-usage.md mis à jour à la racine du dépôt' mais le contenu détaillé de ce fichier n'est pas présent dans le brief lui-même.
- Piste d'amélioration : Joindre ou résumer le contenu d'ai-usage.md (outils, étape d'utilisation, validation humaine, limites) pour atteindre le niveau excellent.

## 3. Déclaration d'utilisation de l'IA

> La déclaration précise l'outil utilisé et décrit clairement à quelles étapes il a aidé, ainsi que les vérifications de sources effectuées. Il manque toutefois une indication explicite du modèle/version utilisé et une mention claire des limites ou erreurs observées dans les sorties générées.

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

- **Run ID :** `20260528T172647Z-afdf4262`
- **Devoir :** `S02`
- **Étudiant·e :** `GIGA1102`
- **Commit analysé :** `5546696`
- **Audit (côté instructeur) :** `tools/instructor/feedback_pipeline/audit/20260528T172647Z-afdf4262/GIGA1102/`
- **Prompts (SHA-256) :**
  - `rubric_grader_system` : `505f32d1d8319d66...`
  - `ai_usage_grader_system` : `81cb7fdf89bda55a...`
- **Fournisseur (rubrique) :** `openai`
- **Fournisseur (IA-usage) :** `openai` (gpt-5-mini-2025-08-07)

_Ce feedback a été produit par un pipeline automatisé et **revu par l'équipe pédagogique avant publication**. Aucun chiffre ni étiquette de niveau n'est diffusé à ce stade expérimental : l'objectif est uniquement formatif. Ouvrez une issue dans ce dépôt pour toute question._
