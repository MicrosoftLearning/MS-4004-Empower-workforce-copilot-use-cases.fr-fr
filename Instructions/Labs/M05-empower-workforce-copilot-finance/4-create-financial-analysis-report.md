# Créer un rapport d’analyse financière à l’aide de Copilot dans Word
---
Copilot dans Word peut aider les professionnels de la finance à créer des documents plus efficacement. Il peut les aider à écrire du contenu, des sujets de recherche et à transformer du contenu existant en un document dont ils peuvent être fiers. Copilot peut également gagner du temps et réfléchir en réécrivant et en modifiant des documents.

Par exemple, si vous êtes analyste financier et que vous devez écrire un rapport sur les performances d’une entreprise, vous pouvez utiliser Copilot dans Word pour rédiger le rapport. Vous pouvez indiquer à Copilot d’écrire « un rapport sur les performances financières de l’entreprise XYZ » et il génère un brouillon que vous pouvez affiner. Vous pouvez poser des questions à Copilot Chat pour effectuer des recherches, des idées ou effectuer une itération pour que le contenu possible soit ajouté.

Si vous travaillez sur un document existant, Copilot peut vous aider à réécrire et à modifier le document, ce qui vous permet de gagner du temps et de réfléchir. Dans cet exercice, vous demandez à Copilot dans Word d’écrire un nouveau rapport basé sur les données de la feuille de calcul Fabrikam Q1 Marketing Campaign que vous avez analysée et mise à jour dans l’exercice précédent. Toutefois, au lieu d’utiliser la feuille de calcul Excel, vous utiliserez plutôt un document Word qui contient toutes les données de feuille de calcul.

> **REMARQUE :** Copilot dans Word peut créer un rapport basé sur une feuille de calcul. Toutefois, vous ne pouvez pas référencer directement un fichier Excel à partir de Word. Au lieu de cela, vous devez copier et coller les données du fichier Excel dans un document Word. Une fois que les données se trouvent dans un document Word, vous pouvez utiliser Copilot pour générer un rapport basé sur ces données. Dans cet exercice, les données de la feuille de calcul utilisées dans l’exercice précédent ont été copiées et collées dans un document Word intitulé **données de campagne marketing Fabrikam Q1**.

> **CONSEIL :** Lorsque vous travaillez dans Copilot, s’il retourne un quelconque message d’erreur, soumettez à nouveau votre invite. Cela résout souvent le problème. De même, les données ne sont pas présentées correctement (telles que les données de table affichées dans le code HTML plutôt qu’une table Word), puis entrez un prompt demandant à Copilot de corriger les données et de les présenter correctement (par exemple : **Les tableaux croisés dynamiques apparaissent tous dans le code HTML. Convertissez ces tableaux en format de tableau dans Word).**

### Exercice

En tant que directeur financier de Fabrikam, vous avez utilisé Copilot dans Excel pour analyser l’efficacité des campagnes marketing Q1 de l’entreprise dans l’exercice précédent. Dans cet exercice, vous prévoyez d’utiliser Copilot dans Word pour générer un rapport qui résume l’analyse de ces données. La feuille de calcul a été copiée et collée pour vous dans un document Word, que vous allez télécharger à la première étape.

1.  Sélectionnez le lien suivant pour télécharger la feuille de calcul [Données des campagnes marketing Fabrikam Q1](https://edxinteractivepage.blob.core.windows.net/ms-4004/Fabrikam%20Q1%20marketing%20campaign%20data.docx).
2.  Une fois le téléchargement terminé, déplacez le fichier vers votre compte OneDrive, puis ouvrez et fermez le fichier pour l’obtenir dans votre liste de fichiers les plus récemment utilisés (MRU).
3.  Si vous avez un onglet **Microsoft 365** ouvert dans votre navigateur Microsoft Edge, sélectionnez-le maintenant, ou ouvrez un nouvel onglet et entrez l’URL suivante : **https://www.office.com**
4.  Dans **Microsoft 365**, ouvrez **Microsoft Word** puis ouvrez un document vide.
5.  Dans la fenêtre **Brouillon avec Copilot** qui apparaît en haut du document vide, entrez l’invite suivante mais ne sélectionnez pas le bouton **Générer** avant d’avoir lié les fichiers au prompt de l’étape suivante :
    
    **Je suis le directeur financier de Fabrikam. Créez un rapport d’analyse des campagnes marketing Q1 basé sur le fichier joint qui fournit des données sur nos campagnes marketing Q1. Inclure les sections suivantes dans le rapport : Résumé exécutif, analyse des données et recommandations**.
6.  Vous devez maintenant joindre au prompt, le fichier de la **campagne marketing Fabrikam Q1 data.docx** que vous avez téléchargé. Dans la fenêtre **Brouillon avec Copilot**, sélectionnez le bouton **Référencer votre contenu**. Dans le menu déroulant qui s’affiche, si le fichier **Données des campagnes marketing Q1 de Fabrikam.docx** apparaît dans la liste des fichiers, sélectionnez-le. Dans le cas contraire, sélectionnez **Parcourir les fichiers à partir du cloud**, sélectionnez le fichier dans la liste des fichiers **Récents**, puis sélectionnez le bouton **Joindre**. Si le fichier n’apparaît pas dans la liste des fichiers **Récents**, sélectionnez **Mes fichiers** en haut du volet de navigation dans la fenêtre **Choisir un fichier**, accédez au dossier où vous avez stocké le fichier, sélectionnez le fichier, puis sélectionnez **Attacher**. Notez comment le fichier est affiché dans le prompt.
7.  Sélectionnez **Générer**. En procédant ainsi, Copilot extrait les informations pertinentes du fichier et rédige un rapport qui analyse les données.
8.  Passez en revue les résultats. Si les données de la section **résumé exécutif** sont présentées dans une liste à puces, entrez l’invite suivante et remplacez **\{table ou liste à puces\}** par **table**. Si les données **résumé exécutif** n’ont pas le format de liste à puces, entrez le prompt suivant et remplacez **\{table ou liste à puces\}** par **liste à puces** :
    
    **Merci de convertir les informations de la section Résumé exécutif au format tableau \{ou liste à puces\}**.
9.  Si la section **Analyse des données** est déjà au format tableau, passez à l’étape suivante. Sinon, entrez le prompt suivant pour placer les données dans une table afin qu’elles soient plus faciles à lire :
    
    **Convertissez les informations de la section Analyse des données en un format tableau**.
10. Examinez le tableau des données dans la section **Analyse des données**. Voyons si Copilot peut supprimer une colonne de données d’un tableau. Entrez l’invite suivante et remplacez \{titre\} par le nom d’une colonne à supprimer :
    
    **Dans le tableau des données de la section Analyse des données, supprimez \{l’en-tête\} colonne**.
11. Vous aimez les **recommandations** mais vous pensez qu’elles seraient plus utiles si Copilot affichait les données par ordre d’importance. Entrez le prompt suivant pour que Copilot apporte cette modification :
    
    **Dans la section Recommandations, affichez les éléments par ordre d’importance en commençant par l’élément le plus important**.
12. Après avoir examiné ce dernier brouillon, vous êtes satisfait du rapport et vous êtes prêt à l’enregistrer. Dans la fenêtre Copilot située en bas du document, sélectionnez le bouton **Conserver** pour le convertir d’un brouillon Copilot en document Word.
13. Passez en revue ce document. Une fois que vous êtes satisfait de celui-ci, vous pouvez ignorer le document ou l’enregistrer dans votre OneDrive pour référence ultérieure.
14. Fermez cet onglet dans votre navigateur Microsoft Edge.
