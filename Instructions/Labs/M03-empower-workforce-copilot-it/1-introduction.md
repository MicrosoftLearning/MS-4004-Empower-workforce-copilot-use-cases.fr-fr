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
Introduction
---
Microsoft 365 Copilot permet aux professionnels de l’informatique d’améliorer leur efficacité, de simplifier les tâches complexes et d’optimiser les flux de travail techniques. Avec Copilot, les professionnels de l’informatique peuvent gérer en toute transparence les opérations informatiques, résoudre les problèmes techniques, garantir la sécurité du système et appliquer des insights pilotés par les données pour la prise de décision stratégique.

Microsoft 365 Copilot sert d’outil précieux pour les professionnels de l’informatique, en leur permettant de naviguer facilement à travers les différentes subtilités de la gestion des technologies. Avec Copilot, ils peuvent identifier et résoudre rapidement les problèmes techniques pour optimiser les performances du système. Par conséquent, Copilot devient un allié indispensable dans la boîte à outils du professionnel de l’informatique. En utilisant Copilot, les professionnels de l’informatique peuvent gagner du temps et se concentrer sur les aspects critiques de leur rôle, tels que l’amélioration de la fiabilité du système, l’implémentation de solutions innovantes et la résolution proactive des défis informatiques.

Ce module permet aux professionnels de l’informatique d’acquérir les compétences et les connaissances nécessaires pour appliquer l’outil d’achèvement du code basé sur l’IA de Copilot pour simplifier leur flux de travail et améliorer leur productivité. En tant que professionnel de l’informatique, votre capacité à utiliser efficacement Microsoft 365 Copilot est essentielle pour :

 -  **Automatisation.** Copilot peut aider les professionnels de l’informatique à automatiser les tâches répétitives. Par exemple, il peut vous aider à gérer les correctifs, le déploiement de logiciels et même la surveillance du réseau.
 -  **Sécurité**. Copilot peut aider les professionnels de l’informatique à garantir la sécurité de leurs systèmes. Par exemple, il peut vous aider à détecter les menaces, à gérer les vulnérabilités et même à répondre aux incidents.
 -  **Résolution des problèmes**. Copilot peut aider les professionnels de l’informatique à résoudre les problèmes plus efficacement. Par exemple, il peut vous aider à analyser les causes racines, à analyser les journaux et même à suggérer des solutions aux problèmes courants.
 -  **Collaboration**. Copilot peut aider les professionnels de l’informatique à collaborer plus efficacement. Par exemple, il peut vous aider à gérer des projets, à communiquer en équipe et même à partager des documents.
 -  **Intégration avec Microsoft 365**. Copilot est intégré à des applications Microsoft 365 telles que Teams, Word, Outlook, PowerPoint et Excel. Cela signifie que les professionnels de l’informatique peuvent utiliser Copilot dans ces applications pour obtenir de l’aide sur leur travail.

Microsoft 365 Copilot constitue un assistant d’écriture basé sur l’IA. Il comprend le contexte, suggère des expressions et aide à générer du contenu, qui peuvent tous améliorer la qualité de votre travail. Les exercices de ce module Cas d’usage sont conçus pour aider les professionnels de l’informatique à acquérir les compétences suivantes :

 -  Utiliser Microsoft 365 Business Chat pour résumer les informations d’une spécification de produit et créer un plan de projet pour implémenter le produit.
 -  Utiliser Microsoft 365 Copilot pour PowerPoint pour créer une présentation basée sur le plan de projet que vous avez créé.
 -  Utilisez Microsoft 365 Copilot dans Word pour modifier un rapport de spécification technique.
 -  Utiliser Microsoft 365 Copilot pour Outlook pour rédiger un e-mail qui énonce les points forts du rapport de spécification technique.
