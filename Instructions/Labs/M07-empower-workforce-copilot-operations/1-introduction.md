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
Ce module équipe Operations Managers avec les compétences et les connaissances nécessaires pour utiliser l’outil d’achèvement du code optimisé par l’IA de Copilot pour simplifier leur flux de travail et améliorer leur productivité. En tant que responsable des opérations, votre capacité à utiliser efficacement Microsoft 365 Copilot est essentielle pour :<br>

 -  **Gestion de projet**. Copilot peut aider les responsables des opérations à gérer les projets plus efficacement. Par exemple, il peut les aider avec l’attribution de tâches, la planification et même fournir des insights sur les performances du projet.
 -  **Automatisation des processus**. Copilot peut aider Operations Managers à automatiser les tâches répétitives. Par exemple, il peut les aider à entrer des données, à générer des rapports et même à lire des preuves.
 -  **Collaboration**. Copilot peut aider les responsables des opérations à collaborer plus efficacement. Par exemple, il peut les aider à communiquer en équipe, partager des documents et même fournir des rappels.
 -  **Personnalisation**. Copilot peut être personnalisé pour répondre aux besoins uniques des gestionnaires d’opérations. Par exemple, il peut les aider à gérer l’inventaire, à optimiser la chaîne d’approvisionnement et même à contrôler la qualité.

Microsoft 365 Copilot constitue un assistant d’écriture basé sur l’IA. Il comprend le contexte, suggère des expressions et aide à générer du contenu, qui peuvent tous améliorer la qualité de votre travail. Les exercices de ce module Cas d’usage sont conçus pour aider les gestionnaires d’opérations à acquérir les compétences suivantes :

 -  Utilisez Microsoft 365 Copilot dans Whiteboard pour réfléchir aux idées de plan de projet pour installer un nouveau système de chaudière.
 -  Utiliser Microsoft 365 Copilot pour Outlook pour résumer un fil de discussion par e-mail et générer une réponse.
 -  Utiliser Microsoft 365 Copilot pour Word pour créer un rapport qui analyse les différents systèmes de chauffage à chaudière, tout en comparant les types de sortie que Copilot peut générer.
 -  Utiliser Microsoft 365 Copilot pour PowerPoint pour créer une présentation basée sur le rapport que vous avez créé qui analyse les différents systèmes de chauffage à chaudière.
