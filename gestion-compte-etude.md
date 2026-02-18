# Gestion de compte étude

Le **compte étude** (ou compte organisation) regroupe les paramètres de l’étude : création du compte, connexion au LRA, connexion Outlook, invitations de collaborateurs, rôles, licences et facturation. Ce chapitre s’adresse en priorité aux administrateurs et aux comptables.

---

## Création de compte

La **création du compte étude** (organisation) s’effectue depuis l’application web Primmo, en général lors de l’onboarding ou par un processus dédié.

- Renseignez les informations de l’étude (nom, type, etc.) et validez la création.
- Une fois le compte créé, vous pouvez configurer la connexion au LRA, Outlook, les invitations et les licences.

Les détails (champs obligatoires, validation) peuvent varier selon votre type de compte et les options souscrites.

---

## Connexion au LRA

Pour **connecter** votre outil de gestion (LRA, iNot, etc.) à Primmo :

1. Accédez aux **paramètres du compte étude** (section administration ou « Connexion LRA »).
2. Renseignez les **paramètres de connexion** (URL, identifiants, périmètre) fournis par Primmo ou votre éditeur de LRA.
3. Testez la connexion puis **enregistrez**.

Une fois la connexion active, les dossiers et documents du LRA peuvent être synchronisés et les options « Verser à iNot » / « Verser au LRA » sont disponibles (voir [Actions rapides liées à un dossier](actions-rapides-dossier.md) et [Gérer vos documents](gerer-documents.md)).

---

## Connexion Outlook

La **connexion Outlook** au niveau compte étude peut désigner la configuration globale (domaine, stratégie) pour que les utilisateurs de l’étude utilisent le complément Outlook avec le même compte Primmo.

- Dans les paramètres du compte étude, vérifiez ou configurez les options liées à **Outlook** (intégration, domaine, déploiement du complément) selon ce qui est proposé.
- Les utilisateurs se connectent ensuite au complément avec leur compte Primmo rattaché à cette étude.

---

## Invitation de collaborateurs

Pour **inviter des collaborateurs** à rejoindre le compte étude :

1. Depuis l’**administration du compte** (section Utilisateurs ou Invitations), cliquez sur **Inviter** (ou « Envoyer une invitation »).
2. Saisissez l’**adresse e-mail** du collaborateur et le **rôle** à lui attribuer (voir ci-dessous).
3. Validez l’envoi : une **invitation** est envoyée par e-mail avec un lien d’acceptation.
4. Le collaborateur clique sur le lien, crée son compte ou se connecte, et **accepte l’invitation** ; il est alors membre du compte étude avec le rôle choisi.

Vous pouvez consulter la liste des invitations (en attente, acceptées, expirées) et annuler une invitation si nécessaire.

---

## Explication des rôles

Les **rôles** définissent les droits des utilisateurs sur le compte étude. En général :

- **Utilisateur** : accès standard aux fonctionnalités (chat, dossiers, documents, e-mails, modèles) sans administration.
- **Administrateur** : gestion des utilisateurs, invitations et paramètres du compte (hors facturation selon la configuration).
- **Super administrateur** : accès complet à toutes les fonctionnalités d’administration du compte.
- **Comptable** : gestion de la facturation et accès au portail de paiement (souscription, factures).

L’attribution des rôles se fait au moment de l’invitation ou depuis la liste des membres (modification du rôle par un admin).

---

## Activation et désactivation de licences

Les **licences** déterminent le nombre d’utilisateurs actifs autorisés sur le compte étude.

- Depuis l’**administration du compte** (section Abonnement, Licences ou Facturation), vous pouvez **activer** ou **désactiver** des licences selon le nombre souscrit.
- **Activer** une licence permet d’attribuer une place à un utilisateur (ou de lui permettre de se connecter).
- **Désactiver** une licence libère une place sans supprimer le compte utilisateur ; l’utilisateur ne pourra plus se connecter tant qu’une licence ne lui est pas à nouveau attribuée.

Le nombre de licences actives ne doit pas dépasser le nombre souscrit dans votre abonnement.

---

## Ajout d’un gestionnaire de facturation

Pour **ajouter un gestionnaire de facturation** (rôle Comptable) :

1. Depuis l’administration du compte, utilisez **Inviter** (ou la gestion des membres).
2. Saisissez l’e-mail du futur gestionnaire et attribuez-lui le rôle **Comptable** (ou « Gestionnaire de facturation » selon le libellé).
3. Envoyez l’invitation ; après acceptation, cette personne aura accès au **portail de facturation** et pourra gérer les moyens de paiement et consulter les factures pour le compte étude.

Vous pouvez avoir plusieurs comptables selon les règles de votre abonnement.
