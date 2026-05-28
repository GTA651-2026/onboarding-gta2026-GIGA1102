# Rétroaction automatisée -- S01 (L'IA générative et l'ère agentique : orchestrer des experts sans en être un)

_Générée le 2026-05-28T18:08:03+00:00 -- Run `20260528T180023Z-d01c8d01`_

Ce document est produit par un pipeline reproductible (vérification SQL déterministe + analyse LLM du brief et de la déclaration IA). Une revue humaine précède toujours sa publication. **À ce stade expérimental, aucune note ni étiquette de niveau n'est diffusée : l'objectif est purement formatif.**

---

## 1. Vérification automatique de la requête SQL

La vérification automatique n'a pas pu être réalisée (gate non applicable (type=text_artifact, must_run=False)).


## 2. Rétroaction pédagogique sur le brief

> Le brief identifie clairement le problème d'échelle de Klarna et donne des chiffres convaincants sur la valeur créée par l'agent. En revanche il manque un contexte organisationnel différencié, une grille justificative des critères, une recommandation argumentée et un ai-usage.md détaillé.

### Observations par dimension

**Contexte organisationnel**
- Observation : Le brief indique seulement «Le cas choisi est Klarna» sans taille, budget ou différenciation PME vs grande entreprise.
- Piste d'amélioration : Ajoutez des détails sur la taille, le secteur et le budget, et explicitez la recommandation distincte pour une PME et pour une grande entreprise.

**Justification criteres**
- Observation : Aucune grille avec impact, faisabilité, risque et coût pour les agents n'est fournie dans le document.
- Piste d'amélioration : Fournissez une grille 3×4 (trois agents × quatre critères) avec justifications factuelles ou hypothèses vérifiables pour chaque cellule.

**Role specialise identifie**
- Observation : Vous écrivez «L'agent a comme rôle orchestré d'être un spécialiste en service client», ce qui nomme un rôle métier.
- Piste d'amélioration : Précisez une tâche métier concrète (ex. : résolution de réclamations de niveau 1) et illustrez par un exemple opérationnel.

**Recommandation argumentee**
- Observation : Le document ne contient pas de recommandation finale ni d'analyse des compromis entre options.
- Piste d'amélioration : Formulez une recommandation claire par contexte et expliquez pourquoi les autres options ont été écartées, en mettant en avant risques et gains.

**Role specialise**
- Observation : Le rôle est décrit comme «spécialiste en service client» mais il n'est pas indiqué quel expert humain est remplacé ou augmenté.
- Piste d'amélioration : Indiquez précisément l'expert humain (ex. : agent support niveau 1) remplacé/augmenté et expliquez pourquoi ce rôle est stratégique pour Klarna.

**Probleme affaires**
- Observation : Le problème est formulé : «gestion de millions de conversations à l'échelle mondiale», en langage exécutif et spécifique au cas.
- Piste d'amélioration : Ajoutez un ancrage chiffré précis (ex. : volume annuel de conversations, coût actuel du support) pour renforcer l'urgence exécutive.

**Valeur creee**
- Observation : Vous quantifiez la valeur: l'agent gère en moyenne 2/3 des discussions (~700 agents), disponible en 35+ langues, et réduit la durée d'une interaction de 11 à ~2 minutes.
- Piste d'amélioration : Citez la source publique de ces chiffres et traduisez-les en impacts financiers ou opérationnels (économies en coût de personnel, amélioration du NPS).

**Risque mitigation**
- Observation : Les risques listés incluent déséquilibre humain/IA, sécurité des données et exactitude ; mitigation proposée: «paramétrage dynamique» et contrôles sur les données et contraintes du modèle.
- Piste d'amélioration : Proposez des mesures concrètes et actionnables (ex. : audits trimestriels, politiques d'accès aux données, tests de qualité de réponses, SLAs fournisseurs).

**Condition succes**
- Observation : Vous mentionnez un plan de mise en place, expertise des spécialistes, formation et mesure de la performance du modèle pour protéger la marque.
- Piste d'amélioration : Formulez une condition mesurable et temporelle (ex. : adoption >80% par les agents internes et réduction des temps de traitement de 50 % en 6 mois).

**Ai disclosure**
- Observation : Le brief contient seulement un rappel «mettez a jour ai-usage.md» sans fournir le contenu du fichier ni indiquer les outils utilisés.
- Piste d'amélioration : Incluez un ai-usage.md indiquant les outils employés (ou «aucun»), l'étape d'utilisation, la validation humaine et les limites observées.

_Quelques points appellent une attention particulière lors de la prochaine itération : ai_usage_missing._

## 3. Déclaration d'utilisation de l'IA

> La déclaration nomme l'outil utilisé et décrit précisément comment il a été employé et validé par l'humain. Il manque une version/modèle explicite de l'outil et aucune limite ou erreur observée n'est clairement documentée.

**Sujets bien couverts dans votre déclaration :**

- à quelle étape l'IA a été utilisée
- comment la sortie a été validée par l'humain

**Sujets à ajouter ou expliciter pour la prochaine itération :**

- outils utilisés (nom + version/modèle)
- limites ou erreurs observées

## 4. Pistes d'action pour la prochaine itération

- Réviser le brief en tenant compte des observations par dimension de la section 2.
- Compléter `ai-usage.md` en y ajoutant : outils utilisés (nom + version/modèle).
- Compléter `ai-usage.md` en y ajoutant : limites ou erreurs observées.

---

## 5. Traçabilité

- **Run ID :** `20260528T180023Z-d01c8d01`
- **Devoir :** `S01`
- **Étudiant·e :** `GIGA1102`
- **Commit analysé :** `5d43b62`
- **Audit (côté instructeur) :** `tools/instructor/feedback_pipeline/audit/20260528T180023Z-d01c8d01/GIGA1102/`
- **Prompts (SHA-256) :**
  - `rubric_grader_system` : `505f32d1d8319d66...`
  - `ai_usage_grader_system` : `81cb7fdf89bda55a...`
- **Fournisseur (rubrique) :** `openai`
- **Fournisseur (IA-usage) :** `openai` (gpt-5-mini-2025-08-07)

_Ce feedback a été produit par un pipeline automatisé et **revu par l'équipe pédagogique avant publication**. Aucun chiffre ni étiquette de niveau n'est diffusé à ce stade expérimental : l'objectif est uniquement formatif. Ouvrez une issue dans ce dépôt pour toute question._
