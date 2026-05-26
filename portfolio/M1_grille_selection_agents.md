# M1 — Grille de sélection et évaluation de solutions IA

> Comparez **Brex** (CFO virtuel), **Salesforce Einstein** (aide à la décision commerciale)
> et **Microsoft Copilot 365** (productivité) sur 5 critères, pour **deux contextes** :
> une PME de 50 employés et une grande entreprise de 500+ employés.
> Concluez par une **recommandation argumentée par contexte**.
>
> Exportez en PDF et déposez `M1_grille_selection_agents.pdf` dans ce dossier.
> Mettez à jour `ai-usage.md` à la racine du dépôt (obligatoire, même si « Aucun »).

---

## Contexte 1 — PME de 50 employés

Lumen Logistique inc., PME québécoise de services-conseils en chaîne d'approvisionnement, 50 employés à Sherbrooke, en croissance. Maturité numérique moyenne : Microsoft 365 est déjà déployé mais sous-utilisé, la comptabilité repose sur QuickBooks et une contrôleuse à temps partiel débordée, il n'y a aucun CFO ni aucune visibilité budgétaire en temps réel, et aucun CRM. L'équipe IT se résume à un généraliste, le talent technique étant rare et cher dans la région. Budget IA d'environ 25 K$ par an. Données clients et financières assujetties à la Loi 25. Pondération retenue : la faisabilité prime pour une PME sans équipe technique, suivie du coût puis de l'impact.

| Critère | Brex | Salesforce Einstein | Microsoft Copilot 365 |
|---|---|---|---|
| **1. Rôle spécialisé orchestré** _(nommez le spécialiste que l'agent remplace/augmente)_ | Le directeur financier que la PME n'a pas les moyens d'embaucher : catégorise les dépenses, alerte sur les anomalies, produit une vue budgétaire en temps réel. | Le directeur commercial ou analyste CRM : score les opportunités et priorise les leads. | L'adjoint de productivité polyvalent qui augmente chaque employé : rédige, résume les réunions Teams, analyse des fichiers Excel. |
| **2. Impact d'affaires** _(1-5 + justification en 1 phrase)_ | 5. Adresse directement la douleur dominante de cette PME, l'absence de contrôle financier en pleine croissance. | 2. Sans pipeline ni données CRM, l'agent n'a presque rien à scorer, sa valeur est quasi nulle ici. | 3. Gain transversal réel, mais qui n'attaque pas la contrainte critique de l'entreprise. |
| **3. Faisabilité PME** _(1-5 + données, compétences, intégration)_ | 3. SaaS léger côté IT, mais Brex est conçu pour le marché américain : sa disponibilité et sa conformité bancaire au Canada restent à valider. | 2. Prérequis bloquant, il faut d'abord des données CRM propres et structurées, absentes ici. C'est un projet, pas un abonnement. | 5. Déjà sur M365, activation par licence, un seul généraliste IT suffit, aucune migration de données. |
| **4. Coût estimé** _(ordre de grandeur annuel + TCO si pertinent)_ | Licence faible, coût réel limité au paramétrage et à l'intégration bancaire, de l'ordre de 5 à 10 K$ par an. Tient dans le budget. | Licences Salesforce, module Einstein et implémentation CRM, de l'ordre de 30 à 50 K$ la première année. Dépasse les 25 K$. | Environ 18 à 24 K$ par an pour 50 postes. Tient dans le budget mais en consomme l'essentiel. |
| **5. Risque principal** _(et mitigation concrète)_ | Dépendance à un fournisseur étranger et adéquation canadienne incertaine. Mitigation : pilote de 30 jours sur un sous-ensemble de dépenses, QuickBooks maintenu en parallèle, bascule seulement si la conformité bancaire est confirmée. | Échec d'adoption faute de données. Mitigation : ne pas déployer tant qu'un CRM alimenté n'existe pas. | Fuite de renseignements personnels via les prompts, non-conformité Loi 25. Mitigation : politique d'usage, désactivation de l'entraînement sur les données, formation du personnel. |

### Recommandation pour la PME

Déployer Microsoft Copilot 365 en premier et lancer en parallèle un pilote de validation de Brex au trimestre suivant. Une fois la pondération appliquée, Copilot devance de très peu Brex, et Einstein reste loin derrière faute de données. Le cas classique de la PME sans CFO désignerait Brex, mais ici un prérequis change tout : Microsoft 365 est déjà en place, ce qui porte la faisabilité de Copilot au maximum et plafonne celle de Brex à cause de l'incertitude canadienne. Comme la faisabilité est le critère qui pèse le plus pour une PME sans équipe technique, le verdict bascule vers l'outil déjà intégré et sans risque de migration, sans pour autant rejeter le besoin financier réel auquel Brex pourra répondre une fois sa conformité confirmée.

---

## Contexte 2 — Grande entreprise de 500+ employés

Coopérative de services financiers du Québec, 800 employés, secteur réglementé par l'AMF. Un ERP financier mature et un CRM Salesforce déjà alimenté par 120 conseillers sont en place. Gouvernance lourde à six niveaux d'approbation avec comité de risque, sponsor exécutif au poste de VP Opérations, budget IA d'environ 2 M$ donc non contraignant mais soumis à la conformité. La Loi 25 et le secret financier dominent. Une direction financière complète, CFO et équipe, existe déjà. Pondération retenue : le budget cesse de limiter, et la conformité réglementaire devient le critère qui peut tout dominer, à parité avec l'impact.

| Critère | Brex | Salesforce Einstein | Microsoft Copilot 365 |
|---|---|---|---|
| **1. Rôle spécialisé orchestré** | CFO virtuel, mais le rôle est déjà tenu par une direction financière humaine et un ERP. | Le directeur commercial augmenté : prédit la probabilité de conversion et priorise les opportunités des 120 conseillers sur le CRM existant. | L'adjoint de productivité pour 800 employés du savoir. |
| **2. Impact d'affaires** _(1-5 + justification)_ | 2. Redondant avec le CFO et l'ERP en place, gain marginal. | 5. Branché sur un CRM déjà alimenté, le lift de conversion de 25 à 35 % rapporté par le cours s'applique à un volume commercial élevé. | 3. Gain de productivité réel mais non différenciant, tous les concurrents l'auront. |
| **3. Faisabilité grande entreprise** _(1-5 + intégration systèmes, gouvernance)_ | 2. Devrait s'insérer dans un ERP complexe déjà optimisé, avec un faible appétit de remplacement. | 5. Infrastructure CRM, données propres et compétences déjà présentes, activation d'un module sur une plateforme maîtrisée. | 3. Simple sur M365, mais la revue de conformité AMF et Loi 25 avant d'autoriser l'IA générative sur des données clients est longue. |
| **4. Coût estimé** _(licences + intégration + formation)_ | Licence faible mais rendement négatif vu la redondance. | Licences à l'échelle de 120 conseillers et gouvernance des modèles, élevé en absolu mais absorbé par 2 M$. | De l'ordre de 300 à 380 K$ par an pour 800 postes plus la mise en conformité. Tient dans le budget. |
| **5. Risque principal** _(et mitigation)_ | Investissement à faible rendement qui double des outils existants. Mitigation : ne pas déployer. | Biais ou dérive des modèles sur la priorisation des leads, sous surveillance du régulateur. Mitigation : supervision humaine obligatoire, audit périodique des modèles, traçabilité de chaque recommandation. | Non-conformité Loi 25 et AMF sur des données financières sensibles, difficile à contenir à 800 postes. Mitigation : déploiement cloisonné, exclusion des données sensibles, responsable de la protection des renseignements personnels impliqué dès le départ. |

### Recommandation pour la grande entreprise

Déployer Salesforce Einstein en premier. Une fois la pondération appliquée, il devance nettement Copilot et Brex. Le choix diffère radicalement de celui de la PME pour une seule raison de fond : le prérequis qui bloquait Einstein à la PME, l'absence de CRM et de données, est ici déjà résolu. Le même agent passe d'une faisabilité faible à maximale et devient le plus fort sur le critère qui pèse le plus, l'impact appliqué à un volume commercial élevé. Le compromis est assumé : Einstein porte un risque réglementaire réel, d'où la mitigation par supervision humaine et audit des modèles, sans laquelle l'AMF ne tolérerait pas le déploiement. Copilot reste un bon second projet mais non différenciant, et Brex est écarté car il double une direction financière déjà en place.

---

## Synthèse — ce que la grille révèle

Le critère qui fait basculer la décision n'est ni l'impact ni le coût pris isolément, c'est la faisabilité, soit l'adéquation entre l'agent et les prérequis déjà présents dans l'organisation. La preuve tient en un constat : Einstein, exactement le même agent, est exclu à la PME et recommandé en premier à la grande entreprise, uniquement parce que le CRM et les données existent dans un cas et pas dans l'autre. C'est la leçon centrale de la séance, il n'y a pas de meilleur agent en absolu, seulement un meilleur agent pour un contexte et des contraintes donnés, et la pondération elle-même doit suivre ce contexte. Au Québec, la Loi 25 impose une revue de conformité avant d'exposer des données clients à une IA générative, et la dépendance à un fournisseur étranger comme Brex doit être validée plutôt que présumée. La règle à retenir pour l'Examen-cas 1 est qu'une recommandation IA crédible part toujours du contexte et des prérequis, jamais de la puissance technique de l'outil.

---

## Liste de contrôle de remise

- [x] Les 3 agents sont comparés sur les mêmes 5 critères dans les deux contextes
- [x] Le rôle spécialisé orchestré est nommé précisément pour chaque agent
- [x] Les scores sont justifiés (pas juste des chiffres)
- [x] La recommandation diffère — ou est explicitement justifiée comme identique — entre PME et grande entreprise
- [x] Le contexte d'une organisation québécoise est pris en compte (Loi 25, marché local, talent)
- [x] `ai-usage.md` mis à jour à la racine du dépôt

> **Crédit :** Jalon M1 — pass/fail (1,5 % du cours). Préparation directe à l'**Examen-cas 1** (S05, 25 %).
