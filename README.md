# Dossier familial

Un dispositif pour que mon épouse et mes enfants sachent quoi faire et où trouver chaque information si je décède, si je suis dans l'incapacité d'agir (maladie, accident) ou si je suis absent longtemps.

Il repose sur deux éléments :

1. **`index.html`** : une application à ouvrir dans un navigateur, **sans Internet ni installation**. On y remplit le dossier ; la famille le consulte et coche les étapes. Tout est chiffré (AES‑256) avec une phrase secrète.
2. **Ce guide** : comment organiser le dispositif autour de l'application, c'est-à-dire qui détient quoi, les actes juridiques à préparer de mon vivant et le rythme des mises à jour.

> Le contenu juridique suit le **droit marocain** (Code de la famille – Moudawana, loi 37‑99 sur l'état civil, loi 16‑98 sur le don d'organes). Il sert à s'orienter et **ne remplace pas l'avis d'un adoul, d'un notaire ou d'un avocat**, surtout si la famille vit hors du Maroc ou a plusieurs nationalités.

---

## 1. L'architecture : trois niveaux

| Niveau | Quoi | Où | Qui y a accès |
|---|---|---|---|
| **1. Fiche réflexe** | Une page : les 3 à 5 personnes à appeler et l'endroit où se trouve le dossier | Imprimée dans un endroit connu de la famille (classeur « Papiers », porte du coffre) | Toute la famille |
| **2. Dossier complet** | L'application remplie : contacts, comptes, biens, protocoles, volontés, messages | Fichier chiffré `.json` (2 clés USB + 1 copie en ligne) **et** une version papier imprimée sous enveloppe scellée au coffre | Mon épouse, puis les enfants majeurs |
| **3. Actes juridiques** | Testament (wasiya), désignation d'un tuteur, actes de donation, procurations, contrats d'assurance | Chez l'adoul / le notaire, originaux au coffre | Adoul / notaire, puis les héritiers |

**La phrase secrète** est conservée **séparément** du fichier chiffré : une enveloppe scellée remise à mon épouse, et une seconde copie chez le notaire ou chez une personne de confiance. Si la phrase est perdue, le dossier est illisible ; c'est pourquoi la version papier au coffre sert de secours.

## 2. Qui sait quoi

| Personne | Ce qu'elle doit savoir dès maintenant |
|---|---|
| **Mon épouse** | Que le dossier existe, où sont les copies, où est la phrase secrète, comment ouvrir l'application. Elle a déjà l'accès d'urgence au gestionnaire de mots de passe. Elle est cotitulaire d'un compte pour les dépenses courantes. |
| **Enfants majeurs** | Que le dossier existe et qui appeler en premier (fiche réflexe). |
| **Enfants mineurs** | Selon leur âge : un numéro à appeler et le nom d'un adulte de confiance. |
| **Personne de confiance** (frère, sœur, ami proche) | Qu'elle figure dans les contacts prioritaires. Elle a éventuellement une copie de la phrase secrète. |
| **Adoul / notaire** | Ils détiennent le testament et les actes. Ils savent qu'un dossier familial existe. |

## 3. Démarches à faire de mon vivant (droit marocain)

À cocher au fur et à mesure. Ce sont elles qui protègent vraiment la famille ; le dossier ne fait que les rendre visibles.

### Succession
- [ ] **Comprendre la répartition légale.** Au Maroc, les parts des héritiers sont fixées par la loi (Moudawana, livre VI). Par exemple, l'épouse reçoit 1/8 s'il y a des enfants, et un fils reçoit le double d'une fille. Demander à un notaire ou un adoul de **simuler la répartition** pour ma situation.
- [ ] **Vérifier le cas des filles.** S'il n'y a que des filles, une partie de la succession peut revenir à d'autres parents de sexe masculin (frères, oncles, neveux…). En parler avec un notaire **avant** qu'il ne soit trop tard : donations de mon vivant, assurance décès, choix de propriété.
- [ ] **Testament (wasiya)**, par acte d'adoul ou de notaire. Il est limité à **1/3** de la succession et ne peut pas bénéficier à un héritier sans l'accord des autres héritiers (art. 280). Il peut servir à désigner un tuteur, à prévoir un « tanzil » pour les petits-enfants dont le parent est décédé (art. 315 et suivants) ou à faire des legs à des proches non héritiers ou à des œuvres.
- [ ] **Donations (hiba) de mon vivant**, si je veux transmettre un bien précis à quelqu'un. La donation n'est parfaite que si le bénéficiaire prend effectivement possession du bien : se faire conseiller.
- [ ] **Biens du couple** : l'acte séparé sur la gestion des biens acquis pendant le mariage (art. 49) existe-t-il ? Sinon, réfléchir à documenter ce que chacun a apporté.
- [ ] **Titres fonciers à jour** à la conservation foncière (ANCFCC) ; immatriculer si possible les biens qui ne le sont pas.
- [ ] **Situations particulières** : famille vivant à l'étranger, double nationalité, biens dans plusieurs pays, conjoint d'une autre religion (pas d'héritage entre musulman et non‑musulman, art. 332). Dans ces cas, consultation **obligatoire** d'un professionnel.

### Protection de la famille
- [ ] **Assurance décès** avec des bénéficiaires nommément désignés. C'est le moyen le plus rapide de mettre de l'argent à disposition de la famille ; vérifier la clause bénéficiaire à chaque événement (naissance, mariage…).
- [ ] **Assurance emprunteur** sur chaque crédit : vérifier la couverture décès **et** invalidité.
- [ ] **Compte joint** ou compte au nom de mon épouse avec de quoi tenir **3 à 6 mois** : les comptes à mon seul nom seront bloqués.
- [ ] **Assistance rapatriement** si nous vivons ou voyageons hors du Maroc.
- [ ] **Tuteur testamentaire (wassi)** pour les enfants mineurs, en cas de disparition des deux parents : désigné par acte d'adoul ou de notaire.

### Incapacité
- [ ] Rédiger mes **souhaits médicaux** (section Santé) et en parler à mon épouse et à mon médecin. Le droit marocain ne leur donne pas de force obligatoire, mais ils guident les décisions.
- [ ] **Procurations (wakala)** générale ou bancaire pour mon épouse, devant notaire ou adoul. Attention : une procuration prend fin au décès et peut être contestée si je perds la raison. Au-delà, il faudra une décision du tribunal (désignation d'un mouqaddem).
- [ ] **Don d'organes** : déclarer ma volonté au tribunal de première instance (loi 16‑98).

### Numérique
- [ ] Un **gestionnaire de mots de passe** avec **accès d'urgence** pour mon épouse (Bitwarden, 1Password, Proton Pass…).
- [ ] **Google** : « Gestionnaire de compte inactif » (myaccount.google.com → Données et confidentialité).
- [ ] **Apple** : « Contact légataire » (Réglages → Identifiant Apple → Connexion et sécurité).
- [ ] **Facebook / Instagram** : « Contact légataire » ou demande de compte commémoratif.
- [ ] **Code du téléphone** et **PIN de la SIM** accessibles à mon épouse : la banque en ligne passe souvent par SMS.
- [ ] **Cryptomonnaies** : phrase de récupération rangée au coffre, avec une explication pour s'en servir.

## 4. Utiliser l'application

1. **Ouvrir `index.html`** en double-cliquant (Chrome, Edge, Firefox ou Safari récent). Aucune connexion Internet n'est nécessaire.
2. **Créer le dossier** avec une phrase secrète de 4 à 5 mots au hasard.
3. **Remplir** (bouton « Remplir ») : l'enregistrement est automatique et chiffré, dans ce navigateur et sur cet ordinateur.
4. **Sauvegarder** : le bouton télécharge un fichier `dossier-familial-AAAA-MM-JJ.json` **chiffré**. Copier ce fichier **et `index.html`** sur deux clés USB et dans un stockage en ligne.
5. **Imprimer** : en mode « Consulter », le bouton produit une version papier (ou un PDF) avec la fiche réflexe, les trois protocoles et toutes les informations renseignées. **Cette version n'est pas chiffrée** : elle va sous enveloppe scellée, au coffre.
6. **Pour la famille** : ouvrir `index.html` sur n'importe quel ordinateur → « Ouvrir un fichier de sauvegarde » → choisir le `.json` → saisir la phrase secrète.

**Sécurité, ce qu'il faut savoir**
- Le fichier `.json` peut être stocké en ligne sans risque tant que la phrase secrète reste forte et rangée séparément (chiffrement AES‑256‑GCM, clé dérivée par PBKDF2 avec 600 000 itérations).
- Sur l'ordinateur où vous remplissez le dossier, toute personne qui connaît la phrase peut le lire : cliquez sur « Verrouiller » en partant.
- Ne mettez **pas** ce dossier rempli dans un dépôt Git ni sur une page web. Ce dépôt ne contient que l'outil vide.
- Quand vous changez la phrase secrète, les **anciennes sauvegardes** restent lisibles avec l'ancienne phrase : supprimez-les ou mettez à jour l'enveloppe.

## 5. Revue du dispositif

**Chaque année** (choisir une date fixe, par exemple le 1er janvier ou après Ramadan) :
- [ ] Ouvrir le dossier, relire chaque section, mettre à jour la date « Dernière mise à jour ».
- [ ] Vérifier les contacts (numéros, notaire et banquier encore en poste ?).
- [ ] Ajouter ou retirer les comptes, contrats, crédits et abonnements.
- [ ] Faire une nouvelle sauvegarde `.json` sur les clés USB et en ligne ; supprimer les anciennes.
- [ ] Réimprimer la version papier et remplacer celle du coffre.
- [ ] Tester avec mon épouse : peut-elle ouvrir le dossier seule, sans mon aide ?

**Immédiatement**, après un événement important : naissance, mariage d'un enfant, achat ou vente d'un bien, nouveau crédit, changement d'employeur, déménagement à l'étranger, nouveau contrat d'assurance.

## 6. Le dire à la famille

Le dispositif ne fonctionne que si la famille sait qu'il existe. Une conversation simple suffit :

> « J'ai rassemblé dans un dossier tout ce dont vous auriez besoin s'il m'arrivait quelque chose. La feuille dans le classeur te dit qui appeler. Le dossier complet est là, la phrase pour l'ouvrir est ici. On l'ouvrira ensemble une fois pour que tu saches t'en servir. »

Pour les enfants, adapter selon l'âge. Les lettres personnelles (section « Mots personnels ») peuvent être écrites à la main et rangées sous enveloppe, avec une indication du moment où les lire.
