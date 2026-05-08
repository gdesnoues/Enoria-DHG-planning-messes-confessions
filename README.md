# Planning messes dominicales, quotidiennes et confessions

Modèle Enoria pour affichage de la liste des messes dominicales, quotidiennes et confessions (avec couleur liturgique)
Inspiré d'un modèle de Erwann Herpe

Nom du modèle : DHG - planning messes et confessions

Contact : guillaume.desnoues@gmail.com

Paroisse : Doyenné du Haut-Gresivaudan

repo. Github : [gdesnoues\Enoria-DHG-planning-messes-confessions](https://github.com/gdesnoues/Enoria-DHG-planning-messes-confessions)

options d'affichage :

- messes dominicales et fêtes (avec couleur liturgique + séparation par date, sauf Samedi/Dimanche regroupés)
- messes quotidiennes (avec couleur liturgique)
- confessions

## Critères de sélection

- Aller sur le module `Célébration`
- Filtrer la colonne `Date et heure` sur la période voulue
- Dans le bouton en haut à droite du choix de la sélection, prendre l'option `Sélectionner résultats filtrés` pour prendre toutes les lignes filtrées
- Aller dans `Outils / Documents`
- Sélectionner le modèle `DHG - planning messes et confessions`
- Cocher les cases des éditions que vous souhaitez voir dans le PDF (messes dominicales, confessions, messes quotidiennes)
- Lancer la génération avec `Selection / Visualisation PDF` (n'utilisez pas `Télécharger le PDF` qui peut ne pas fonctionner quand il y a trop de célébrations)

## Format

- PDF A4 Portrait
- Saut de page entre chaque type d'événement

## Astuces

- Affichage de la note de la célébration si elles ne commencent pas par un ! (critère de non\-affichage)
- Affichage du lieu (ville de l'adresse postale) s’il ne commencent pas par un ! (critère de non\-affichage)
- Affichage du nom de la salle entre () si le nom ne commence pas par un é (pour ne pas l'afficher pour les "église xxxxx", mais l'afficher pour les maisons de retraite, par exemple)
