# Complete-software-testing-bootcamp.
Everything you need to know about software testing: Design, Plan, Campaign and Test Strategy, Automation.

# Test logiciel : Les niveaux de test  

## Test de composant (test unitaire):  
   - Les tests composant sont réalisé par les développeur dans le but.  

## Test d'intégration:  
    - Un test d'intégration est un type de test logiciel qui vise à vérifier que les différentes parties d'un système fonctionnent correctement ensemble, une fois qu'elles sont intégrées. Il s'agit donc de tester la bonne communication entre les différents composants du système.  

    Contrairement aux tests unitaires qui testent une unité de code isolément, les tests d'intégration vérifient le bon fonctionnement de l'ensemble du système, en testant l'interaction entre les différentes unités de code.  

    ### Voici un exemple concret de test d'intégration :  

    Supposons que vous travaillez sur un site Web de commerce électronique qui permet aux utilisateurs de passer des commandes en ligne. Votre site Web se compose de plusieurs modules, tels que le module de paiement, le module de gestion des commandes, le module de gestion des stocks, etc. Pour vérifier que tous ces modules fonctionnent correctement ensemble, vous pouvez créer un test d'intégration qui effectue une commande réelle sur le site et vérifie que la commande est correctement traitée, que le paiement est accepté, que le stock est correctement mis à jour, etc.

    ### Le test d'intégration pourrait se dérouler comme suit :

    1. Créez un utilisateur de test sur le site Web.
    2. Ajoutez un produit au panier et vérifiez que le produit est bien ajouté.
    3. Entrez les informations de livraison et de facturation et passez à l'étape suivante.
    4. Sélectionnez une méthode de paiement (par exemple, carte de crédit).
    5. Entrez les informations de paiement et vérifiez que le paiement est accepté.
    6. Vérifiez que la commande est correctement enregistrée dans le module de gestion des commandes.
    7. Vérifiez que le stock est correctement mis à jour dans le module de gestion des stocks.
    8. Vérifiez que le client reçoit une confirmation de commande par e-mail.
    Ce test d'intégration permet de vérifier que l'ensemble du système fonctionne correctement et permet de détecter les éventuelles erreurs ou problèmes d'interaction entre les différents modules du système.  

## Test système
    Permet la Validation des tests composant. En cas d'anomalie l'équipe dev est en charge de trouver une solution.  

## Test d'acceptation 
    Phase de recette ou VSR
