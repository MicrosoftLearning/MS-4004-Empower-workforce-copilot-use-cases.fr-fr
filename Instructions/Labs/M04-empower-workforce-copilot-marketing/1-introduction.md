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
Microsoft 365 Copilot peut assister de plusieurs façons les professionnels du marketing. Par exemple, ils peuvent générer du contenu pour leurs campagnes, améliorer la productivité, fournir des insights sur les campagnes, collaborer de manière plus efficace et bien plus encore. Copilot peut suggérer des mots-dièse, des images et même rédiger à votre place des publications pour les réseaux sociaux. De même, si vous créez un billet de blog, Copilot peut suggérer des sujets, fournir des ressources de recherche et même vous aider à le rédiger.

Copilot peut également permettre aux professionnels du marketing de gagner du temps en automatisant les tâches répétitives comme la mise en forme, l’ajout de tableaux et de graphiques, et même la révision des documents. En outre, Copilot peut analyser la performance de vos publications sur les réseaux sociaux, découvrir celles qui sont les plus engageantes et déterminer le meilleur moment de la journée pour les publier. Copilot peut également vous aider à collaborer plus efficacement avec votre équipe en vous aidant à distribuer des tâches, à définir des délais et même à effectuer des relances.

Ce module permet aux professionnels du marketing d’acquérir les compétences et connaissances nécessaires pour mobiliser l’outil Copilot de complétion de code basé sur l’IA afin de simplifier leur flux de travail et améliorer leur productivité. Votre capacité à communiquer de manière transparente avec Copilot et d’extraire des réponses précises est primordiale pour :

 -  **Générer du contenu** : Copilot peut aider les professionnels du marketing à générer du contenu pour leurs campagnes. Par exemple, si vous créez une publication pour les réseaux sociaux, Copilot peut suggérer des mots-dièse, des images et même la rédiger à votre place. De même, si vous créez un billet de blog, Copilot peut suggérer des sujets, fournir des ressources de recherche et même vous aider à le rédiger.
 -  **Améliorer la productivité** : Copilot peut aider les professionnels du marketing à gagner du temps en automatisant des tâches répétitives. Par exemple, si vous créez un rapport, Copilot peut vous aider avec la mise en forme, l’ajout de tableaux et de graphiques et même la révision du document.
 -  **Fournir des insights** : Copilot peut aider les professionnels du marketing à obtenir des insights sur leurs campagnes. Par exemple, si vous mettez en œuvre une campagne sur les réseaux sociaux, Copilot peut analyser la performance de vos publications, découvrir celles qui sont les plus engageantes et déterminer le meilleur moment de la journée pour les publier.
 -  **Collaborer** : Copilot peut aider les professionnels du marketing à collaborer plus efficacement. Par exemple, si vous travaillez sur un projet en équipe, Copilot peut vous aider à attribuer des tâches, à définir des délais et même à effectuer des relances.
 -  **L’intégration à Microsoft 365** : Copilot est intégré à des applications Microsoft 365 telles que Teams, Word, Outlook, PowerPoint et Excel. Les professionnels du marketing peuvent donc utiliser Copilot dans ces applications pour obtenir de l’aide dans leur travail.

Microsoft 365 Copilot constitue un assistant d’écriture basé sur l’IA. Il comprend le contexte, suggère des expressions et aide à générer du contenu. Tout cela peut contribuer à améliorer la qualité de votre travail. Les exercices de ce module de cas d’usage sont conçus pour aider les professionnels du marketing à acquérir les compétences suivantes :

 -  Utiliser Microsoft 365 Business Chat pour analyser les tendances du marché, fournir des prévisions de ventes et identifier de nouvelles opportunités de vente.
 -  Utiliser Microsoft 365 Copilot pour Loop pour générer des idées de campagne marketing pour une nouvelle ligne de produits.
 -  Utilisez Microsoft 365 Copilot dans Word pour consolider trois rapports de marketing produit en un seul rapport d’analyse du marché.
 -  Utiliser Microsoft 365 Copilot pour Excel pour analyser les tendances du marché dans une feuille de calcul.
