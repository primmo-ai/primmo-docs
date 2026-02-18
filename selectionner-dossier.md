# Sélectionner un dossier

Dans Primmo, un **dossier** correspond à une affaire ou un dossier de travail. Le sélectionner permet d’accéder à son contexte (documents et e-mails), de fournir ce contexte à votre assistant lors de vos demandes, et d’effectuer des actions rapides (collecte, versement des documents et des emails). Ce chapitre explique comment sélectionner un dossier et comprendre l’indicateur de statut.

***

## Bouton « Sélectionner un dossier »

Depuis l’interface du complément (Outlook ou Word) ou de l’application web, un **bouton « Sélectionner un dossier »** (ou libellé proche) ouvre le panneau ou la fenêtre de recherche de dossiers.

* Cliquez sur ce bouton pour afficher la liste de vos dossiers et en choisir un, ou en créer un nouveau si l’option est disponible.
* Si vous êtes connecté à votre LRA, vous pourrez importer votre dossier depuis votre LRA.

Une fois un dossier sélectionné, il reste le dossier « courant » jusqu’à ce que vous le fermiez en cliquant sur la croix ; toutes les demandes que vous ferez à Primmo prendront ce dossier comme contexte.

***

## Rechercher avec le nom du dossier

Dans le panneau de sélection :

* Utilisez le champ **Rechercher** et saisissez tout ou partie du **nom (intitulé) du dossier**.
* Un **dossier Primmo** correspond en général à un **sous-dossier** dans votre LRA (logiciel de rédaction d'actes) lorsque la connexion LRA est active : la recherche peut afficher à la fois les dossiers déjà importés dans Primmo et, si applicable, les sous-dossiers disponibles sur le LRA (iNot).

Les résultats se mettent à jour au fil de la saisie. Sélectionnez le dossier voulu dans la liste.

***

## Sélectionner ou importer

* **Sélectionner** : cliquez sur un dossier dans les résultats pour le choisir comme dossier courant.
* **Importer** : si le dossier n’existe pas encore dans Primmo mais existe dans le LRA, une option **Importer** ou **Nouveau dossier** peut permettre de le créer dans Primmo (ou de l’associer). Suivez les libellés de l’interface pour importer ou créer un dossier.

Une fois le dossier sélectionné (ou importé puis sélectionné), il est utilisé pour le chat, les documents et les actions rapides.

***

## Comprendre l’indicateur de statut

Un **indicateur de statut** peut afficher un compteur du type **`x / y`** à côté du dossier (ou dans la zone documents).

Lisez-le comme : **“documents prêts / documents présents”**.

* **`y`** = nombre de documents **présents** dans le dossier Primmo (importés / versés).
* **`x`** = nombre de documents déjà **traités** par Primmo (analysés / indexés), donc **utilisables** par l’assistant.

### Comment l’interpréter

* **`x = y`** : tout est prêt.
* **`x < y`** : certains documents sont encore en **cours de traitement**.
  * Vous pouvez déjà travailler avec ceux qui sont traités.
  * Attendez que le compteur progresse si vous avez besoin des autres.

### Exemple

* **`3 / 10`** : 10 documents sont dans le dossier.
* 3 documents sont déjà analysés.
* 7 documents sont encore en attente.

{% hint style="info" %}
Le compteur peut évoluer pendant une synchronisation LRA (import en cours). Si le compteur reste bloqué longtemps, fermez puis rouvrez le dossier, ou relancez l’import/versement si l’option existe.
{% endhint %}
