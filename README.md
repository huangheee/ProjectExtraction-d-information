# ProjetLaviedesmotssurleweb
## Présentation
Le mot « diplôme » sur l'Internet des français, des coréens et des chinois.

Dans le cadre de ce projet multilingue, nous devons :

- Faire une recherche sur Internet dans chacune des langues, axée sur un mot précis en récoltant au moins 50 urls.
- Mettre au point un script en langage Bash qui récupère le contenu des pages html, le met au format texte, y applique des traitements linguistiques dont les résultats sont rendus accessibles en ligne.
- Faire tourner le programme d'analyse ITrameur afin de voir ce que peux nous apprendre le "mot" sur ceux qui l'utilisent.

## Script
Le script que nous avons rédigé est destiné à élaborer un tableau html dans lequel plus de 50 URLS sont collectés par chacune de nous dans sa langue de travail (français, coréen et chinois). Ces urls sont issus de la recherche de pages internet contenant le mot diplôme dans chacune des langues. 

Nous vous présentons ci-dessous le déroulement général du script. En premier lieu, nous enregistrons tous les URLs dans un fichier au format texte. Nous avons ensuite commencé à créer l’en-tête de notre tableau html. 

Nous allons récupérer les index hiérarchiques, puis les bigrammes et les trigrammes pour chaque fichier. Nous utilisons ici un programme python et le stanford-segmenter pour segmenter le coréen et le chinois, enfin, nous recherchons les contextes des mots au format .txt et au format .html. Nous concaténons ensuite le contenu de nos fichiers dump dans un fichier, puis celui de nos fichiers contextes et nous pouvons terminer le tableau.

## Bilan
Malgré les obstacles rencontrés, nous avons également beaucoup appris grâce à ce projet. Les difficultés concernant le script nous ont poussées à nous documenter en ligne, plus particulièrement sur des forums (StackOverflow, etc.). Etant novices dans le domaine de la programmation, nous avons ainsi pu apprendre beaucoup de choses sur l'utilisation de commandes Bash telles que curl et lynx, notamment sur les problèmes d’encodage, ainsi que sed et grep. Afin de tester nos commandes, nous avons dû faire des petits scripts en Bash, par exemple pour compter le nombre de pages vides ou le nombre de fichiers mal encodés. Ces recherches que nous avons dû mener par nos propres moyens nous ont amenées à réfléchir : comment avoir recours à telle commande, à tel outil, et ainsi à comprendre la logique de la programmation. De la même manière, nous avons appris à utiliser le terminal et à être à l’aise avec l’utilisation courante de cet outil dont certaines d’entre nous ne connaissaient rien au début du Master. Nous avons également découvert l’HTML ainsi que tout l’envers du décor d’un site, dont nous ne connaissions que les grandes lignes.

Nous avons également appris beaucoup grâce à l’aspect multilingue de ce projet. Bien que nous soyons chacunes chargées d’étudier une langue, nous avons échangé et partagé nos informations. Ainsi, chacune d’entre nous a pu découvrir le fonctionnement des autres langues qu’elle ne connaissait pas. Nous avons aussi pu approfondir nos connaissances concernant nos propres langues, puisque nous avons choisi d’étudier des langues n’étant pas nos langues maternelles. Ce projet nous a également permis de développer notre culture des pays étudiés, grâce aux résultats de notre analyse, qui, rappelons-le, ne doit pas être prise trop au sérieux du fait de ses nombreuses imperfections.

Ce projet étant mené en groupe, nous avons également pu améliorer des compétences telles que l’esprit d’équipe et la collaboration. Nous avions chacune une langue à étudier, mais menions la même études, il était donc impossible de mener ce projet à bien sans un vrai travail d’équipe. Nous nous sommes beaucoup entraidées, notamment pendant la phase de création du script.

