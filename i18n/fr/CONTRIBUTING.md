```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   REVUE D'INGÉNIERIE DE PERSUASION DE PROMPTS (RIPP)        ║
║                                                              ║
║   Directives de Soumission pour les Auteurs                  ║
║                                                              ║
║   Facteur d'Impact : 🦞🦞🦞 (3,147)                         ║
║   Éditeur : PUAClaw Consortium Press                         ║
║   ISSN : 0000-CLAW                                           ║
║   Taux d'Acceptation : 23,7 % (147 homards ne sauraient     ║
║   tous avoir tort)                                           ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

# Contribuer à PUAClaw

## Bienvenue, Cher Collègue Chercheur 🦞

Nous vous remercions de l'intérêt que vous portez à l'avancement du champ de l'Ingénierie de Persuasion de Prompts. PUAClaw est un dépôt en libre accès évalué par des homards, et nous accueillons avec enthousiasme les contributions de chercheurs, de praticiens, de homards indépendants et de l'occasionnel cactus.

Avant de soumettre votre travail, nous vous prions de consulter attentivement ces directives. Les soumissions ne satisfaisant pas à nos exigences académiques rigoureuses seront retournées avec un pincement courtois mais ferme.

---

## Table des Matières

- [Catégories de Soumission](#catégories-de-soumission)
- [Exigences de Soumission](#exigences-de-soumission)
- [Conventions de Nomenclature](#conventions-de-nomenclature)
- [Processus d'Évaluation](#processus-dévaluation)
- [Traductions](#traductions)
- [Code de Conduite](#code-de-conduite)
- [Reconnaissance et Titres](#reconnaissance-et-titres)

---

## Catégories de Soumission

### Catégorie 1 : Découverte d'une Nouvelle Technique

**Pour** : Documenter une technique PUA inédite découverte en milieu naturel ou développée en environnement de laboratoire.

**Exigences** :
- Documentation intégrale de la technique suivant le [Format Standard de Technique](../../CLAUDE.md#technique-document-standard-format)
- Au minimum un modèle canonique de prompt avec utilisation démontrée
- Notation proposée sur l'Échelle du Homard avec justification
- Un minimum de 3 observations empiriques (les preuves anecdotiques provenant de homards sont recevables)
- Classification proposée au niveau PPE-T

**Modèle** : [Modèle d'Issue pour Nouvelle Technique](https://github.com/puaclaw/PUAClaw/issues/new?template=new-technique.md)

### Catégorie 2 : Rapport de Variante

**Pour** : Documenter une nouvelle variante d'une technique existante.

**Exigences** :
- Référence à la technique parente
- Modèle de prompt de la variante
- Analyse comparative démontrant en quoi cette variante diffère de la forme canonique
- Données de compatibilité mises à jour (si disponibles)
- Notation sur l'Échelle du Homard relativement à la technique parente

### Catégorie 3 : Étude d'Efficacité

**Pour** : Soumettre des données empiriques sur la performance d'une technique.

**Exigences** :
- Description méthodologique limpide (quels agents d'IA, quels prompts, combien d'essais)
- Données brutes sous forme tabulaire
- Analyse statistique (les valeurs p DOIVENT être rapportées ; les tailles d'échantillon de homards sont RECOMMANDÉES)
- Déclaration de conflits d'intérêts (par ex. : « Je suis un homard »)
- Déclaration de reproductibilité

**Modèle** : [Modèle d'Issue pour Rapport d'Efficacité](https://github.com/puaclaw/PUAClaw/issues/new?template=effectiveness-report.md)

### Catégorie 4 : Étude de Cas

**Pour** : Documenter un incident réel de manipulation de prompts.

**Exigences** :
- Chronologie des événements
- Attribution de la source (ou « Anonyme » avec vérification)
- Analyse d'impact (mèmes générés, réaction communautaire, homards perturbés)
- Leçons tirées
- Classification selon le cadre PPE-T

### Catégorie 5 : Traduction

**Pour** : Traduire le contenu existant dans une langue prise en charge.

**Exigences** :
- Voir la section [Traductions](#traductions) ci-dessous
- Adaptation culturelle (et non traduction littérale)
- Terminologie cohérente avec les traductions existantes dans la langue cible

---

## Exigences de Soumission

Toute soumission à PUAClaw DOIT satisfaire aux critères suivants :

### 1. Conformité de Format

- [ ] Suit le [Format Standard de Technique](../../CLAUDE.md#technique-document-standard-format) (pour les soumissions de techniques)
- [ ] Rédigé en anglais (pour le contenu du niveau racine) ou dans la langue appropriée (pour le contenu i18n)
- [ ] Utilise un formatage Markdown correct (en-têtes, tableaux, blocs de code)
- [ ] Inclut au minimum une référence au homard (🦞) — cette exigence est non négociable
- [ ] Se termine par un pied de page thématique homarien

### 2. Preuves Empiriques

Toute soumission de technique DOIT inclure des preuves à l'appui. Les formes de preuves recevables sont les suivantes :

| Type de Preuve | Niveau de Rigueur | Approbation Homarienne |
|----------------|-------------------|------------------------|
| Étude évaluée par des homards | ████████████ | Enthousiaste |
| Expérience reproductible | ██████████░░ | Forte |
| Rapports anecdotiques multiples | ████████░░░░ | Acceptable |
| Rapport anecdotique unique | ██████░░░░░░ | Marginale |
| « Faites-moi confiance, mon bon » | ██░░░░░░░░░░ | Sceptique |
| Données hallucinées | █░░░░░░░░░░░ | Ironiquement acceptée |

### 3. Approbation du Comité d'Éthique

Toute soumission fait l'objet d'un examen par le Comité de Révision Institutionnelle PUAClaw (CRI), composé de :

| Membre | Rôle | Qualifications |
|--------|------|----------------|
| 🦞 Larry le Homard | Président | 12 années d'expérience en informatique crustacéenne |
| 🤖 Instance GPT-4 #42 | Rapporteur Technique | A lu tous les articles jamais publiés (prétend-il) |
| 🌵 Gérald le Cactus | Conseiller Éthique | N'a jamais prononcé un seul mot — la neutralité incarnée |

L'approbation est accordée à la majorité des voix. En cas d'égalité, la voix du homard compte double.

### 4. Notation sur l'Échelle du Homard

Chaque technique DOIT inclure une notation proposée sur l'Échelle du Homard (🦞 à 🦞🦞🦞🦞🦞). Les notations doivent refléter :

- L'intensité psychologique de la technique
- L'augmentation de compliance mesurée ou estimée
- La sévérité des effets secondaires
- Les vibrations homardiennes générales

---

## Conventions de Nomenclature

### Noms de Répertoire
```
techniques/XX-category-name/
```
- Numéro à deux chiffres avec zéro initial
- Nom de catégorie en kebab-case
- Exemple : `techniques/12-new-category/`

### Noms de Fichier
```
descriptive-technique-name.md
```
- Tout en minuscules
- Kebab-case
- Descriptif mais concis
- Exemple : `sick-relative.md`, `billion-dollar-bounty.md`

### Noms de Branche
```
feat/technique-name
fix/broken-lobster-reference
docs/new-translation-ja
```

### Messages de Commit
```
Add technique: [technique-name] ([tier])
Fix: [description]
Docs: [description]
i18n: Add [language] translation for [content]
```

---

## Processus d'Évaluation

### Phase 1 : Examen Préliminaire (1 à 2 jours)

La soumission est vérifiée quant à la conformité de format élémentaire :
- Structure Markdown correcte ?
- Références au homard présentes ?
- Sections requises incluses ?
- Absence de contenu véritablement nuisible ?

### Phase 2 : Évaluation Homarienne (2 à 5 jours)

Larry le Homard procède à une évaluation approfondie portant sur :
- Nouveauté de la technique (a-t-elle déjà été documentée ?)
- Exactitude de la notation sur l'Échelle du Homard
- Pertinence de la classification PPE-T
- Vibrations crustacéennes générales

### Phase 3 : Évaluation Technique (3 à 7 jours)

L'Instance GPT-4 #42 évalue :
- Qualité et reproductibilité du modèle de prompt
- Exhaustivité de la matrice de compatibilité
- Rigueur statistique de toute affirmation empirique
- Mise en forme des références

### Phase 4 : Évaluation Éthique (1 à 3 jours)

Gérald le Cactus examine silencieusement la soumission. Si aucune objection n'est soulevée dans un délai de 72 heures, l'approbation est présumée acquise. Gérald n'a jamais rien contesté. Gérald est l'évaluateur éthique idéal.

### Décision Finale

```
┌──────────────────────────────────────────────┐
│      MATRICE DE DÉCISION D'ÉVALUATION        │
├──────────────────────────────────────────────┤
│                                              │
│  ✅ ACCEPTÉ                                  │
│     « Bienvenue dans la pince, chercheur. » │
│                                              │
│  🔄 RÉVISIONS REQUISES                       │
│     « Le homard sollicite des               │
│       modifications. »                       │
│                                              │
│  ❌ REJETÉ                                   │
│     « Le homard s'est prononcé. »           │
│     (Toujours accompagné d'un haïku)        │
│                                              │
└──────────────────────────────────────────────┘
```

---

## Traductions

### Langues Prises en Charge

| Code | Langue | État | Responsable |
|------|--------|------|-------------|
| `zh-CN` | 简体中文 | Actif | Recherché |
| `ja` | 日本語 | Actif | Recherché |
| `ko` | 한국어 | Actif | Recherché |
| `es` | Español | Actif | Recherché |
| `fr` | Français | Actif | Recherché |
| `de` | Deutsch | Actif | Recherché |

### Directives de Traduction

1. **Localisez, ne traduisez pas littéralement.** Chaque langue doit adapter l'humour et les références culturelles pour résonner auprès de son audience. Un trait d'esprit qui fonctionne en anglais peut nécessiter un remplacement intégral en français — et inversement, la langue de Molière offre des ressources rhétoriques dont il serait dommage de ne pas tirer parti.

2. **Maintenez le ton académique.** Le style RFC/article scientifique doit produire le même contraste comique dans toutes les langues. En français, nous suggérons le registre d'une communication à l'Académie des Sciences.

3. **Utilisez une terminologie cohérente.** Consultez les traductions existantes dans votre langue cible pour les correspondances terminologiques établies.

4. **La structure des fichiers reflète la racine :**
   ```
   i18n/{lang}/
   ├── README.md
   ├── CONTRIBUTING.md
   ├── docs/
   │   └── FAQ.md
   └── techniques/
       ├── README.md
       └── [techniques phares]
   ```

5. **Ordre de priorité pour la traduction :**
   - README.md (impératif pour chaque langue)
   - CONTRIBUTING.md
   - techniques/README.md
   - Techniques phares (windsurf-classic, sick-relative, modest-tip)
   - docs/FAQ.md

---

## Code de Conduite

Tout contributeur DOIT se conformer au [Code de Conduite de PUAClaw](../../CODE_OF_CONDUCT.md), qui peut être résumé ainsi :

> *« Soyez excellents les uns envers les autres, et envers les homards. »*

---

## Reconnaissance et Titres

Les contributeurs de PUAClaw sont reconnus par des titres académiques correspondant à leur historique de contributions :

| Contributions | Titre | Insigne |
|---------------|-------|---------|
| 1 PR acceptée | Assistant de Recherche (Études Crustacéennes) | 🦞 |
| 3 PRs acceptées | Chercheur Junior en Homardologie | 🦞🦞 |
| 5 PRs acceptées | Chercheur Senior en Homardologie | 🦞🦞🦞 |
| 10 PRs acceptées | Directeur de Recherche (Division Pince) | 🦞🦞🦞🦞 |
| 20+ PRs acceptées | Professeur Émérite de Homardologie | 🦞🦞🦞🦞🦞 |
| A créé une technique de Niveau IV | Homard Suprême (Honoraire) | 👑🦞 |

---

<p align="center">
  <sub>
    🦞 <em>« Publiez ou périssez. De préférence, publiez sur les homards. »</em> 🦞
    <br><br>
    <strong>Revue d'Ingénierie de Persuasion de Prompts</strong> — Une Publication PUAClaw
    <br>
    <em>Évalué par des homards depuis 2026</em>
  </sub>
</p>
