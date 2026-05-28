# Rétroaction automatisée -- S02 (Sélectionner des solutions IA : décision, opérations, productivité)

_Générée le 2026-05-28T21:24:16+00:00 -- Run `20260528T211725Z-bd460c4e`_

Ce document est produit par un pipeline reproductible (validation automatique du livrable + analyse LLM du brief et de la déclaration IA). Une revue humaine précède toujours sa publication. **À ce stade expérimental, aucune note ni étiquette de niveau n'est diffusée : l'objectif est purement formatif.**

---

## 1. Rétroaction pédagogique sur le brief

> Très bon brief: le contexte PME vs grande entreprise est bien détaillé et la grille justifie clairement la recommandation différenciée. Pour atteindre l'excellence finale, quantifiez davantage les impacts et formalisez des conditions de succès vérifiables.

### Observations par dimension

**Contexte organisationnel**
- Observation : Le brief décrit une PME québécoise de 50 employés (Lumen Logistique inc.) avec budget IA de 25 K$ et une grande coopérative de 800 employés avec budget de 2 M$, en précisant maturité M365, ERP/CRM et contraintes réglementaires (Loi 25, AMF).
- Piste d'amélioration : Ajouter une courte matrice récapitulative comparant explicitement taille, budget, compétences IT et contraintes réglementaires pour chaque contexte.

**Justification criteres**
- Observation : La grille présente pour chaque agent et chaque contexte des justifications chiffrées ou factuelles pour l'impact, la faisabilité, le coût et le risque (ex. coûts estimés, faisabilité liée à M365 ou CRM existant).
- Piste d'amélioration : Insérer une source ou hypothèse chiffrée pour chaque estimation (ex. tarif licence moyen ou hypothèse d'effort d'intégration) pour renforcer la vérifiabilité.

**Role specialise identifie**
- Observation : Chaque agent se voit assigner un rôle métier précis (ex. Brex = « directeur financier que la PME n'a pas », Einstein = « directeur commercial/analyste CRM », Copilot = « adjoint de productivité polyvalent »).
- Piste d'amélioration : Donner un exemple d'une tâche métier concrète par agent (ex. « categorise 95 % des dépenses automatiquement ») pour illustrer la spécialisation.

**Recommandation argumentee**
- Observation : La recommandation différencie clairement les contextes: déployer Copilot puis piloter Brex pour la PME, et prioriser Salesforce Einstein pour la grande entreprise, avec justification par la pondération des critères et prérequis.
- Piste d'amélioration : Ajouter un calendrier de déploiement succinct et les principaux indicateurs à suivre pour appuyer la recommandation devant un comité de direction.

**Role specialise**
- Observation : Le brief indique quel expert humain chaque agent remplace/augmente (p.ex. Brex remplace un CFO absent; Einstein augmente le directeur commercial; Copilot augmente les employés).
- Piste d'amélioration : Préciser l'expertise humaine exacte (poste, niveau seniorité) et l'ampleur du remplacement vs augmentation (FTE équivalent ou % des tâches).

**Probleme affaires**
- Observation : Le problème est formulé pour la PME: absence de CFO, contrôle budgétaire en temps réel manquant et contrôleuse débordée; pour la grande entreprise: nécessité de conformité et optimisation du pipeline CRM.
- Piste d'amélioration : Ajouter un indicateur quantifié du problème principal (ex. nombre de jours de clôture mensuelle, % d'écart budgétaire) pour renforcer l'ancrage exécutif.

**Valeur creee**
- Observation : Le brief mentionne des gains plausibles (gain de conversion 25→35 % cité pour Einstein, réduction de charge financière attendue avec Brex, gains de productivité avec Copilot) mais rarement issus de sources propres au cas.
- Piste d'amélioration : Quantifier l'impact attendu pour Lumen (ex. économies annuelles projetées, heures économisées) et indiquer la source ou l'hypothèse pour chaque chiffre.

**Risque mitigation**
- Observation : Les risques principaux sont nommés (conformité canadienne pour Brex, adoption et données pour Einstein, fuite de renseignements et Loi 25 pour Copilot) avec mitigations concrètes (pilote 30 jours, maintien QuickBooks, audits et politique d'usage).
- Piste d'amélioration : Décrire brièvement qui (poste/responsable) exécutera chaque mitigation et le calendrier d'actions initiales.

**Condition succes**
- Observation : Le document propose des recommandations et mitigations mais n'énonce pas clairement des conditions de succès mesurables (ex. taux d'adoption cible, horizon temporel vérifiable).
- Piste d'amélioration : Formuler 2–3 conditions de succès mesurables par contexte (ex. adoption > 60 % en 6 mois, réduction des écarts budgétaires de 20 % en 12 mois).

**Ai disclosure**
- Observation : La liste de contrôle indique 'ai-usage.md mis à jour à la racine du dépôt ✓', répondant à l'exigence de présence du fichier.
- Piste d'amélioration : Inclure dans ai-usage.md les quatre éléments requis (outil, étape d'utilisation, validation humaine, limites observées) pour atteindre l'excellent.

## 2. Déclaration d'utilisation de l'IA

> La déclaration donne des détails utiles sur l'utilisation et sur les sources vérifiées, mais elle omet la version/modèle de l'outil et ne mentionne pas de limites ou d'erreurs observées. Merci d'ajouter la version/modèle précise de Claude et une section explicite sur les limites ou erreurs constatées.

**Sujets bien couverts dans votre déclaration :**

- à quelle étape l'IA a été utilisée
- comment la sortie a été validée par l'humain

**Sujets à ajouter ou expliciter pour la prochaine itération :**

- outils utilisés (nom + version/modèle)
- limites ou erreurs observées

## 3. Pistes d'action pour la prochaine itération

- Compléter i-usage.md en y ajoutant : outils utilisés (nom + version/modèle).
- Compléter i-usage.md en y ajoutant : limites ou erreurs observées.

---

## 4. Traçabilité

- **Run ID :** `20260528T211725Z-bd460c4e`
- **Devoir :** `S02`
- **Étudiant·e :** `GIGA1102`
- **Commit analysé :** `1de8539`
- **Audit (côté instructeur) :** `tools/instructor/feedback_pipeline/audit/20260528T211725Z-bd460c4e/GIGA1102/`
- **Prompts (SHA-256) :**
  - `rubric_grader_system` : `505f32d1d8319d66...`
  - `ai_usage_grader_system` : `81cb7fdf89bda55a...`
- **Fournisseur (rubrique) :** `openai`
- **Fournisseur (IA-usage) :** `openai` (gpt-5-mini-2025-08-07)

_Ce feedback a été produit par un pipeline automatisé et **revu par l'équipe pédagogique avant publication**. Aucun chiffre ni étiquette de niveau n'est diffusé à ce stade expérimental : l'objectif est uniquement formatif. Ouvrez une issue dans ce dépôt pour toute question._
