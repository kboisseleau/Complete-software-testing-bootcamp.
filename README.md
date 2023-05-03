# Complete-software-testing-bootcamp.
Everything you need to know about software testing: Design, Plan, Campaign and Test Strategy, Automation.

# Test logiciel : Les niveaux de test  

## Test de composant (test unitaire):  
    Un test unitaire est une procédure de test automatisée qui vise à vérifier le comportement attendu  
    d'une unité de code isolée, telle qu'une   fonction, une méthode ou une classe, dans un  
    environnement contrôlé.  

    Le but des tests unitaires est de garantir que chaque unité de code fonctionne correctement  
    et de manière indépendante, en s'assurant que toutes les entrées possibles sont correctement  
    traitées et que les sorties produites sont conformes aux attentes. Les tests unitaires sont  
    généralement écrits par les développeurs eux-mêmes et sont souvent exécutés automatiquement  
    à chaque modification de code pour détecter rapidement les erreurs et les régressions potentielles.  

    En faisant des tests unitaires, vous pouvez vous assurer que votre code fonctionne correctement et  
    éviter les erreurs qui pourraient se propager à d'autres parties de votre application.  
      
    Les avantages des tests unitaires incluent:  

    Détection précoce des erreurs:  
    les tests unitaires vous permettent de détecter rapidement les  
    erreurs dans votre code, ce qui facilite leur correction avant qu'elles ne se propagent à d'autres
    parties de votre application.  
      
    Documentation du comportement:  
    les tests unitaires agissent également comme une documentation en  
    décrivant le comportement attendu de chaque unité de code.  
    Réduction du temps de débogage: en détectant les erreurs plus tôt, les tests unitaires permettent  
    également de réduire le temps de débogage nécessaire pour les corriger.  
    En somme, les tests unitaires sont une pratique importante de l'ingénierie logicielle qui permet  
    de garantir la qualité et la fiabilité du code.  

## Test d'intégration:  
    Un test d'intégration est un type de test logiciel qui vise à vérifier que les différentes parties  
    d'un système fonctionnent correctement ensemble, une fois qu'elles sont intégrées. Il s'agit  
    donc de tester la bonne communication entre les différents composants du système.  

    Contrairement aux tests unitaires qui testent une unité de code isolément, les tests 
    d'intégration vérifient le bon fonctionnement de l'ensemble du système, en testant  
    l'interaction entre les différentes unités de code.  

    Voici un exemple concret de test d'intégration :  

    Supposons que vous travaillez sur un site Web de commerce électronique qui permet aux  
    utilisateurs de passer des commandes en ligne. Votre site Web se compose de plusieurs  
    modules, tels que le module de paiement, le module de gestion des commandes, le module  
    de gestion des stocks, etc. Pour vérifier que tous ces modules fonctionnent  
    correctement ensemble, vous pouvez créer un test d'intégration qui effectue  
    une commande réelle sur le site et vérifie que la commande est correctement  
    traitée, que le paiement est accepté, que le stock est correctement mis à jour, etc.  

    Le test d'intégration pourrait se dérouler comme suit :

    1. Créez un utilisateur de test sur le site Web.
    2. Ajoutez un produit au panier et vérifiez que le produit est bien ajouté.
    3. Entrez les informations de livraison et de facturation et passez à l'étape suivante.
    4. Sélectionnez une méthode de paiement (par exemple, carte de crédit).
    5. Entrez les informations de paiement et vérifiez que le paiement est accepté.
    6. Vérifiez que la commande est correctement enregistrée dans le module de gestion des commandes.
    7. Vérifiez que le stock est correctement mis à jour dans le module de gestion des stocks.
    8. Vérifiez que le client reçoit une confirmation de commande par e-mail.
    Ce test d'intégration permet de vérifier que l'ensemble du système fonctionne correctement  
    et permet de détecter  
    les éventuelles erreurs ou problèmes d'interaction entre les différents modules du système.  

## Test système
    Permet la Validation des tests composant. En cas d'anomalie l'équipe dev est en charge de  
    trouver une solution.  

## Test d'acceptation 
    Phase de recette ou VSR
