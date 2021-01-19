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

19/une pull request permet de proposer les changements qu'un utilisateur a effectuer. Celui qui gère le projet peut ensuite examiner les modifications et accepter ou refuser de merge pour les ajouter à la branche principale

20/Vercel deploie la branche cmd du projet sur les versions développement (lors du pull request) et preview (après la modification)

21/la version production correspond à la branche master du projet, les pull requests permettent de proposer les changements dans l'environnement preview afin de les tester. A son développemnt la feature est ajouter d'abord à la version preview (version de développement) puis passe par la version preview au pull request (version permettant de tester les modifications) et lors du merge la feature apparait sur la version production qui est utilisé par tout les utilisateurs.

22/ en serverless, un for=urnisseur de services cloud execute une partie du code, sa rémunération dépends de la quantité de code executé. 
