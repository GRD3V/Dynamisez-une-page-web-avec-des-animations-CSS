# Dynamisez une page web avec des animations CSS

[![PREVIEW](https://img.shields.io/badge/PREVIEW-17F?style=for-the-badge)](https://grd3v.github.io/Dynamisez-une-page-web-avec-des-animations-CSS/)

## Build

```bash
# build html & scss
npm run build

# or watch html & scss
npm run watch
```

### Enfin

Ouvrez le fichier `dist/index.html` avec votre navigateur

---

![Bannière scénario](https://user.oc-static.com/upload/2022/06/28/16564030859322_Banner_Sce%CC%81nario.png)
Vous avez intégré Ohmyfood en tant que développeur junior. Il s’agit d’une jeune startup qui voudrait s'imposer sur le marché de la restauration. Déjà présente à New-York, elle souhaite désormais faire sa place à Paris.
![Bannière du site Ohmyfood](https://user.oc-static.com/upload/2022/06/22/16559011566667_FR_1117_P4_Banner-Ohmyfood.png)

**Votre mission** est de **développer un site “mobile first” qui répertorie les menus de restaurants gastronomiques**. En plus des systèmes classiques de réservation, les clients pourront composer le menu de leur repas pour que les plats soient prêts à leur arrivée. Finis, les temps d'attente au restaurant !

L’équipe commerciale a déjà réussi à convaincre 4 restaurateurs d’utiliser la plateforme OhMyFood. Paul décide alors que le site contiendra 4 menus dans un premier temps.

À deux, vous avez pu établir ce [brief créatif](https://course.oc-static.com/projects/D%C3%A9veloppeur+Web/IW_P4+Animations+CSS+Ohmyfood/Brief+cr%C3%A9atif+site+Ohmyfood.pdf) pour rassembler toutes les informations clés du projet de développement du site.

Le projet va pouvoir commencer. Paul vous envoie les maquettes par e-mail :

> **Objet :** Maquettes site OhMyFood Paris
> **De :** Paul
> **À :** moi
>
> Bonjour !
>
> L’UX designer a finalisé les **maquettes mobile et desktop** du site ! Tu les trouveras en pièce jointe, en plus du dossier des sources du site (images et textes). Tu y trouveras également le prototype du site via Figma, incluant les animations et comportements à intégrer. Voici un extrait de ce à quoi devra ressembler le site :
> ![Extrait des maquettes mobile et desktop](https://user.oc-static.com/upload/2022/06/22/16559016787093_Untitled%20design.png)
> Il n’y a plus qu’à le **développer pour mobile, tablette et desktop** en s’appuyant rigoureusement sur les informations déterminées dans le brief créatif ! Pour rappel, le site doit être **responsive** et en **“mobile first”**. On veut aussi des animations soignées. Il faudra que tu m’expliques comment elles fonctionnent.
>
> Hâte de voir le site terminé !
>
> Bon courage !
>
> Paul
>
> > **Pièce jointe :**
> >
> > - [Maquettes mobile et desktop du site Ohmyfood](https://www.figma.com/file/t4449fzDnwGYmzuwQdu87V/Projet-3-FR---Ohmyfood?node-id=0%3A1)
> > - [Prototype du site](<https://www.figma.com/proto/t4449fzDnwGYmzuwQdu87V/Maquettes-Ohmyfood-(mobile-et-desktop)?node-id=25368-591&scaling=scale-down&page-id=0%3A1&starting-point-node-id=25368%3A591&show-proto-sidebar=1>)
> > - [Fichiers sources (images et textes)](https://course.oc-static.com/projects/D%C3%A9veloppeur+Web/IW_P4+Animations+CSS+Ohmyfood/Images+et+textes+Ohmyfood.zip)

Vous avez désormais tous les éléments pour construire le site. Vous vous lancez dans cette nouvelle aventure !

> ### Rappel
>
> Pour rappel, afin de vous aider à réaliser ce projet, vous pouvez consulter **[ce guide d’étapes à suivre](https://course.oc-static.com/projects/D%C3%A9veloppeur+Web/IW_P4+Animations+CSS+Ohmyfood/Guide+d%E2%80%99e%CC%81tapes+cle%CC%81s+%E2%80%93+Ame%CC%81liorez+l'interface+d'un+site+mobile+avec+des+animations+CSS.pdf)**, qui contient des recommandations et des ressources pour organiser votre travail.

![Bannière livrables](https://user.oc-static.com/upload/2022/06/27/16563220599551_Banner_Livrables.png)

1. Un fichier au format PDF ou TXT contenant :
   Le lien vers votre repository **GitHub**.
   Le lien de la version en ligne de votre site Internet.

> ### Rappel
>
> Pour faciliter votre passage devant le jury, déposez sur la plateforme, dans un dossier ZIP nommé “**Titre_du_projet_nom_prénom**”, tous les livrables du projet comme suit : **Nom_Prénom_n° du livrable_nom du livrable\_\_date de démarrage du projet**. Cela donnera :
>
> - Nom_Prénom_1_repository_mmaaaa
>
> Par exemple, le premier livrable peut être nommé comme suit : Dupont_Jean_1_repository_012022.

![Bannière soutenance](https://user.oc-static.com/upload/2022/06/22/16559012528213_Banner_Soutenance_Dev.png)
Durant la présentation orale, l’évaluateur interprétera le rôle de Paul, le CTO. La soutenance est structurée de la manière suivante :

- **Présentation des livrables (15 minutes)**

  - Dans un premier temps, vous expliquerez vos choix techniques concernant la conception du site.
    - Vous aborderez :
      - comment vous avez réalisé l’animation du cœur ;
      - comment vous avez réalisé le sélecteur de plat ;
      - votre choix pour le loader de la page d’accueil ;
      - comment vous avez abordé le code du projet en mobile first.

- **Discussion (10 minutes)**

  - Toujours dans le rôle de Paul, votre évaluateur vous posera des questions. Il pourra vous challenger sur les points suivants :
    - la façon dont vous avez réalisé les animations ;
    - vos choix pour l’organisation de votre code CSS ;
    - la façon dont vous avez abordé le responsive du site.

- **Debrief (5 minutes)**
  - À la fin de la soutenance, l'évaluateur arrêtera de jouer le rôle de Paul pour vous permettre de débriefer ensemble.

> ### Attention
>
> Votre présentation devra durer 15 minutes (+/- 5 minutes). Puisque le respect de la durée des présentations est important en milieu professionnel, les présentations en dessous de 10 minutes ou au-dessus de 20 minutes peuvent être refusées.

#### Compétences évaluées

- Mettre en œuvre des effets CSS graphiques avancés
- Mettre en place une structure de navigation pour un site web
- Assurer la cohérence graphique d'un site web
- Utiliser un système de gestion de versions pour le suivi du projet et son hébergement
- Mettre en place son environnement Front-End
