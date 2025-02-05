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
Pour les professionnels de la vente, une communication efficace est la pierre angulaire de la réussite. Dans ce module, vous allez découvrir la puissance de Microsoft 365 Copilot et comment les professionnels de la vente peuvent appliquer l’utilisation de prompts de façon stratégique pour améliorer leurs processus commerciaux.

Pour les professionnels de la vente, améliorer leur capacité à utiliser efficacement Copilot n’est pas seulement un avantage, c’est aussi un moyen de maximiser leur productivité. Cette compétence devient leur allié stratégique dans différents scénarios de vente impliquant des applications Microsoft 365, qu’il s’agisse de composer des e-mails d’information convaincants dans Outlook, de gérer des interactions avec les clients dans Excel, d’élaborer des présentations commerciales percutantes dans PowerPoint ou de collaborer facilement dans Teams.<br>

Ce module permet aux professionnels de la vente d’acquérir des techniques sophistiquées essentielles à la réussite de votre processus de vente. En tant que professionnel du secteur de la vente, votre capacité à utiliser efficacement Microsoft 365 Copilot est cruciale pour :

 -  **Automatiser la saisie de données**. Copilot peut aider les professionnels de la vente à automatiser des tâches répétitives, comme la saisie de données. Par exemple, il peut vous aider à capturer, accéder à et inscrire des données dans n’importe quel système de gestion de la relation client (CRM).<br>
 -  **Fournir des insights**. Copilot peut aider les professionnels de la vente à générer des prospects et à obtenir des insights sur leurs données de vente. Par exemple, il peut vous aider à analyser les tendances des ventes, à identifier les opportunités et même à prédire les résultats futurs.<br>
 -  **Améliorer la productivité**. Copilot peut aider les professionnels de la vente à gagner du temps en automatisant des tâches manuelles et en prenant en charge la gestion des pipelines. Par exemple, il peut vous aider à planifier, à assurer le suivi et même à relire les textes.<br>
 -  **Collaboration**. Copilot peut aider les professionnels de la vente à collaborer plus efficacement. Par exemple, il peut vous aider à communiquer avec vos équipes, à partager des documents et même à envoyer des rappels.

Microsoft 365 Copilot constitue un assistant d’écriture basé sur l’IA. Il comprend le contexte, suggère des phrases et aide à générer du contenu, tout ceci concourant à améliorer la qualité de votre travail. Les exercices de ce module Cas d’usage sont conçus pour aider les professionnels de la vente à développer les compétences suivantes :<br>

 -  Utilisez Microsoft 365 Copilot dans Loop pour créer un rapport d’étude du marché.
 -  Utiliser Microsoft 365 Copilot pour PowerPoint pour créer et personnaliser une présentation commerciale.
 -  Utiliser Microsoft 365 Business Chat pour résumer vos e-mails, vos réunions et vos conversations pour un projet spécifique au cours des 30 derniers jours, puis générer une liste d’actions et d’éléments d’action à propos d’une personne ou d’un sujet spécifique.
 -  Utiliser Microsoft 365 Copilot pour Word pour comparer trois accords avec le fournisseur, identifier les différences et recommander des actions.
