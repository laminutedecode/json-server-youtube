Supposons que nous voulons introduire des relations entre les langages et les développeurs qui les utilisent. Voici comment cela pourrait être fait :

{
  "languages": [
    {"id": 1, "name": "HTML", "category": "frontend"},
    {"id": 2, "name": "CSS", "category": "frontend"},
    {"id": 3, "name": "JavaScript", "category": "frontend"},
    {"id": 4, "name": "Python", "category": "backend"},
    {"id": 5, "name": "Ruby", "category": "backend"},
    {"id": 6, "name": "Java", "category": "backend"},
    {"id": 7, "name": "PHP", "category": "backend"},
    {"id": 8, "name": "SQL", "category": "backend"},
    {"id": 9, "name": "C#", "category": "backend"}
  ],
  "developers": [
    {"id": 1, "name": "Alice", "languages": [1, 2, 3]},
    {"id": 2, "name": "Bob", "languages": [4, 5]},
    {"id": 3, "name": "Charlie", "languages": [6, 7, 8, 9]}
  ]
}

<!-- Dans cet exemple, nous avons introduit deux types d'objets : "languages" (langages) et "developers" (développeurs). Les développeurs sont associés à des langages via une liste d'identifiants de langage. Cette liste d'identifiants représente les langages que chaque développeur connaît. -->

<!-- Ainsi, nous avons créé une relation entre les développeurs et les langages qu'ils utilisent. Cette modélisation permet de représenter efficacement les relations complexes entre les données dans un fichier JSON. -->

http://localhost:3000/data?_expand=developers