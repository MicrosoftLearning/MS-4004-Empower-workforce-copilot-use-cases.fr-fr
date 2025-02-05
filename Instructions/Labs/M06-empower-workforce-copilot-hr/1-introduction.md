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
L’objectif de ce module est d’offrir aux professionnels des Ressources Humaines (RH) les compétences et les connaissances nécessaires pour appliquer l’outil de complétion de code de Copilot basé sur l’IA pour simplifier leur workflow et améliorer leur productivité. En ce qui concerne les professionnels des RH, leur capacité à utiliser efficacement Microsoft 365 Copilot est cruciale dans les domaines suivants :

 -  **Recrutement**. Copilot peut aider les professionnels des RH à simplifier le processus de recrutement. Par exemple, il peut vous aider à créer des descriptions de poste, analyser les CV et même planifier des entretiens.
 -  **Intégration.** Copilot peut aider les professionnels des RH à intégrer les nouveaux employés. Par exemple, il peut vous aider à créer des plans d’intégration, à fournir des supports de formation et même à répondre aux questions courantes.
 -  **Gestion des performances**. Copilot peut aider les professionnels des RH à gérer les performances des employés. Par exemple, il peut vous aider à définir des objectifs, à suivre la progression et à fournir un retour d’information.
 -  **Engagement des employés**. Copilot peut aider les professionnels des RH à améliorer l’engagement des employés. Par exemple, il peut vous aider à créer des sondages, à analyser les résultats et même à suggérer des façons d’améliorer l’engagement.
 -  **Conformité**. Copilot peut aider les professionnels des RH à garantir la conformité vis-à-vis des réglementations. Par exemple, il peut vous aider à créer des stratégies, à suivre la conformité et même à fournir des supports de formation.

Microsoft 365 Copilot constitue un assistant d’écriture basé sur l’IA. Il comprend le contexte, suggère des phrases et aide à générer du contenu, ce qui permet d’améliorer la qualité de votre travail. Les exercices de ce module Cas d’usage sont conçus pour aider les professionnels des RH à acquérir les compétences suivantes :

 -  Utiliser Microsoft 365 Copilot pour Word pour créer une description de tâche pour un rôle.
 -  Utiliser Microsoft 365 Copilot pour Word pour analyser plusieurs CV, et fournir un rapport comparant les forces et les faiblesses de chaque candidat, classer les candidats du plus qualifié au moins qualifié et faire une recommandation.
 -  Utiliser Microsoft 365 Copilot pour Loop pour créer un ensemble de questions d’entretien à poser aux candidats pour ce poste.
 -  Utiliser Microsoft 365 Copilot pour Outlook pour créer une lettre d’offre par e-mail destinée au candidat sélectionné pour ce poste.
