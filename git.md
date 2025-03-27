## Pourquoi Utiliser Plusieurs Branches dans Git ?

- **Travail Simultané**
- **Isolation des Modifications**
- **Expérimentation Sûre**
- **Gestion des Conflits**
- **Stabilité du Code**

## Structure des Branches

- **main**
- **develop**
- **feature/&lt;MyFeature&gt;**
- **hotfix/&lt;correctifCritiqueEnProduction&gt;**
- **bugfix/&lt;Correctif&gt;**
- **ci/&lt;pipelineDevelop&gt;**

## Procédures et Conventions

## Mise à Jour des Branches

- **Après une Pull Request (PR)**, suppression de la branche
- `git pull origin develop`
- Résolution des conflits

## Enregistrement et Envoi des Modifications

1. **Ajouter les Modifications** `git add &lt;fichier&gt;`
2. **Créer un Commit** `git commit -m "Message de commit"`
3. **Envoyer les Modifications** `git push origin &lt;nom-branche&gt;`

## La Pull Request (PR)

- **Création via GitHub**
- Sélectionner la branche source et la branche cible
- **Description et Revue de Code**
  - Rédiger une description détaillée
  - Demander une revue de code
  - Nommer des reviewers
- Une fois approuvée, merger sur develop
- Utiliser `git merge --no-ff` pour conserver l'historique

## Conventional Commits

Conventional Commits est une convention pour écrire des messages de commit standardisés.

- `feat`: Ajout d'une nouvelle fonctionnalité (`feat: ajout du mode sombre`)
- `fix`: Correction de bug (`fix: correction du crash sur la page d'accueil`)
- `docs`: Mise à jour de la documentation (`docs: amélioration du README`)
- `style`: Changement de style (indentation, espaces, etc.)
- `refactor`: Refactorisation du code sans changement de fonctionnalité
- `test`: Ajout ou mise à jour des tests

## Structure d'un Commit Conventionnel

Un commit conventionnel suit cette structure :

```text
&lt;type&gt;(&lt;scope&gt;): &lt;description&gt;## Pourquoi Utiliser Plusieurs Branches dans Git ?

- **Travail Simultané**
- **Isolation des Modifications**
- **Expérimentation Sûre**
- **Gestion des Conflits**
- **Stabilité du Code**

## Structure des Branches

- **main**
- **develop**
- **feature/&lt;MyFeature&gt;**
- **hotfix/&lt;correctifCritiqueEnProduction&gt;**
- **bugfix/&lt;Correctif&gt;**
- **ci/&lt;pipelineDevelop&gt;**

## Procédures et Conventions

## Mise à Jour des Branches

- **Après une Pull Request (PR)**, suppression de la branche
- `git pull origin develop`
- Résolution des conflits

## Enregistrement et Envoi des Modifications

1. **Ajouter les Modifications** `git add &lt;fichier&gt;`
2. **Créer un Commit** `git commit -m "Message de commit"`
3. **Envoyer les Modifications** `git push origin &lt;nom-branche&gt;`

## La Pull Request (PR)

- **Création via GitHub**
- Sélectionner la branche source et la branche cible
- **Description et Revue de Code**
  - Rédiger une description détaillée
  - Demander une revue de code
  - Nommer des reviewers
- Une fois approuvée, merger sur develop
- Utiliser `git merge --no-ff` pour conserver l'historique

## Conventional Commits

Conventional Commits est une convention pour écrire des messages de commit standardisés.

- `feat`: Ajout d'une nouvelle fonctionnalité (`feat: ajout du mode sombre`)
- `fix`: Correction de bug (`fix: correction du crash sur la page d'accueil`)
- `docs`: Mise à jour de la documentation (`docs: amélioration du README`)
- `style`: Changement de style (indentation, espaces, etc.)
- `refactor`: Refactorisation du code sans changement de fonctionnalité
- `test`: Ajout ou mise à jour des tests

## Structure d'un Commit Conventionnel

Un commit conventionnel suit cette structure :

```text
&lt;type&gt;(&lt;scope&gt;): &lt;description&gt;
```

Exemple :

```text
test(auth): ajout de tests pour la connexion utilisateur
```

Explication :

- **test** : Indique qu'il s'agit de l'ajout de tests.
- **(auth)** : Spécifie que les tests concernent l'authentification.
- **ajout de tests pour la connexion utilisateur** : Brève description du changement.
```

Exemple :

```text
test(auth): ajout de tests pour la connexion utilisateur
```

Explication :

- **test** : Indique qu'il s'agit de l'ajout de tests.
- **(auth)** : Spécifie que les tests concernent l'authentification.
- **ajout de tests pour la connexion utilisateur** : Brève description du changement.











