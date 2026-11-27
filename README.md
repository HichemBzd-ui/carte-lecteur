# Carte de lecteur numérique

**Ouvrir la carte : https://hichembzd-ui.github.io/carte-lecteur/**

Page web installable (PWA), qui marche hors connexion, et qui affiche une carte de lecteur avec un code-barres Code 128 généré dans le navigateur (norme implémentée à la main, sans bibliothèque).

> **Projet de test, non officiel.** Simple petit projet d'apprentissage, voir l'avertissement plus bas.

## À quoi ça sert

L'idée : en cas de **perte, de vol ou d'oubli** de la carte physique, avoir sous la main une **carte numérique de secours** sur son téléphone, avec le même code-barres que la carte d'origine.

C'est seulement une idée de test : rien n'indique qu'elle soit acceptée par la bibliothèque. En cas de perte ou de vol de la vraie carte, il faut quand même **prévenir la bibliothèque**.

## L'esprit du projet

- **Gratuit et sans but lucratif.** Je ne cherche ni argent, ni rémunération, ni rien en échange. C'est fait par plaisir, pour aider : en voyant des étudiants, parfois venus de loin ou d'autres wilayas, refusés à l'entrée parce qu'ils ont oublié leur carte.
- **Si la bibliothèque le souhaite**, je peux le lui donner gratuitement, sans condition, et l'institution en fait ce qu'elle veut.
- **Aucune donnée n'est collectée.** C'est une simple page web : tout se passe dans le navigateur de la personne. Le nom et le numéro saisis restent sur son appareil, je n'y ai aucun accès, et il n'y a ni serveur, ni base de données, ni compte. Le code est ouvert et chacun peut le vérifier dans ce dépôt.
- C'est un **simple générateur de code-barres** : on entre un numéro, la page dessine le code-barres correspondant (Code 128). Elle ne se connecte à aucun système de la bibliothèque.
- Projet fait avec l'aide d'une IA, comme indiqué plus bas. Il reste à tester en conditions réelles et **rien n'est officiel**.

## Comment l'utiliser

1. Ouvrir le lien : https://hichembzd-ui.github.io/carte-lecteur/
2. Toucher le bouton **« تعديل البيانات »** (qui veut dire « modifier les données »).
3. Remplir **le nom, le prénom et le numéro de lecteur**. Le numéro de lecteur est **le numéro écrit sous le code-barres** de ta carte physique : il faut donc le noter **avant** de perdre la carte.
4. Garder le type **Code 128** (c'est le format de la carte d'origine), puis enregistrer. Le code-barres se recalcule tout seul.
5. Pour le présenter : toucher le code-barres pour l'afficher en plein écran, avec la luminosité au maximum.
6. Pour l'avoir toujours sous la main, l'installer sur l'écran d'accueil (voir « Installation » plus bas).

## Avertissement important

- **Ce projet n'est pas officiel.** Il n'est ni créé, ni approuvé, ni reconnu par la Bibliothèque nationale d'Algérie ni par aucune institution.
- C'est une **idée et un petit projet personnel de test**, fait pour apprendre. Rien ne garantit qu'il soit accepté ou lu par un scanner ou un système de contrôle.
- **Personne n'est obligé de l'utiliser.** Quiconque choisit de l'utiliser le fait **à ses propres risques et sous sa seule responsabilité**.
- **L'auteur n'est responsable de rien** en cas d'utilisation (refus d'accès, problème avec une institution, etc.), tant que le projet n'a pas été officialisé par l'institution concernée. S'il le devient un jour, cet avertissement sera mis à jour.
- **À utiliser uniquement en cas de perte de la carte physique.** Après utilisation, il faut **se rendre directement à l'administration de la bibliothèque** pour signaler la perte. Cette carte numérique ne remplace pas la vraie carte et ne dispense jamais de ce signalement.
- Ne pas utiliser pour se faire passer pour quelqu'un d'autre : chacun entre uniquement **ses propres** informations.

## Avertissement (بالعربية)

هذا المشروع **غير رسمي**، وهو مجرد فكرة وتجربة شخصية لا علاقة لها بالمكتبة الوطنية الجزائرية ولا بأي مؤسسة. استعماله اختياري وعلى مسؤولية المستخدم وحده، ولا يتحمل صاحب المشروع أي مسؤولية ما دام غير معتمد رسميا.

## Installation

Ouvrir le lien sur le téléphone (Safari sur iPhone, Chrome sur Android), puis « Sur l'écran d'accueil » ou « Installer l'application ». Ensuite elle s'ouvre sans internet.

## Données personnelles

Les données saisies (nom, numéro) restent **uniquement sur l'appareil** de la personne (stockage local du navigateur). Rien n'est envoyé nulle part et rien n'est enregistré dans ce dépôt. Les valeurs par défaut sont fictives.

## Pour la Bibliothèque nationale et ses responsables

Ce projet pourrait devenir une vraie solution **s'il était validé par la bibliothèque**. Donc :

- Si vous êtes **responsable à la Bibliothèque nationale** (ou dans l'institution) et que l'idée vous intéresse, vous pouvez me contacter pour en discuter sérieusement.
- Si vous **connaissez un responsable** là-bas, ou si vous avez des contacts qui pourraient lui présenter l'idée, n'hésitez pas à me joindre : l'objectif est de la proposer officiellement, de manière sérieuse et transparente.
- Ceci n'est pas une blague : c'est une vraie proposition, faite en toute bonne foi, que l'institution est libre d'accepter ou de refuser.

**Comment me contacter :** ouvrir une discussion dans l'onglet **Issues** de ce dépôt (bouton « New issue »), ou passer par ce compte GitHub.

للمسؤولين في المكتبة الوطنية الجزائرية، أو لمن يعرف مسؤولا هناك: إذا أعجبتكم الفكرة وترغبون في دراستها رسميا، يمكنكم التواصل معي عبر قسم **Issues** في هذا المستودع أو عبر هذا الحساب.

## À propos

Projet d'apprentissage réalisé avec l'aide d'une IA (Claude). Le format Code 128 a été décodé et vérifié sur une vraie carte pour comparer les barres.
