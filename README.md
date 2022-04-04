Ce document explique le fonctionnement du github emmausConnect, il peut être changé à tout moment et est le plus à jour possible.
<br />

#### Les termes:<br />
repo/dépôt : un projet sur github, par exemple https://github.com/emmausConnect/inspector.<br />
utilisateur/profil github/un github : un compte github (login/mdp + email).<br />
<br />

### 0 Le but
[Emmaüs-connect](https://emmaus-connect.org/) est une association qui est très étendue géographiquement, les valeureux bénévoles sont séparés la distance. Mais internet et le téléphone sont arrivés et les bénévoles commencent a être plus au contact. Plusieurs bénévoles ont commencé à développer des outils pour faciliter leur bénévolat dans [Emmaüs-connect](https://emmaus-connect.org/) mais ces outils sont généralement tenus/développés uniquement par ses créateurs originaux. Mais github et l'open source sont arrivés et plusieurs bénévoles peuvent à présent améliorer les outils de [Emmaüs-connect](https://emmaus-connect.org/) même s'ils ne sont pas ses créateurs originaux. C'est dans ce but que le github emmausConnect est créée, réduire la quantité d'effort à fournir individuellement pour augmenter la qualité de nos outils.<br />


### 1 Quels outils sont nécessaires pour participer à un github emmausConnect ?
* maîtriser grossièrement le fonctionnement de git, github.
* avoir [**un**](https://git-scm.com/downloads/guis) outil des suivants pour pouvoir interagir avec github (par exemple sourcetree).
* une adresse mail.

### 2 Ce qui n'est pas forcément requis
* des compétences en programmation.

### 3 Comment créer un dépôt pour votre projet sur emmausConnect ?
Disons que vous voulez créer un projet superProjet.<br />
Créer d'abord superProjet dans un dépôt soit en local ou mieux sur votre propre profil github.<br />
Une fois que votre projet a une première version fonctionnelle (cad qui marche et qui peut être utilisée par les bénévoles/bénéficiaires de l'association).<br />
Vous devez demander à un membre de [Emmaüs-connect](https://emmaus-connect.org/) de vous parrainer pour être intégré au github emmausConnect.<br />
Une fois que vous êtes un membre de confiance, emmausConnect créée votre superProjet à cette adresse https://github.com/emmausConnect/superProjet (remplacer superProjet dans l'URL).<br />

### 4 Comment rejoindre un projet existant sur emmausConnect ?
Il faut demander la permission à un utilisateur qui a les droits sur le dépôt du projet.<br />
La liste des utilisateurs qui ont les droits sur le dépôt est dispo dans la liste des contributeurs.<br />
L'utilisateur qui a les droits sur le repo choisit de vous faire confiance ou pas en fonction.<br />

### 5 J'ai obtenu les droits sur le repo comment le connecter sur mon logiciel
Vous avez les droits 3 ou 4. Maintenant il faut vous connecter à github, il y a plusieurs moyens disons la méthode du token dans un premier temps.<br />
Ajouter simplement l'url de synchronisation (ou remote) dans votre outil : https://ecolyon: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@github.com/emmausConnect/superProjet.<br />
Voici le format de l'url : https://ecolyon:TOKEN@github.com/emmausConnect/PROJET<br />
Avec le token TOKEN qui vaut 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 et le projet PROJET qui vaut superProjet.<br />
Remplacer superProjet dans l'url par le projet sur lequel vous allez.<br />
Vous devez vous générer un token depuis votre compte github en suivant cette [procédure](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) uniquement la permission "repo" est requise.<br />
Vous avez maintenant un logiciel correctement configuré.

### 6 Sécurité sur les droits d'accès au dépôts ?
Les utilisateurs ne peuvent pas casser les choses qu'ils n'ont pas été autorisé à casser. <br />
Par exemple sur emmausConnect deux projets recondapi et inspector sont attribués à deux utilisateurs ex jean qui est autorisé sur recondapi et jack sur inspector.<br />
Si jack deviens diabolique il ne peut casser que le projet inspector les autres utilisateurs ne souffre pas de ce problème. L'administrateur emmausConnect bloque l'utilisateur jack fin du problème.

### 7 Confidentialité sur les dépôts ?
Par défaut les dépots sur github sont créée en privé ce qui veut dire que ce que vous mettez dedans reste entre la plateforme et vous. Quand le projet (si vous voulez le rendre publique) est prêt, on peut regarder et changer sa visibilité sur publique.

### 8 Propriété sur le code ?
La propriété sur le code dans les dépôts de emmausConnect reviens à l'association [Emmaüs-connect](https://emmaus-connect.org/) pour bien que ce soit clair pour les personnes qui consultent le dépôt, il est conseillé d'ajouter un fichier LICENSE.md à la racine du dépôt comme par exemple [ici](/LICENSE-MIT.md). Pour les bénévoles qui veulent garder la propriété sur le code la meilleure solution est de créer le projet sous leur propre compte github.

### 9 Politique de emmaüs-connect sur le github emmausConnect
Tous les projets de ce github ont pour vocation de contribuer, d'améliorer le service que [Emmaüs-connect](https://emmaus-connect.org/) apporte aux personnes bénéficiaires.<br />
L'association [Emmaüs-connect](https://emmaus-connect.org/) est au courant de ce github et à bien donné son feu vert.<br />
