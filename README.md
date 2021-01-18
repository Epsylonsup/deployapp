4/vercel -v
5/npx create-react-app deployapp
6/cd deployapp
vercel
7/ vercel list
8/vercel log
9/récupérer les informations concernant un déploiement 

10/les variables d'environnement sont des variables qui permettent de changer le fonctionnement de l'application en fonction de l'environnement dans lequel elle fonctionne.

11/vercel env add plain TEST_VARIABLE production

12/vercel env ls

13/les Secrets sont lié à la valeur d'une variable d'environnement et sont cryptés. Ils sont utilisé afin de partager des informations entre différent déploiement.

15/vercel secrets add secretG gawr

16/Production Preview et Development sont les environnements par défaut. 
