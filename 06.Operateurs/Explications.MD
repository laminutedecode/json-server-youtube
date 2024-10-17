JSON Server prend en charge les opérateurs logiques. Vous pouvez les utiliser pour filtrer les données de manière plus complexe. Par exemple, pour récupérer les langages de programmation avec un ID supérieur ou égal à 4, vous pouvez envoyer une requête GET à l'URL suivante :

<!-- _lte : "Less than or equal" (inférieur ou égal). Il permet de filtrer les éléments ayant une valeur inférieure ou égale à celle spécifiée. -->
Inferieur à 4 ou égale à 4
http://localhost:3000/data?id_lte=4

<!-- _gte : "Greater than or equal" (supérieur ou égal). Il permet de filtrer les éléments ayant une valeur supérieure ou égale à celle spécifiée.  -->
superieur ou egale à 4
http://localhost:3000/data?id_gte=4


<!-- _gt : "Greater than" (supérieur). Il permet de filtrer les éléments ayant une valeur strictement supérieure à celle spécifiée. -->
http://localhost:3000/data?id_gt=4
Superieur  égale à 4

<!-- _lt : "Less than" (inférieur). Il permet de filtrer les éléments ayant une valeur strictement inférieure à celle spécifiée. -->
http://localhost:3000/data?id_lt=4
Inferieur égale à 4

<!-- _ne : "Not equal" (différent). Il permet de filtrer les éléments ayant une valeur différente de celle spécifiée. -->
Different de 4
http://localhost:3000/data?id_ne=4




<!-- Ces opérateurs logiques offrent une flexibilité supplémentaire lors de la manipulation des données avec JSON Server, vous permettant ainsi de créer des requêtes plus spécifiques pour répondre à vos besoins de filtrage de données. -->