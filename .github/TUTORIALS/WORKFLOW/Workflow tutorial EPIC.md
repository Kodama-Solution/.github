# Workflow tutorial

Un flux de travail standardisé est essentiel pour assurer la bonne progression de notre projet. Ce tutoriel explique comment utiliser GitHub pour planifier nos sprints à l'aide des EPICs et des tâches.

## EPIC

Un EPIC représente un « Sprint » ou un grand bloc de travail (de 1 à 4 semaines) qui regroupe plusieurs tâches plus petites. C'est notre outil principal pour définir les objectifs globaux d'une période donnée.

### Créer un EPIC

Pour créer un nouvel EPIC :

1. Va dans l'onglet **Issues** du répertoire (repository).
2. Clique sur le bouton vert **New issue**.
3. Dans la liste des templates, choisis **Template: 🗓️ Epic** en cliquant sur *New Issue*.

<img width="1664" height="822" alt="image" src="https://github.com/user-attachments/assets/ad5b51c9-2a16-46ba-b8a9-bad2801603e9" />


### Remplir un EPIC

L'EPIC doit fournir une vue d'ensemble claire de ce qui sera accompli. Voici comment remplir les différentes sections en utilisant notre exemple de référence :

> **[Lien vers l'Issue #39 (L'EPIC d'exemple)](https://github.com/Kodama-Solution/Kodama-Solution-Planning/issues/39)**

* **Titre :** Utilise la nomenclature `[EPIC] - sprint 0XX Name`. Exemple : `[EPIC] - sprint 007 Example`.
* **Sprint Metadata :** * *Sprint ID :* Numéro du sprint (ex: 007).
* *Time dedicated :* Durée prévue (ex: 1 week).
* *Objective :* Une phrase résumant le but (ex: *Créer un Sprint complet de une semaine avec des tâches comme exemple pour l'équipe.*).


* **Scope & Boundaries :** C'est ici qu'on définit les limites pour éviter que le travail ne s'étende trop.
* *In-Scope :* Ce qu'on fait (ex: Modifier les templates, Faire un exemple complet).
* *Out-of-Scope :* Ce qu'on ne fait expressément pas (ex: Développement technique, Créer plus de templates).


* **Expected Deliverables :** La liste des éléments concrets à livrer. Ajoute toujours une estimation de temps (1 semaine = 6 à 12h de travail par personne impliquée).
* **Dependencies & Blockers :** Ce qui doit être fait avant de commencer, ou ce qui bloque l'avancement.
* **Definition of Done (DoD) :** Les critères stricts qui prouvent que le Sprint est un succès (ex: *Le tutoriel est complet, le tout est présenté à l'équipe*).

<img width="1104" height="1233" alt="image" src="https://github.com/user-attachments/assets/488741c5-6923-400a-b07a-7a737b019ed1" />


#### Attention!!!

* **Ne sous-estime pas le temps :** Garde en tête qu'une semaine représente environ 6 à 12h de travail réel par personne 100% dédiée au sprint. Ne surcharge pas les livrables.
* **Reste strict sur le "Out-of-Scope" :** Si une idée n'est pas dans le *In-Scope*, elle doit être documentée pour un futur Sprint, mais ne doit pas être commencée maintenant (Scope creep).
* **Pas oublier de remplir le tableau de droite :** Ajoutez les informations minimal dans la section `Projects` "Planification Global" afin que le tout s'affiche bien. Notamment, la date de début, date de fin et le sprint actuel.

<img width="557" height="1206" alt="image" src="https://github.com/user-attachments/assets/3466cde9-e34a-4b83-af73-812c736eb94f" />

#### Validation avec Aimée ou Jacob

* Assigne **Jabooby** (Jacob) et/ou **stewarteaimee** (Aimée) à l'issue pour qu'ils puissent réviser le *Scope* et le *Definition of Done*.
* Ils laisseront eur approbation (un commentaire ou un *thumbs up* 👍).
* Au besoin, ils vous donneront du feedback et des changement à faire.

### Comment ajouter une tâche

L'EPIC agit comme un parent pour les tâches individuelles (Logiciel, Mécanique, Électrique, Gestion).

1. Ne fais pas le travail directement dans l'EPIC.
2. Crée des nouvelles issues pour chaque tâche technique ou de gestion.
3. Lie ces tâches à l'EPIC en utilisant la fonction de suivi (*Tracked by* / *Tasklist* de GitHub) pour que l'on puisse voir la barre de progression avancer.
4. Ou bien, vous pouvez créez un "sub-issue" directemetn à partir de l'EPIC

<img width="396" height="1033" alt="image" src="https://github.com/user-attachments/assets/634ca351-3bd5-40f5-958a-31cda94303de" />
<img width="1452" height="580" alt="image" src="https://github.com/user-attachments/assets/3f25d88f-3060-482a-b04b-7115f59f2763" />

### À faire à la fin!

Un EPIC n'est jamais simplement "fermé" sans réflexion. À la fin du temps alloué (ex: à la fin de la semaine 007), tu dois remplir la section **To complete at the end** située au bas du template :

1. **Resume of what has been accomplished :** Fais un résumé rapide. Est-ce que tous les points du *Definition of Done* ont été cochés ?
2. **Retrospective :** Remplis honnêtement les trois questions :
* *What went well?* (Les bons coups)
* *What didn't go well?* (Les blocages ou retards)
* *What should we change?* (Actions pour le prochain Sprint)


3. Une fois cette section remplie, tu peux cliquer sur **Close issue**.

> **[ 🖼️ INSÉRER CAPTURE D'ÉCRAN : La section "To complete at the end" remplie avec un exemple de rétrospective ]**

---

## Tâche

Si l'EPIC est le grand objectif de la semaine, les tâches sont les actions concrètes et individuelles qui permettent de l'atteindre. Chaque tâche doit être assignée à une personne (ou un petit groupe) et doit être claire.

### Créer une tâche

Pour créer une nouvelle tâche :

1. Va dans l'onglet **Issues** du répertoire.
2. Clique sur le bouton vert **New issue**.
3. Choisis le template qui correspond à ton département ou au type de travail à faire :
* ⚙️ **Mécanique & Hardware** (CAO, fabrication, assemblage)
* ⚡ **Électrique & PLC** (Câblage, PCBs, sécurité)
* 💻 **Logiciel & IA** (Création de feature, tests unitaires)
* 👔 **Gestion & Direction** (Livrables, budget, organisation)
* Vous pouvez aussi créer vos propres template à vous! Juste me le dire pour que je vous montre comment faire.


4. Clique sur *Create* sur le template approprié.

<img width="953" height="882" alt="image" src="https://github.com/user-attachments/assets/7cb5bd24-a8b6-44ac-95d1-61adeba996e8" />

### Remplir une tâche

Chaque template a ses particularités, mais la structure de base reste la même pour tout le monde. Voici comment bien la remplir :

* **Titre :** Respecte la nomenclature du template `[Domaine] [Nom de l'EPIC] - Titre de la tâche`.
* *Exemple :* `[Mécanique] [sprint 007 Example] - Modélisation de la buse de succion`


* **Contexte & Objectif (Why?) :** Explique pourquoi tu fais cette tâche. Qu'est-ce que ça apporte au système ? (Ex: *La buse actuelle est trop lourde pour le robot, il faut l'alléger.*)
* **Détails Techniques / Spécifications :** Mets les liens vers tes fichiers de travail (Lien KiCad, lien vers le document CAO, nom du nœud ROS, etc.).
* **Definition of Done (DoD) :** C'est la section la plus importante. Coche les cases génériques qui s'appliquent à ta tâche, efface celles qui ne servent à rien, et ajoute tes propres critères de succès.
* **Dépendances / Bloqueurs :** Si tu as besoin que l'équipe Électrique finisse de souder un connecteur avant de pouvoir tester ton code, écris-le ici et mentionne le numéro de leur issue (ex: `Dépend de l'issue #42`).

<img width="1097" height="1146" alt="image" src="https://github.com/user-attachments/assets/258112e6-1437-4046-856a-e38cf76c221a" />


**N'oublie pas de lier la tâche!**
Assure-toi que ta tâche est bien connectée à l'EPIC parent (dans le menu de droite sous *Tracked by* ou *Projects*) pour que la barre de progression de l'EPIC se mette à jour automatiquement.

### Ajouter des commentaires

GitHub n'est pas juste une liste de choses à faire, c'est notre outil de communication technique! Pendant que tu travailles sur ta tâche :

* **Montre ton avancement :** Glisse des captures d'écran de ton modèle 3D, de ton schéma électrique ou une photo de la pièce fabriquée directement dans les commentaires.
* **Pose des questions :** Si tu es bloqué, tag un membre de l'équipe avec `@nom_utilisateur` pour lui demander de l'aide ou une révision de code.
* **Documente les changements :** Si tu as dû changer de plan en cours de route (ex: *On a manqué de vis M4, j'ai adapté le design pour des M3*), écris-le dans les commentaires. Ça servira de documentation pour le futur.

<img width="1097" height="1146" alt="image" src="https://github.com/user-attachments/assets/681fca19-072e-45e0-bab6-c0d97edbb443" />


### Fermer une tâche

Une tâche n'est pas terminée juste parce que tu as fini de travailler dessus. Avant de cliquer sur **Close issue** :

1. Vérifie que **TOUTES** les cases de ton *Definition of Done* sont cochées ou bien transféré à une autre tâches. Sinon, juste mettre en commentaire si non-important.
2. Assure-toi que ton travail est sauvegardé au bon endroit (Code poussé sur GitHub, CAO validée, document déposé sur le Drive/Sharepoint).
3. Laisse un dernier petit commentaire avec le résultat final (ex: *Test concluant, le convoyeur tourne bien à la bonne vitesse*).
4. Clique sur **Close issue** (ou laisse ton *Pull Request* fermer l'issue automatiquement si tu es en Logiciel).

<img width="1048" height="545" alt="image" src="https://github.com/user-attachments/assets/d3e4bb19-bb55-404c-9289-1f259f196dc7" />

---

## BONUS : Mini-guide Markdown

GitHub utilise le langage **Markdown** pour formater le texte dans les Issues, les Pull Requests et les commentaires. C'est très simple à utiliser et ça permet de garder nos documents propres et professionnels.

Voici les bases que vous allez utiliser 95 % du temps :

### 1. Titres et Sous-titres

Utilise le symbole dièse `#` pour créer des titres. Plus il y a de `#`, plus le titre est petit.

```markdown
# Titre principal (H1)
## Sous-titre (H2)
### Petit sous-titre (H3)

```

### 2. Mettre en valeur le texte

```markdown
**Texte en gras**
*Texte en italique*
~~Texte barré~~

```

### 3. Listes et Checklists (Le plus important!)

Les checklists sont essentielles pour nos *Definition of Done (DoD)*.

```markdown
Liste à puces :
- Point 1
- Point 2
  - Sous-point (avec une indentation)

Checklist :
- [x] Tâche complétée
- [ ] Tâche à faire

Liste numérotée :
1. Étape 1
2. Étape 2

```

### 4. Insérer du Code (Surtout pour l'équipe Logiciel)

Pour du code intégré dans une phrase, utilise un seul accent grave (backtick) : `code`.
Pour un gros bloc de code, utilise trois backticks avec le nom du langage :
```python

import numpy as np

# 1. Create a 1D array from a list
arr_1d = np.array([1, 2, 3, 4, 5])

# 2. Create a 2D array (Matrix)
arr_2d = np.array([[1, 2, 3], [4, 5, 6]])

# 3. Quick array initialization
zeros = np.zeros((2, 3))    # 2x3 array of 0s
ones = np.ones(5)           # 1x5 array of 1s
range_arr = np.arange(0, 10, 2)  # [0, 2, 4, 6, 8]

# 4. Basic Math (Element-wise)
# Unlike Python lists, operations apply to every element at once
doubled = arr_1d * 2        # [2, 4, 6, 8, 10]
squared = arr_1d ** 2       # [1, 4, 9, 16, 25]

# 5. Array Attributes
print(f"Shape: {arr_2d.shape}")    # (2, 3)
print(f"Dimensions: {arr_2d.ndim}") # 2
print(f"Data Type: {arr_1d.dtype}") # int64 (usually)

# 6. Aggregation
print(f"Sum: {arr_1d.sum()}")      # 15
print(f"Mean: {arr_1d.mean()}")    # 3.0

```

### 5. Liens et Images

```markdown
Lien cliquable :
[Texte du lien cliquable](https://www.google.ca)

Image (ajoute un point d'exclamation devant) :
![Description de l'image](URL_de_l_image)

```

*Astuce GitHub :* Tu n'as pas besoin de coder tes images à la main! Tu peux simplement faire un copier-coller (Ctrl+V) de ta capture d'écran directement dans la boîte de texte de ton Issue, et GitHub va générer le code Markdown automatiquement!

### 🔗 Outils et Références utiles

Si tu veux te pratiquer ou voir le résultat en temps réel avant de publier sur GitHub, ou si tu cherches à faire des choses plus complexes (comme des tableaux de BOM), voici de bonnes ressources :

* **Éditeur Markdown en ligne (temps réel) :** [Dillinger.io](https://dillinger.io/) ou [StackEdit.io](https://stackedit.io/)
* **Documentation officielle GitHub :** [Guide complet de formatage sur GitHub (Cheatsheet)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* L'onglet **Preview** : Sur GitHub, quand tu écris une Issue ou un commentaire, clique toujours sur l'onglet *Preview* juste en haut de la boîte de texte pour vérifier que ton formatage est beau avant de sauvegarder!
