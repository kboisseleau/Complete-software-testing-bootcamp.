# Test logiciel : Les niveaux de test  

## Test de composant (test unitaire):  
    Un test unitaire est une procédure de test automatisée qui vise à vérifier le comportement attendu  
    d'une unité de code isolée, telle qu'une fonction, une méthode ou une classe, dans un  
    environnement contrôlé.  

    Le but des tests unitaires est de garantir que chaque unité de code fonctionne correctement  
    et de manière indépendante, en s'assurant que toutes les entrées possibles sont correctement  
    traitées et que les sorties produites sont conformes aux attentes. Les tests unitaires sont  
    écrits par les développeurs pour détecter rapidement les erreurs et les régressions potentielles.  

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
    Un test système est un type de test qui vérifie le bon fonctionnement de l'ensemble d'un système  
    ou d'une application dans son environnement réel, y compris toutes les interactions avec les  
    autres systèmes et composants.  

    Le but des tests système est de s'assurer que le système ou l'application fonctionne correctement  
    dans son ensemble, tel qu'il est censé être utilisé dans des conditions réelles, et qu'il répond  
    aux exigences et aux spécifications fonctionnelles et non fonctionnelles. Les tests système sont  
    généralement effectués après les tests unitaires et d'intégration pour valider le système dans  
    son ensemble avant sa mise en production.  

    En faisant des tests système, vous pouvez vous assurer que votre application fonctionne correctement  
    et répond aux exigences du client.  
      
    Les avantages des tests système incluent:  

    Détection de problèmes de compatibilité:  
    les tests système permettent de détecter les problèmes de compatibilité avec d'autres systèmes  
    et composants, ce qui peut éviter des problèmes coûteux lors de la mise en production.  
    Détection de problèmes de performance: les tests système permettent également de détecter les  
    problèmes de performance, tels que les temps de réponse trop longs ou les erreurs de traitement  
    de volume élevé de données.  
      
    Validation de l'expérience utilisateur:  
      
    les tests système permettent de valider l'expérience utilisateur, en s'assurant que toutes les  
    fonctionnalités sont disponibles et fonctionnent correctement.  
    En somme, les tests système sont une pratique importante de l'ingénierie logicielle qui permet  
    de valider le système ou l'application dans son ensemble avant sa mise en production, garantissant  
    ainsi que l'application est prête pour une utilisation réelle.  

## Test d'acceptation 
    Un test d'acceptation est un type de test logiciel qui vérifie si le système répond aux exigences  
    et attentes des utilisateurs et des parties prenantes. Il s'agit d'un test de haut niveau qui vise  
    à déterminer si le système est prêt pour une utilisation réelle et peut être accepté par les  
    utilisateurs finaux.  
  
    Les tests d'acceptation peuvent être effectués manuellement ou de manière automatisée. Les tests manuels  
    impliquent souvent des scénarios de test basés sur des cas d'utilisation réels, tandis que les tests  
    automatisés peuvent utiliser des frameworks de test ou des outils de simulation pour simuler des  
    interactions utilisateur.  
  
    Voici un exemple de test d'acceptation pour une application de commerce électronique:  
  
    Supposons que nous devions tester une fonctionnalité de panier d'achat pour une boutique en ligne.  
    Les exigences de cette fonctionnalité sont les suivantes:  
  
    - L'utilisateur doit pouvoir ajouter un produit au panier.  
    - L'utilisateur doit pouvoir supprimer un produit du panier.  
    - L'utilisateur doit pouvoir modifier la quantité d'un produit dans le panier.  
    - Le panier doit afficher le montant total des produits ajoutés.  
    - L'utilisateur doit pouvoir passer à la caisse et finaliser la commande.  
    - Pour effectuer un test d'acceptation, nous pouvons suivre les étapes suivantes:  
  
    1. Planification et préparation: Nous devons identifier les scénarios de test à effectuer pour cette  
    fonctionnalité. Nous pouvons utiliser des techniques de conception de test pour garantir une couverture  
    complète des exigences. Nous devons également préparer un environnement de test avec des données de test  
    et les configurations nécessaires.  
      
    2. Conception de scénarios de test: Nous pouvons concevoir des scénarios de test qui couvrent toutes  
    les exigences de la fonctionnalité, tels que:  
    
    -Ajouter un produit au panier et vérifier qu'il apparaît dans le panier avec la quantité correcte.  
    -Supprimer un produit du panier et vérifier qu'il disparaît du panier.  
    -Modifier la quantité d'un produit dans le panier et vérifier que le montant total est mis à jour en conséquence.  
    - Passer à la caisse et finaliser la commande. 
       
    3. Exécution des tests: Nous pouvons exécuter les scénarios de test dans l'environnement de test  
    préparé, en suivant le plan de test. Nous devons enregistrer les résultats de test et les  
    défauts identifiés.  
  
    4. Analyse des résultats: Nous pouvons analyser les résultats de test pour identifier les défauts  
    et les problèmes de performance. Nous pouvons également vérifier si les exigences ont été satisfaites.  
  
    5. Rapports de test et revue: Nous devons générer des rapports de test pour documenter les résultats de  
    test et les défauts identifiés. Nous devons également réviser les rapports de test avec les parties  
    prenantes du projet, y compris les développeurs, les chefs de projet et les clients.  
  
    Les tests d'acceptation sont importants pour garantir la qualité et la fiabilité du système.  
