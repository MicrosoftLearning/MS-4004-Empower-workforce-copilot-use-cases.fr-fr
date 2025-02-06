# Préparation du labo :

Durant ce module, nous allons créer des prompts Microsoft 365 Copilot qui feront référence à des fichiers. Tout d’abord, chargeons tous les fichiers requis sur OneDrive pour s’assurer qu’ils sont accessibles au cours de ce labo.


### Chargement des fichiers dans OneDrive

Suivez les étapes ci-dessous pour charger tous les fichiers requis dans **OneDrive** :

1. Connectez-vous à la machine virtuelle fournie par votre fournisseur de locataire en tant que compte **Administrateur** local avec le mot de passe `Pa55w.rd`.
2. Dans la barre des tâches Windows, sélectionnez **Microsoft Edge**.
3. Dans la barre d’adresse, entrez `https://www.office.com` .
4. Sous **Bienvenue dans Microsoft 365**, sélectionnez **Se connecter**.
5. À l’**invite de connexion**, entrez `userx@yourtenant.onmicrosoft.com` (nom d’utilisateur et locataire fournis par votre fournisseur de locataire), puis sélectionnez **Suivant**.
6. Dans l’écran **Entrez le mot de passe**, entrez le mot de passe (fourni par le fournisseur de locataire) pour le compte d’utilisateur, puis sélectionnez **Se connecter**.
7. Si vous êtes invité à **rester connecté**, sélectionnez **Ne plus afficher**, puis **Oui**.
8. Dans **Microsoft 365**, sélectionnez **Applications**.
9. Dans **Applications**, sélectionnez **OneDrive**.
10. Dans **OneDrive**, dans le coin supérieur gauche, sélectionnez **+** (ajouter) > **Chargement de fichiers**.
11. Dans l’**Explorateur de fichiers**, sélectionnez **Ce PC** > **Disque local (C:)** et ouvrez le dossier **ResourceFiles**.
12. Sélectionnez tous les fichiers du dossier **ResourceFiles**, puis sélectionnez **Ouvrir** pour les charger dans **OneDrive**.
13. Une fois le chargement terminé, vous devriez voir **29 éléments chargés dans Mes fichiers** en bas au centre de l’écran.
14. Laissez **Edge** ouvert et passez à la tâche suivante.

### Référencement de fichiers dans Copilot

Lorsque vous utilisez Copilot, vous pouvez constater que certains fichiers ne sont pas immédiatement disponibles dans les suggestions. En effet, certaines expériences Copilot référencent uniquement les fichiers figurant dans la **liste des éléments utilisés récemment**, tandis que d’autres vous permettent de parcourir **OneDrive** directement. Pour vous assurer qu’un fichier apparaît dans la **liste des éléments utilisés récemment**, il vous suffit de l’ouvrir dans l’application Microsoft 365 appropriée, et il sera ajouté automatiquement.

> [!IMPORTANT]
> Microsoft 365 Copilot fonctionne uniquement avec les fichiers enregistrés dans **OneDrive**. Les fichiers stockés localement sur votre PC doivent être déplacés vers **OneDrive** pour que Copilot puisse y accéder.

À mesure que vous progressez dans le module, vous aurez la possibilité d’essayer différents prompts sur ces fichiers. N’hésitez pas à expérimenter différentes approches pour améliorer vos compétences avec Copilot.

# Introduction
---
En utilisant Microsoft 365 Copilot, les professionnels de la finance peuvent économiser du temps et des efforts, simplifier leur travail et prendre des décisions éclairées basées sur des informations sur les données. Ce module permet aux professionnels de la finance d’acquérir les compétences et les connaissances nécessaires à l’utilisation de l’outil de complétion de code basé sur l’IA de Copilot pour simplifier votre flux de travail et améliorer votre productivité. En tant que professionnel des finances, votre capacité à utiliser efficacement Microsoft 365 Copilot est essentielle pour :

 -  **Automatisation des tâches financières** : Copilot peut aider les professionnels de la finance à automatiser des tâches financières répétitives. Par exemple, il peut vous aider à budgéter, planifier et même préparer les impôts.
 -  **Fourniture d’insights** : Copilot peut aider les professionnels de la finance à obtenir des insights sur leurs données financières. Par exemple, il peut vous aider à analyser des états financiers, identifier des tendances et même prédire les résultats futurs.
 -  **Amélioration de la productivité** : Copilot peut aider les professionnels de la finance à économiser du temps en automatisant les tâches manuelles. Par exemple, il peut vous aider à entrer des données, générer des rapports et même corriger des documents.
 -  **Collaboration** : Copilot peut aider les professionnels de la finance à collaborer plus efficacement. Par exemple, il peut vous aider à gérer des projets, communiquer en équipe et même partager des documents.

Microsoft 365 Copilot constitue un assistant d’écriture basé sur l’IA. Il comprend le contexte, suggère des expressions et aide à générer du contenu, tout ce qui peut améliorer la qualité de votre travail. Les exercices de ce module Cas d’usage sont conçus pour aider les professionnels de la finance à acquérir les compétences suivantes :

 -  Utiliser Microsoft 365 Copilot pour Outlook pour créer un e-mail destiné à la compagnie d’assurance de l’entreprise afin de discuter des augmentations excessives de ses primes d’assurance maladie.
 -  Utiliser Microsoft 365 Copilot pour Excel pour analyser une feuille de calcul contenant les prévisions des revenus des campagnes marketing du premier trimestre, puis ajouter de nouveaux calculs et graphiques pour visualiser les données.
 -  Utiliser Microsoft 365 Copilot pour Word pour créer un rapport de campagne marketing basé sur la feuille de calcul de la campagne marketing du premier trimestre de l’entreprise.
 -  Utiliser Microsoft 365 Copilot pour Word pour résumer les résultats financiers des cinq dernières années d’une entreprise.
