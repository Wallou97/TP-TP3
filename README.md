# TP-TP3
1\) Présentation de l’application

L'application Caribus de l’équipe 7 est une Interface Web Map interactive, qui vous permet de sélectionner un quartier de Montréal pour vous informer sur l'activité du quartier.

On retrouve sur cette interface, plusieurs commodités de la ville de Montréal mise à disposition de la population : les transports en commun, les parcs, les stations de bixi. On retrouve également des trajets de vélos, qui ont montré la densité de circulation des vélos.  Cette interface donne directement l'accès à d'autres informations pertinentes de la part de la ville, via des hyperliens. Ceci vous permet d'évaluer votre quartier de choix en termes de commodités. Il est possible de générer des analyses statistiques en fonction de la commodité choisie.

![](https://lh7-us.googleusercontent.com/99Ba6Rytbbsq6qRYM7MTuS0z3WTJAb5U8ROCBwKSbA8b5P-6DA5rAHM_f482NsW1dXYtUEKs4CklUcMZyGvrZJlkKPwPrnGVDvWM3VXTFm-cf-CdrxCHTxCcYJTG7TyWuwrj4mVqAwKoUO0BUTyZGQ4)

 

2\) Travaux réalisés 

Dans cette partie nous présenterons les travaux réalisés pour la construction, l'analyse et le développement des données vectorielles, json, etc…

a. Présentation des différentes fonctions du js

Ici vous trouverez les différents Js écrit pour l’application 

![](https://lh7-us.googleusercontent.com/wP1reNcnlKE1rjGPoqk8z1KZpFY9dWiTviWPF2kqVS3yg15TACXzFvM_jDL4JPQ9vl9MhDI7iNk7CmUjz4w7rZW1vTLbKuSxtfhXPhCCAqAkItJljbb6g75pQVxHx3AsCcUKueRS5jjwIXlIZygGtW0)

 

Je vous présente le code des pistes cyclables de Montréal, avec l’ajout du côté source  et des couches DD891050.piste\_cyclabe\_2

![](https://lh7-us.googleusercontent.com/GaTe1kuhgAO8TxdY5rnxa43I5S5ZZM4jS8Jai27zndpkvQUu7likjNBZhopbM9odq9vE6mE_Quk9AWGZPTUXdZDYuL7IsIw-XxwH1JMADlRv89utUBTYw2lXZy2UdBGlZBpB7cj-STwTFwd-ZEf-36U)

 

Ici, on présente le code pour effectuer l’action checkbox : 

 

![](https://lh7-us.googleusercontent.com/WhwGDdO8X1qQcXdwP3slChPgKUwa1YvWVpRifUkyA4tmOZqHo1Ep9PK3IKpESdCk7VBmjifEt7NxtBS5snCqzELXLlB2J5dwpitvfz7xOFrs1mKrx1_AKLTYAtlXm9HRGHSI7ZQNNSFWCPgDKC7wFnE)

La base de ses codes est utilisée pour tout la donnée liée à une action check.

Les Js heatmap, creategrid, et d'autres js vus en cours sont utilisés pour les analyses de données de notre application.

b. Présentation du bottom menu et du right menu

i. Bottom Menu 

Le bottom Menu a été choisi pour avoir une interface facilement compréhensible et visible avec un codage du Html. Nous avons choisi de combiner deux codes, la fabrication de colonne et les checkbox.

Ici un bout du code :

![](https://lh7-us.googleusercontent.com/lFVmM34WX8AsjrkjJQXN3MTBgXIHXRh5mbyN6JvtDmFc92ZNiwAT9f4x-DgSVDOpbpXAsPwbDteSvjisIJ2Btun-TaMvkrQhYNu_JQq9M7OG6ZywMYWGlHA9vSfXQXIpJyClhO25tO3TzWbf4RuklXU)

 

Un bouton restart map a été ajouté pour supprimer d’un clic toutes les couches sélectionnées.

 ![](https://lh7-us.googleusercontent.com/HUMpW46KoZPOA1hFrV0jfwuCbfhuMV8e5ySV6lpI6MiFm-s-T4lDWySQrbdK5_1W8DNOptHWoynWFU_tWKEo4w3NDrmerfmx7OECNCZ9etj8iOrM0gjtiyesyQYtEZqlY1gfAYsB4rGURzpF4dL327U)

ii. Right Menu 

Dans le right Menu on retrouve le nom de notre interface, avec une brève description, de la fonctionnalité de l’application. On retrouve un menu déroulant avec les noms des quartiers de Montréal

 ![](https://lh7-us.googleusercontent.com/rLDTT3wT7N60FGw_iGUgzqjHaoinfNAKL8Y4c66055Siy3VKpoNi5wH6wE2vKUkEAvnrSkJCdLben-xyJebIk0ICX5H3MYaXHG5TRNcOrsSOb6WoXQog3Af6eRgkLAwXdLZlr7lTSh3gy5Kar9CHTFQ)

Code associé est le suivant :

![](https://lh7-us.googleusercontent.com/clmDuw7toYjCebXpK4G7Vawku6wicBdCeR3TpXdqIOrt4UMVc2rUQ2F1wrggs4vNMvxaQddQCqTx34i-zDeH9hDxhWlidxynrh9KduEk6fWRFWqxYXUyF48htTH1FCeXG2glP16wUdSDzSU9cSNOwnc)

 

Des boutons et des hyperliens ont été ajoutés.

 

 ![](https://lh7-us.googleusercontent.com/VrM5LHNlDWHZf09_lgf4lVNOCHQSqj0k5qh1YveuLA9UvSiDShCcaB98CcEjG0qFXUzwK4TX3tqqSyEqwMeHNUpabdUNFDG-6C43rGTKJ3MByK2hLh_a8x6uo3V5bq4vuRTH7TxMr1yaK2RljUDDMo4)

![](https://lh7-us.googleusercontent.com/NmwIT8nOQ8NLI0T2oByKc_mK4DzyUhoZcFhq_He9TdzuTpxr8HDXASekcz0MIpDwiE-Xo1DqMaMv51tYaZq7G5UumKd4CgMsC4Ysz0wVR8fP1vYO9tDd7XAuayLPS5_onU0iOtEm7Qyh6SIHiMCty38)

3\) Produit finale

L’application finale, Caribus, est facile à utiliser ! L’utilisateur a simplement à choisir les informations à afficher sur la carte de Montréal en cochant une ou plusieurs cases parmi les neuf choix en bas de la page (pistes cyclables, stations bixi …). Cela dit, l’utilisateur peut aussi faire marche arrière et désélectionner une ou plusieurs options pour ne plus l' afficher. Aussi, sur le côté droit de la page, l’utilisateur a la possibilité de télécharger des carte WFS, le heatmap ou encore la carte hexagonale 3D en faisant le choix par un simple clic.

4\) Evolution

Dans cette partie nous discuterons de l’évolution du projet Caribus de l’équipe 7.

En début de session, nous avons voulu travailler sur l’aspect transports en commun et transports verts. Nous avons envisagé incorporer les stations de métro, les lignes de bus, les stations Bixi avec l’ensemble de pistes cyclables, mais aussi les parcs, les aéroports (comme source de nuisance sonore), la densité de population par quartier ainsi que des photos aériennes. L’idée du début était de concevoir un Atlas s’adressant aux planificateurs urbains leur permettant d’évaluer l’état du réseau de transport en commun et du transport vert afin de planifier l’ajout de nouvelles pistes cyclables, ou modifier certaines lignes de bus etc…mais aussi de permettre aux usagers de planifier leurs déplacements en évitant les zones bruyantes, ou en ciblant les quartiers les mieux desservis par les transports en commun ou de loisir.

En cours de route nous avons mis de côté les photos aériennes et la densité de population par quartier car elles sont difficiles à traiter.

Le projet a évolué bien évidement, soit parce que certaines idées n’ont pas fonctionné comme voulues, soit parce que nos idées ont évolué. Le projet final offre un aperçu, par quartier, des commodités telles que le transport, l’hébergement ou autres, en ayant la possibilité de visualiser les quartiers d’intérêt, afin d’obtenir les informations souhaitées.

 ![](https://lh7-us.googleusercontent.com/mRgmY75IMKPzIUxgrbmkmrD2JzKLd5NyKnVOWSFeSTy6kKGfw0mM1M6ZzP1TKNmoUWVsfUtKG7XZND-3fkZaDfzklAoiI1CHIUmAfXktchMUZNpy9-VfxjSBV_cn3C8SDj-iZGwASa5vDWZ63NqZDPQ)

Il y a également la possibilité de cliquer sur des liens hyperlinks envoyant l’utilisateur vers des sites web, de la ville de Montréal, par exemple, ou d’un site d’hébergement, afin de pouvoir affiner leur recherche de logement sur un quartier voulu.

 

![](https://lh7-us.googleusercontent.com/F_mwoYQTftG29rMsP_wxE6fPoyc1KJ2VZsvcx2uwAx2l9vsnjTGC85cPyerjG-g7AiQOvz-JZ9XHqulhx1V5Xn-I514_loFevbwXUocFC8zeudq36MoQeJkOKN99-886zyfoLSNV1tMQWUfB3ybF224)

5\) Problème rencontré 

Dans cette partie nous décrirons les problèmes rencontrés lors de la mise en forme de notre application. 

Les problèmes rencontrés étaient nombreux. À commencer par les problèmes liés au code, à l’apprentissage du HTML, CSS et JS. Aussi, il a fallu du temps pour aller trouver les fonctions déjà existantes pour en choisir celles qui nous intéressent. Un problème majeur fut celui de « pousser » les branches pour la vérification. 

De grandes difficultés sont rencontrées avec le traitement des couches afin de proposer une variété d’analyses spatiales et visuelles , telles que Heatmap et la statistique 3D.
