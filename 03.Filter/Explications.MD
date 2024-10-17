Pour filtrer les données dans JSON Server, vous pouvez utiliser les paramètres de requête pour spécifier les critères de filtrage. 

Voici comment vous pouvez filtrer les données dans différents scénarios :

Filtrer par ID : Pour récupérer un seul élément par son ID, vous pouvez utiliser la syntaxe suivante :

http://localhost:3000/data?id=2

Par exemple, pour obtenir l'élément avec l'ID 1, vous enverrez une requête GET à /data/1.

Filtrer par un attribut spécifique : Si vous souhaitez filtrer les données en fonction d'un attribut spécifique, vous pouvez utiliser la syntaxe suivante :
(http://localhost:3000/data?categorie=frontend)


Filtrer avec plusieurs attributs : Vous pouvez également combiner plusieurs critères de filtrage en ajoutant des paramètres de requête supplémentaires :
(http://localhost:3000/data?categorie=frontend&langage=HTML)



