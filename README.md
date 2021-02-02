# Oh my Git !

## Qu'est ce que Git ?

Git est de loin le système de contrôle de version le plus largement utilisé aujourd'hui. Git est un projet open source avancé, qui est activement maintenu. À l'origine, il a été développé en 2005 par Linus Torvalds, le créateur bien connu du noyau du système d'exploitation Linux.

Par sa structure décentralisée, Git illustre parfaitement ce qu'est un système de contrôle de version décentralisé (DVCS). Plutôt que de consacrer un seul emplacement pour l'historique complet des versions du logiciel comme c'était souvent le cas dans les systèmes de contrôle de version ayant fait leur temps, comme CVS et Subversion (également connu sous le nom de SVN), dans Git, chaque copie de travail du code est également un dépôt qui contient l'historique complet de tous les changements.

En plus d'être décentralisé, Git a été conçu pour répondre à trois objectifs : performances, sécurité et flexibilité.


<details>
      <summary>Cliquez ici pour déplier et en apprendre plus sur Git ...</summary>



### Performance

Les performances brutes de Git sont très élevées par rapport à de nombreuses alternatives. Commiter de nouveaux changements, créer des branches, faire des merges et comparer les anciennes versions… Toutes ces actions sont optimisées pour les performances. Les algorithmes implémentés dans Git tirent parti de connaissances approfondies sur les attributs courants des arborescences de fichiers de code source réel, la manière dont ils sont modifiés au fil du temps et les schémas d'accès.

Contrairement à certains logiciels de contrôle de version, Git n'est pas dupe des noms des fichiers au moment de déterminer le type de stockage et l'historique de version de l'arborescence des fichiers. Au lieu de cela, Git se concentre sur le contenu du fichier lui-même. Après tout, les fichiers de code source sont fréquemment renommés, partagés et réorganisés. Le format d'objet des fichiers du dépôt Git associe le codage différentiel (stockage de différences de contenu) et la compression ; en clair, il stocke explicitement les contenus du répertoire et les objets de métadonnées de version.

La décentralisation a également de grands avantages sur le plan des performances.

Par exemple, imaginons qu'Alice, une développeuse, apporte des changements au code source en ajoutant une fonctionnalité pour la version 2.0 à venir, puis qu'elle crée des commits de ces changements en y associant des messages descriptifs. Ensuite, elle travaille sur une deuxième fonctionnalité et réalise à nouveau des commits de ces changements. Bien sûr, ces changements sont stockés comme des tâches isolées dans l'historique de version. Par la suite, Alice bascule sur la branche de la version 1.3 du même logiciel pour corriger un bug qui n'affecte que cette version plus ancienne. Le but est de permettre à l'équipe d'Alice de livrer un correctif de bug, la version 1.3.1, avant que la version 2.0 ne soit prête. Alice peut ensuite retourner sur la branche 2.0 pour continuer à travailler sur de nouvelles fonctionnalités pour cette version ; le tout sans accéder au réseau, ce qui lui permet de travailler rapidement et efficacement. Elle pourrait même effectuer ces tâches à bord d'un avion. Une fois qu'elle est prête à envoyer tous les changements commités individuellement vers le dépôt distant, Alice peut les « pusher » en une fois.

### Sécurité

L'intégrité du code source géré a été la priorité absolue lors de la conception de Git. Le contenu des fichiers, les liens entre les fichiers et les répertoires, les versions, les tags, les commits : tous ces éléments du dépôt Git sont sécurisés à l'aide d'un algorithme de hachage sécurisé de façon cryptographique, appelé SHA1. Celui-ci protège le code et l'historique des changements contre toute modification accidentelle ou malveillante, tout en assurant une traçabilité complète de l'historique.

Grâce à Git, vous êtes sûr de disposer d'un historique authentique de votre code source.

D'autres systèmes de contrôle de version ne prévoient pas de protection contre des modifications secrètes à une date ultérieure. Toute organisation qui dépend du développement logiciel peut ainsi faire face à d'importantes failles de sécurité.

### Flexibilité

Lors de la conception de Git, l'un des principaux objectifs a été la flexibilité. Git est flexible à plusieurs niveaux : que ce soit pour la prise en charge de divers workflows de développement non linéaires, pour son efficacité dans l'élaboration de projets de différente envergure ou pour sa compatibilité avec de nombreux systèmes et protocoles existants.

Git a été conçu pour prendre en charge la création de branches et de tags en priorité (contrairement à SVN), et les opérations qui concernent les branches et les tags (comme les merges et les reverts) sont également stockées dans l'historique des changements. Peu de systèmes de contrôle de version offrent un tel niveau de suivi.

### Contrôle de version avec Git

Git est la solution idéale pour la plupart des équipes de développement actuelles. Si chaque équipe est différente et doit faire sa propre analyse, voici les principales raisons pour lesquelles le contrôle de version Git est l'option à privilégier :

### Git est un outil de qualité

Git offre les fonctionnalités, les performances, le niveau de sécurité et la flexibilité dont la plupart des équipes et des développeurs ont besoin. Ces avantages de Git sont repris en détail ci-dessus. Lorsqu'elles les comparent à d'autres solutions, beaucoup d'équipes préfèrent Git.

### Git s'est imposé comme la norme de facto

Parmi les outils du genre, Git est le plus adopté. Git séduit pour plusieurs raisons. Chez Atlassian, le code source de nos projets est essentiellement géré dans Git.

Un grand nombre de développeurs ont déjà travaillé avec Git, et il est fort probable qu'une proportion importante de jeunes diplômés ne connaissent que cet outil. Si certaines entreprises ont beaucoup de choses à apprendre au moment de passer d'un autre système de contrôle de version à Git, bon nombre de leurs développeurs actuels et à venir n'ont pas besoin de formation.

Outre le large pool de talents, la prédominance de Git implique aussi que de nombreux logiciels et services tiers sont déjà intégrés à Git y compris les IDE et nos propres outils, comme le client de bureau DVCS, Sourcetree, le logiciel de suivi des tickets et des projets, Jira, ainsi que le service d'hébergement de code, Bitbucket.

Si vous êtes un développeur inexpérimenté et que vous souhaitez acquérir des compétences utiles dans les outils de développement, en particulier le contrôle de version, Git doit figurer sur votre liste.

### Git est un projet open source de qualité

Git est un projet open source bien pris en charge, qui a bénéficié d'une gestion solide pendant plus de dix ans. Les mainteneurs de projet ont su faire preuve de jugement et ont adopté une stratégie réfléchie pour répondre aux besoins à long terme de leurs utilisateurs, en publiant régulièrement de nouvelles versions pour améliorer l'ergonomie et les fonctionnalités. La qualité du logiciel open source est évidente, et un nombre incalculable d'entreprises misent sur cette qualité.

Git est largement approuvé et compte une vaste base d'utilisateurs. La documentation est excellente et abondante : elle inclut des livres, des tutoriels et des sites web dédiés. Mais ce n'est pas tout : vous trouverez également des podcasts et des tutoriels vidéo.

La mise en open source réduit les coûts pour les développeurs amateurs, puisqu'ils peuvent utiliser Git gratuitement. Pour les projets open source, Git est incontestablement le successeur des anciennes générations de systèmes de contrôle de version ayant fait leurs preuves, comme SVN et CVS.

</details>


## Création de l'environnement Git

Lorsque je travaille sur Git, j'ai pris maintenant l'habitude de me créer à minima un environnement de travail dit classique. A savoir une branche **master** et une branche **develop**. Ma branche _master_ est ce que je vais appeler ma branche stable. Je développe donc dans ma branche _develop_. Dès que mon developpement de la branche _develop_ est stable, alors je fais un **merge request** de la branche _develop_ vers la branche _master_. Ainsi ma version _master_ reste toujours "propre", donc stable. 

J'utilise Git de plusieurs manières. Pour des développements simple ou je suis souvent seul contributeur, je n'utilise que ces 2 branches, elle me sont suffisantes. Cependant en entreprise, ou lors de développement plus complexe, j'utilise des branches supplémentaires. Lorsqu'une issue demande de grosse modification, lorsque je dois implémenter une nouvelle feature, etc, je créé une nouvelle branche basée sur ma branche _develop_, je travaille dans celle ci, puis lorsque mon travaille est stable, je merge le developpement de la nouvelle branche dans _develop_. Puis lorsque mon travaille est stable je merge tout dans _master_, ma branche stable. 

Ensuite il y a les tags. Les tags on se dire que ce sont nos **releases** (1.0, 1.1, 1.2, etc). Ainsi quand on developpe en continue qu'on à pas besoin de releases, pas besoin de les utiliser, mais lorsqu'on souhaite fournir à des clients ou des utilisateurs des releases dites _stable_, alors il faut en plus utiliser des tags. Mais rien de difficile vous allez voir. Une fois mon developpement prêt et testé, et validé, je me met dans ma branche master et je dis à Git de créer un __tag__ basé sur ma version actuelle (donc stable ci vous avez suivi ce que je dis). Donc si je sors une version 1.2 d'un programme, je tag ma version actuelle, et celle ci devriendra alors ma _release_ officielle 1.2. Si un bug apparait et que je dois le corriger alors je reprend le même cycle: develop > master > tag 1.2.1 > release. Tout simplement. Tout ça est géré dans git, par git. Easy non ? 

Si vous n'êtes pas un habitué du git vous devez vous dire mais qu'est ce que tu racontes, tu te rajoutes du travail la ? Et bien au final, lorsqu'on à pris l'habitude de travailler comme ça en fait on gagne énormement de temps. En plus de pouvoir développer à plusieurs sur un projet, on peut facilement versionner notre code, afficher les modifications entre plusieurs versions de code, revenir en arrière ... Bref les possibilités sont multiples. 

Mais mettez vous bien en tête que c'est avec la pratique que vous arriverez à utiliser puis maitriser cet incroyable outil. 

### Github

Je ne vais pas rentrer dans le débat Github / Gitlab, j'utilise les 2 plateformes. Ici je vais surtout parler de github. 

Avant tout, il est nécessaire de mettre sa clé SSH publique sur le serveur de Github (on peut travailler en https, mais je préfère ne pas taper mon mot de passe à chaque fois). Uploader sa clé ssh ici : https://github.com/settings/keys

### VSCode

Comme beaucoup de personne, j'utilise VSCode (ou VIM) pour développer. VSCode est super pour plein de raison. Il supporte nativement git, et permet de switcher de branche, pull, push, commit ... bref un super outil. Vous pouvez aussi installer des extensions pour vous aider avec git, mais pour une simple utilisation je pense que de base il sera très bien pour le commun des mortels :)

### Listes des différentes commandes

- [Créer un projet](https://github.com/SckyzO/Oh-My-Git/blob/main/creer_un_projet.md)
- 