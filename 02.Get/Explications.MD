la méthode GET est l'une des principales méthodes HTTP utilisées pour récupérer des données à partir du serveur.

Lorsque vous effectuez une requête GET à un endpoint spécifique sur JSON Server, cela signifie que vous demandez au serveur de vous renvoyer les données correspondant à cet endpoint. Par exemple, avec notre data fichier JSON si vous exécutez une requête GET à l'endpoint /data, le serveur répondra avec une liste de tous des langages disponibles dans le fichier JSON


http://localhost:3000/data

ou

http://localhost:3000/data?id=1

Cette requête pourrait récupérer un langage avec l'ID 1 dans la liste des langages.

En résumé, la méthode GET dans JSON Server est utilisée pour récupérer des données à partir du serveur en spécifiant l'endpoint approprié dans l'URL de la requête.