<h1 align="center">Welcome to Ohmyfood</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/VGMSoft/VirgileGuglielmi_3_13122020#readme" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/VGMSoft/VirgileGuglielmi_3_13122020/graphs/commit-activity" target="_blank">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" />
  </a>
  <a href="https://github.com/VGMSoft/VirgileGuglielmi_3_13122020/blob/master/LICENSE" target="_blank">
    <img alt="License: ISC" src="https://img.shields.io/github/license/VGMSoft/Ohmyfood" />
  </a>
  <a href="https://twitter.com/virgilegug" target="_blank">
    <img alt="Twitter: virgilegug" src="https://img.shields.io/twitter/follow/virgilegug.svg?style=social" />
  </a>
</p>

> Using a CSS preprocessor (i.e SASS / SCSS) & Using CSS Animations / @keyframes

>Technologies<br/>
  ● Le développement en CSS, sans JavaScript.<br/>
  ● Aucun framework utilisé, SASS .<br/>
  ● Aucun CSS inline.

>Compatibilité<br/>
La cible étant les personnes connectées et pressées, le site est développé en utilisant l’approche mobile-first.<br/>
  ● L’ensemble du site est responsive sur mobile, tablette et desktop.<br/>
  ● Les pages remplissent les conditions de la validation W3C en HTML et CSS.<br/>
  ● Le site est compatible avec les dernières versions desktop de Chrome et Firefox.

>Contenu des pages<br/>
  Page d’accueil (x1)<br/>
    ● Affichage de la localisation des restaurants. À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu.<br/>
    ● Une courte présentation de l’entreprise.<br/>
    ● Une section contenant les 4 menus sous forme cartes. Au clic sur la carte,
    l’utilisateur est redirigé vers la page du menu.<br/>
  Pages de menu (x4)<br/>
    ● 4 pages contenant chacune le menu d’un restaurant.<br/>  
  Footer<br/>
    ● Le footer est identique sur toutes les pages.<br/>
    ● Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.<br/>
  Header<br/>
    ● Le header est présent sur toutes les pages.<br/>
    ● Sur la page d’accueil, il contient le logo du site.<br/>
    ● Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil

>Effets graphiques et animations<br/>
    Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils utilisent les animations ou transitions CSS, pas de JavaScript ni de librairie.<br/>
  Boutons<br/>
    ● Au survol, la couleur de fond des boutons principaux s’éclaircit légèrement et l’ombre portée est plus visible.<br/>
    ● À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il se remplir progressivement. Pour cette première version, l’effet apparaît au survol sur desktop au lieu du clic.<br/>
  Page d’accueil<br/>
    ● Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, nous en proposons un aperçu. Il apparaît pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvre l'intégralité de l'écran, et utilise les animations CSS (pas de librairie).<br/>
  Pages de menu<br/>
    ● À l’arrivée sur la page, les plats apparaissent progressivement avec un léger décalage dans le temps.<br/>
    ● Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche coulisse de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il est rogné avec des points de suspension. Un exemple de l’effet attendu est fourni.

### 🏠 [Homepage](https://github.com/VGMSoft/VirgileGuglielmi_3_13122020/)

### ✨ [Demo](https://vgmsoft.github.io/VirgileGuglielmi_3_13122020/)

## Fork

```sh
https://github.com/VGMSoft/VirgileGuglielmi_3_13122020.git
```

## Usage

```sh
sass --watch ./sass/main.scss:./public/css/styles.css
postcss --watch ./public/css/styles.css --use autoprefixer -d ./public/css/prefixed/
build npm run sass & npm run prefix
```

## Author

👤 **Virgile Guglielmi**

* Website: virgileg.com
* Twitter: [@virgilegug](https://twitter.com/virgilegug)
* Github: [@VGMSoft](https://github.com/VGMSoft)
* LinkedIn: [@Virgile Guglielmi](https://linkedin.com/in/Virgile Guglielmi)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/VGMSoft/VirgileGuglielmi_3_13122020/issues). You can also take a look at the [contributing guide](https://github.com/VGMSoft/VirgileGuglielmi_3_13122020/blob/master/CONTRIBUTING.md).

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2021 [Virgile Guglielmi](https://github.com/VGMSoft).<br />
This project is [ISC](https://github.com/VGMSoft/VirgileGuglielmi_3_13122020/blob/master/LICENSE) licensed.

***
_This README was generated with by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_