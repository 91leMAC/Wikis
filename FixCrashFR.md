# Link to the Craft Document
https://www.craft.me/s/OfPNhukA0Cjb3A

## Markdown Code
**If you want to duplicate it, open the link to the craft document. And copy/paste into your own craft document

``` # Comment résoudre un crash modpack

*Tout tenter, et vous réussirez.*

---

Ce guide est spécialement créer pour résoudre tous les problèmes de crash lors d’un lancement d’instance, de chargement du monde ou de crash survenu dans le monde.

> *N’hésitez surtout pas à contribuer, donner des techniques, corriger si il y a des erreurs.*

> 💡Prennez de quoi noter à côter de vous, notez tous vos changements (pour éviter toute erreur  supplémentaire)

+ # Crash de lancement

> ⚠️**macOS** : chercher un fichier DS_store et le supprimer.

+ ## Analyser
   1. #### Lire le crash_report (dans le dossier crash-reports)

Si le crash_report est inutile utiliser la solution **suivante.**

> #### 💡Pour avoir du texte en couleur (cliquez ici)

1. Allez en bas à droite de VSCode et cliquez sur la case « Texte brut », une fenêtre va apparaître avec plusieurs formats de code, inscrivez « log », appuiez sur « enter ».

2. #### Lire les logs (dans le dossier `logs` )

Ouvrez les `latest.log` ils ont l’avantage de s'actualiser en direct (comme une console), vous pouvez voir en plus de vos erreurs, celles pendant le démarrage.

> Les logs peuvent parfois indiquer des choses que le **crash_report** ne peuvent pas montrer.

1. #### Vous n’avez pas trouvé la cause

Si le crash_report ne vous aide pas ou bien les logs référez-vous [ici](https://docs.craft.do/editor/d/cf60cb5e-0deb-d5d4-1ab3-9b0453fad6ab/EDDA604C-622B-438F-9BAA-51C303DDA94E/b/65728314-FF41-47BC-8D68-7B312C6A489F#56A59601-5BAB-4DC5-9296-C6EA40B977DD)

+ ## Tester

Par exemple, vous avez réussi à trouver l’erreur. Que ce soit une dépendance ou autre. Lancez votre modpack sans le mod mis en cause.

#### Résultats :

1. Le crash est réglé
2. [Cela renvoie sur un autre problème](https://docs.craft.do/editor/d/cf60cb5e-0deb-d5d4-1ab3-9b0453fad6ab/EDDA604C-622B-438F-9BAA-51C303DDA94E/b/65728314-FF41-47BC-8D68-7B312C6A489F#6228D0BB-7365-4977-844F-D89472C4E0BC)
3. L’erreure est la même.
   + ## Downgrader (opt)

> ❌ Technique peu efficace

L’intérêt de « downgrader » un mod c’est de résoudre une erreur sans perdre le mod. Cela peut prendre plus de temps que le supprimer, mais ça en vaut la chandelle.
Si vous souhaitez quand même l’utiliser, [demandez à l’auteur](https://docs.craft.do/editor/d/cf60cb5e-0deb-d5d4-1ab3-9b0453fad6ab/EDDA604C-622B-438F-9BAA-51C303DDA94E/b/65728314-FF41-47BC-8D68-7B312C6A489F#D9D2216D-1C9C-4525-B25B-BE6174378E7C) de régler le problème pour une prochaine mise à jour.

> Gardez à l’esprit que cela fonctionne assez rarement.

+ ## Désactiver

> ✅ Technique efficace

Désactiver un mod se fait le plus souvent à l’aide d’un launcher tel que Curseforge qui transforme le nomdumod.jar en nomdumod.jar_desactivate ou bien avec Atlauncher qui déplacera le mod dans un autre dossier externe au dossier `mods` cela est la meilleur option mais les incidents liés à ça sont mineurs (quasi inexistant).

## Renvoie du problème

Nous touchons un cas de figure spécial, admettons que vous ayez désactivé un mod et qu’un autre est mis en cause par le crash_report vous pouvez donc [supprimer](https://docs.craft.do/editor/d/cf60cb5e-0deb-d5d4-1ab3-9b0453fad6ab/EDDA604C-622B-438F-9BAA-51C303DDA94E/b/65728314-FF41-47BC-8D68-7B312C6A489F#9B58B949-4820-4356-94CD-C08034D31906) le nouveau mod découvert.

## Shotgun

> 💥Dernière solution

Cette technique de dernière nécessitée consiste à enlever tous les mods par ordre alphabétique jusqu'à temps que le modpack fonctionne, utilisez le launcher **Curseforge :**

1. Désactiver tous les mods de A - D
2. Lancer (si le crash persiste suivre la prochaine étape)
3. Désactiver tous les mods de E - J (etc…)

A la fin vous n’aurez plus beaucoups de mods d’activés mais vous pourrez enfin avoir un modpack qui fonctionne.

+ ## Demander de l’aide

Si vous n’avez pas réussi à trouver votre solution, l’aide de la communauté Minecraft va être la bienvenue. Allez dans [Discord](https://docs.craft.do/editor/d/cf60cb5e-0deb-d5d4-1ab3-9b0453fad6ab/EDDA604C-622B-438F-9BAA-51C303DDA94E/b/65728314-FF41-47BC-8D68-7B312C6A489F#48939F14-AD62-4545-8FCB-D80B67DB64C7)

+ ## Pour un mod en particulier

Allez sur la page Curseforge sur internet du mod, et cliquez sur la case Discord si il y a, sinon vous pourrez souvent trouver un lien dans la description du mod. Ecrivez une issue dans son [Github](https://docs.craft.do/editor/d/cf60cb5e-0deb-d5d4-1ab3-9b0453fad6ab/EDDA604C-622B-438F-9BAA-51C303DDA94E/b/65728314-FF41-47BC-8D68-7B312C6A489F#D9D2216D-1C9C-4525-B25B-BE6174378E7C) Vous pouvez tout aussi envoyer un commentaire sur le projet curseforge, mais l’auteur prendra plus de temps à y réponodre que dans Discord.

+ ## Pour un crash

### Discord :

> ⏩️ Solution Rapide

Voici une liste de différents serveurs discord communautaires qui pourront vous aider en fonction des erreures

| Discords                                                                   | Modpacks | Mods | Serveur |
| -------------------------------------------------------------------------- | -------- | ---- | ------- |
| [Minecraft Forge France](https://discord.com/invite/0uXCYNHVWGM8sAYS) 🇫🇷 | ✅        | ✅    | ❌       |
| [Iron Support](https://discord.gg/HypRqrdQ78) 🇫🇷                         | ✅❌       | ✅❌   | ✅       |
| [Modded Minecraft](https://discord.com/invite/moddedmc) 🇺🇸               | ✅        | ✅    | ❌       |
| [Minecraft Mod Development]( https://discord.tophatcat.dev/) 🇺🇸          | ✅        | ✅    | ❌       |
| [Fabric](https://discord.gg/v6v4pMv) 🇺🇸                                  | ✅❌       | ✅    | ❌       |

---

### Github :

> ⏯️ Solution lente, mais efficace

#### Comment ouvrir une issue ?

> Une issue est un moyen de signaler un problème, une suggestion, une question ou une demande sur un projet Github. Vous pouvez ouvrir une issue pour communiquer avec les auteurs ou les contributeurs du projet, ou pour participer à son amélioration.

# Étapes pour ouvrir une issue

1. Connectez-vous à votre compte Github sur [github.com](https://github.com/).

![CleanShot 2023-08-04 at 11.14.50.png](https://res.craft.do/user/full/cf60cb5e-0deb-d5d4-1ab3-9b0453fad6ab/doc/EDDA604C-622B-438F-9BAA-51C303DDA94E/1BA1ACDB-8D58-40EA-8D9E-4332E289EC27_2/zEcT3nAOOkyR4temNMCb4NlQBx1LQPwyG7l6ocaU3mIz/CleanShot%202023-08-04%20at%2011.14.50.png)

2. Naviguez vers la page principale du projet sur lequel vous voulez ouvrir une issue. Par exemple, si vous voulez ouvrir une issue sur le projet Industrial Reborn, allez sur [https://github.com/GabrielOlvH/Industrial-Revolution](https://github.com/GabrielOlvH/Industrial-Revolution) par exemple.

![CleanShot 2023-08-04 at 11.16.17.png](https://res.craft.do/user/full/cf60cb5e-0deb-d5d4-1ab3-9b0453fad6ab/doc/EDDA604C-622B-438F-9BAA-51C303DDA94E/7CBF49E1-5CF2-49FF-83AD-705520742D36_2/aNtRsK3cu8gF92kcrswuImMCqtIzHGyWbTMrGfdzJ8wz/CleanShot%202023-08-04%20at%2011.16.17.png)

3. Sous le nom du projet, cliquez sur **Issues**. Vous verrez la liste des issues déjà ouvertes pour ce projet.

![CleanShot 2023-08-04 at 11.17.07.png](https://res.craft.do/user/full/cf60cb5e-0deb-d5d4-1ab3-9b0453fad6ab/doc/EDDA604C-622B-438F-9BAA-51C303DDA94E/D603B7AC-7D39-4A52-92FE-8580EBA565E9_2/sObuSVzz6OJgT9qeiUJMuxxxnOlWSRM1p0tCgilM1Akz/CleanShot%202023-08-04%20at%2011.17.07.png)

4. Cliquez sur **New issue**. Si le projet utilise des modèles d’issue, choisissez le type d’issue que vous voulez ouvrir, puis cliquez sur **Get started**. Sinon, cliquez sur **Open a blank issue**.

![CleanShot 2023-08-04 at 11.18.16.png](https://res.craft.do/user/full/cf60cb5e-0deb-d5d4-1ab3-9b0453fad6ab/doc/EDDA604C-622B-438F-9BAA-51C303DDA94E/3A078945-E28A-4B76-85BA-20B600972FD9_2/2iUc6O3ikBvaqnNoRStt2FydonKqXScsF9WhyrdWje8z/CleanShot%202023-08-04%20at%2011.18.16.png)

5. Donnez un titre à votre issue qui résume votre problème ou votre demande. Par exemple, “Bug avec le générateur solaire” ou “Suggestion pour ajouter un module de stockage”.

![CleanShot 2023-08-04 at 11.21.45.png](https://res.craft.do/user/full/cf60cb5e-0deb-d5d4-1ab3-9b0453fad6ab/doc/EDDA604C-622B-438F-9BAA-51C303DDA94E/76C9E391-C67B-4206-91A2-C44C77743006_2/hvriCFCAFGUvCyujZIYODThWDlHkWS2EOfve9oMER5Ez/CleanShot%202023-08-04%20at%2011.21.45.png)

6. Décrivez votre issue en donnant plus de détails, comme les étapes pour reproduire le problème, les versions du jeu et du mod utilisées, les captures d’écran ou les [logs](https://mclo.gs/) si possible. Utilisez le formatage Markdown pour mettre en forme votre texte. Vous pouvez consulter la [documentation Markdown](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) pour plus d’informations.

> 💡Pour les logs merci de les mettre dans : [https://mclo.gs/](https://mclo.gs/)

7. Si vous voulez mentionner d’autres utilisateurs Github dans votre issue, vous pouvez utiliser le symbole @ suivi de leur nom d’utilisateur. Par exemple, @GabrielOlvH pour mentionner l’auteur du projet Industrial Reborn.

![CleanShot 2023-08-04 at 11.26.29.png](https://res.craft.do/user/full/cf60cb5e-0deb-d5d4-1ab3-9b0453fad6ab/doc/EDDA604C-622B-438F-9BAA-51C303DDA94E/528981E1-B1F9-4545-9E6D-FC1C2B9DA133_2/o8LcJwTCqoFjRL91MWIt6o79k3MOl5uAr6L4KMO8FHoz/CleanShot%202023-08-04%20at%2011.26.29.png)

8. Quand vous avez terminé de rédiger votre issue, cliquez sur **Submit new issue**. Votre issue sera créée et visible par les autres utilisateurs.

![CleanShot 2023-08-04 at 11.26.58.png](https://res.craft.do/user/full/cf60cb5e-0deb-d5d4-1ab3-9b0453fad6ab/doc/EDDA604C-622B-438F-9BAA-51C303DDA94E/7FB2E412-E497-46F4-AB93-7D6DC659C032_2/CX4B8CIyrl6ZgUuKxCiXfthkLHcaufgJxVjUEx8D7Bwz/CleanShot%202023-08-04%20at%2011.26.58.png)

> 💡Activez les notifications de Github, il serai dommage de ne pas recevoir de notification et de faire attendre la personne qui veut vous aider.

Pour ouvrir une demande de support aller dans le projet de l’auteur et accédez à l’onglet « issues » :

1. Regardez les issues fermés, peut être d’autres joueurs ont ils eu la même erreur ?
2. Regardez les issues ouvertes, un doublons d’issue ne sert à rien

---

+ # Cas de figure

> Voici différents cas de figures de crash qui ont pour utilité d’éviter que vous faites des erreures qui vous prennent du temps et de l’énergie à résoudre.

+ ## Crash à l’ajout de mods

## Contexte

> Je créer un modpack qui comporte beaucoups de mods. Je gère ça avec le launcher Curseforge. Mon but ici est d'ajouter des mods, plus je vais en rajouter plus les probabilités de crash seront élevées.

## Erreur

Ayant beaucoup de mods, certains demande une mise à jour. Arrivé dans le menu d’ajout de mods certains mods demanderons une mise à jour, je vais mettre à jour les mods qui se présentent à moi, puis j’en ajoute une cinquentaine de mods en plus.

Je lance le modpack, celui-ci crash avec un crash_report qui n’indique la cause de presques aucuns mods (ou met en cause un mod qui fonctionne très bien avant d’ajouter et de mettre à jour **d**’**autres** mods.

## Solution

1. Dupliquez votre modpack avant ajouts de mods. Travaillez seulement sur une autre version, comme ça vous pourrez recommencer sur une version saine cela vous ferra économiser du temps.
2. Ne mettez à jour les mods avant d’ajouter d’autres mods.
3. Mettez à jour et ajouter les mods 5 par 5.

# Notes de l’auteur

#### À écrire plus tard

Donner des cas de figure (aj de mods, et maj puis crash)

Crash dans un monde

→ Trouver la nature (mod de génération, entitée, autre…)

Crash de connection à un serveur

→ Mismatched mods channel list.

→ packet limit

```
